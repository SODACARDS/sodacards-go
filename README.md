# SODACARDS Go SDK

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Docs](https://img.shields.io/badge/docs-developers.sodacards.com-003087.svg)](https://developers.sodacards.com)
[![Go Reference](https://pkg.go.dev/badge/github.com/SODACARDS/sodacards-go.svg)](https://pkg.go.dev/github.com/SODACARDS/sodacards-go)

The official Go client for the [SODACARDS Developer API](https://developers.sodacards.com) — sell gift cards and game top-ups from your own systems, across West Africa.

Browse the catalog, place orders, retrieve delivered codes, and subscribe to webhooks.

## Requirements

Go 1.23 or newer.

## Installation

```sh
go get github.com/SODACARDS/sodacards-go
```

## Authentication

Every request is authenticated with an API key that you generate from the [developer dashboard](https://developers.sodacards.com). Keys are prefixed `sc_live_` (production) or `sc_test_` (sandbox); the sandbox returns fake codes so you can integrate safely.

The key is passed through the request context — load it from the environment, never hard-code it.

```go
auth := context.WithValue(
    context.Background(),
    sodacards.ContextAPIKeys,
    map[string]sodacards.APIKey{"ApiKeyAuth": {Key: os.Getenv("SODACARDS_API_KEY")}},
)
```

## Quickstart

```go
package main

import (
    "context"
    "fmt"
    "os"

    sodacards "github.com/SODACARDS/sodacards-go"
)

func main() {
    client := sodacards.NewAPIClient(sodacards.NewConfiguration())
    auth := context.WithValue(
        context.Background(),
        sodacards.ContextAPIKeys,
        map[string]sodacards.APIKey{"ApiKeyAuth": {Key: os.Getenv("SODACARDS_API_KEY")}},
    )

    // 1. Discover what you can sell.
    catalog, _, err := client.DefaultAPI.ListCatalog(auth).Execute()
    if err != nil {
        panic(err)
    }
    fmt.Println(catalog)

    // 2. Place an order for one product.
    line := sodacards.NewSodacardsDevpublicV1OrderLine()
    line.SetProductId("prod_123")
    line.SetQuantity(1)

    body := sodacards.NewSodacardsDevpublicV1PlaceOrderRequest()
    body.SetLines([]sodacards.SodacardsDevpublicV1OrderLine{*line})
    body.SetReference("my-internal-ref-0001")

    order, _, err := client.DefaultAPI.PlaceOrder(auth).
        SodacardsDevpublicV1PlaceOrderRequest(*body).
        Execute()
    if err != nil {
        panic(err)
    }

    // 3. Read back the delivered codes once the order is fulfilled.
    codes, _, err := client.DefaultAPI.RevealOrderCodes(auth, order.Order.GetId()).Execute()
    if err != nil {
        panic(err)
    }
    fmt.Println(codes)
}
```

## Idempotency

`PlaceOrder` is the only state-changing call. Set an `Idempotency-Key` header so a retried request never creates a duplicate order — the API returns the original order for a repeated key.

## Operations

| Method | Description |
| --- | --- |
| `DefaultAPI.ListCatalog` | List sellable products (cursor-paginated). |
| `DefaultAPI.GetProduct` | Fetch a single product by id. |
| `DefaultAPI.PlaceOrder` | Buy one or more products. |
| `DefaultAPI.GetOrder` | Retrieve an order by id. |
| `DefaultAPI.ListOrders` | List your orders (cursor-paginated). |
| `DefaultAPI.RevealOrderCodes` | Reveal the delivered codes for a fulfilled order. |
| `DefaultAPI.RegisterWebhook` | Subscribe an endpoint to events. |
| `DefaultAPI.ListWebhooks` | List your webhook endpoints. |
| `DefaultAPI.DeleteWebhook` | Remove a webhook endpoint. |
| `DefaultAPI.Ping` | Health check for your credentials. |

## Pagination

List endpoints use cursor (keyset) pagination. Pass the `nextCursor` returned by a response as the `cursor` of the next call until it is empty.

## Documentation and support

- API reference and guides: <https://developers.sodacards.com>
- Support: <mailto:support@sodacards.com>

## License

Released under the [MIT License](./LICENSE).

---

This SDK is generated from the SODACARDS OpenAPI specification and is regenerated automatically whenever the API changes. Open issues on the [documentation portal](https://developers.sodacards.com) rather than editing generated files directly.
