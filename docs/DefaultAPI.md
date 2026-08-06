# \DefaultAPI

All URIs are relative to *https://api.sodacards.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteWebhook**](DefaultAPI.md#DeleteWebhook) | **Delete** /v1/webhooks/{id} | Delete a webhook endpoint
[**GetBalance**](DefaultAPI.md#GetBalance) | **Get** /v1/balance | Get wallet balance
[**GetOrder**](DefaultAPI.md#GetOrder) | **Get** /v1/orders/{id} | Get an order
[**GetProduct**](DefaultAPI.md#GetProduct) | **Get** /v1/products/{id} | Get a product
[**ListCatalog**](DefaultAPI.md#ListCatalog) | **Get** /v1/catalog | List catalog products
[**ListOrders**](DefaultAPI.md#ListOrders) | **Get** /v1/orders | List orders
[**ListWebhooks**](DefaultAPI.md#ListWebhooks) | **Get** /v1/webhooks | List webhook endpoints
[**Ping**](DefaultAPI.md#Ping) | **Get** /v1/ping | Ping
[**PlaceOrder**](DefaultAPI.md#PlaceOrder) | **Post** /v1/orders | Place an order
[**RegisterWebhook**](DefaultAPI.md#RegisterWebhook) | **Post** /v1/webhooks | Register a webhook endpoint
[**RevealOrderCodes**](DefaultAPI.md#RevealOrderCodes) | **Get** /v1/orders/{order_id}/codes | Reveal order codes
[**RotateWebhookSecret**](DefaultAPI.md#RotateWebhookSecret) | **Post** /v1/webhooks/{id}/rotate | Rotate a webhook signing secret



## DeleteWebhook

> map[string]interface{} DeleteWebhook(ctx, id).Execute()

Delete a webhook endpoint



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SODACARDS/sodacards-go"
)

func main() {
	id := "id_example" // string | id is the webhook endpoint to remove.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.DeleteWebhook(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.DeleteWebhook``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteWebhook`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.DeleteWebhook`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id is the webhook endpoint to remove. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteWebhookRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**map[string]interface{}**

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBalance

> SodacardsDevpublicV1GetBalanceResponse GetBalance(ctx).Execute()

Get wallet balance



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SODACARDS/sodacards-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetBalance(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetBalance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBalance`: SodacardsDevpublicV1GetBalanceResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetBalance`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetBalanceRequest struct via the builder pattern


### Return type

[**SodacardsDevpublicV1GetBalanceResponse**](SodacardsDevpublicV1GetBalanceResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrder

> SodacardsDevpublicV1GetOrderResponse GetOrder(ctx, id).Execute()

Get an order



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SODACARDS/sodacards-go"
)

func main() {
	id := "id_example" // string | id is the order id, from PlaceOrder.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetOrder(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrder`: SodacardsDevpublicV1GetOrderResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id is the order id, from PlaceOrder. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SodacardsDevpublicV1GetOrderResponse**](SodacardsDevpublicV1GetOrderResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProduct

> SodacardsDevpublicV1GetProductResponse GetProduct(ctx, id).Execute()

Get a product



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SODACARDS/sodacards-go"
)

func main() {
	id := "id_example" // string | id is the product id, taken from a catalog entry.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetProduct(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetProduct``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProduct`: SodacardsDevpublicV1GetProductResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetProduct`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id is the product id, taken from a catalog entry. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProductRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SodacardsDevpublicV1GetProductResponse**](SodacardsDevpublicV1GetProductResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCatalog

> SodacardsDevpublicV1ListCatalogResponse ListCatalog(ctx).Limit(limit).Cursor(cursor).Execute()

List catalog products



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SODACARDS/sodacards-go"
)

func main() {
	limit := int32(56) // int32 | limit is the maximum number of products to return (1..100). Zero applies the  default page size. (optional)
	cursor := "cursor_example" // string | cursor is the next_cursor of the previous page. Empty for the first page. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListCatalog(context.Background()).Limit(limit).Cursor(cursor).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListCatalog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCatalog`: SodacardsDevpublicV1ListCatalogResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListCatalog`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCatalogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | limit is the maximum number of products to return (1..100). Zero applies the  default page size. | 
 **cursor** | **string** | cursor is the next_cursor of the previous page. Empty for the first page. | 

### Return type

[**SodacardsDevpublicV1ListCatalogResponse**](SodacardsDevpublicV1ListCatalogResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListOrders

> SodacardsDevpublicV1ListOrdersResponse ListOrders(ctx).Limit(limit).Cursor(cursor).Reference(reference).Execute()

List orders



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SODACARDS/sodacards-go"
)

func main() {
	limit := int32(56) // int32 | limit is the maximum number of orders to return (1..100). Zero applies the  default page size. (optional)
	cursor := "cursor_example" // string | cursor is the next_cursor of the previous page. Empty for the first page. (optional)
	reference := "reference_example" // string | reference, when set, filters the list to the orders carrying that client  reference. The cursor is ignored when a reference is given. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListOrders(context.Background()).Limit(limit).Cursor(cursor).Reference(reference).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListOrders`: SodacardsDevpublicV1ListOrdersResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListOrders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | limit is the maximum number of orders to return (1..100). Zero applies the  default page size. | 
 **cursor** | **string** | cursor is the next_cursor of the previous page. Empty for the first page. | 
 **reference** | **string** | reference, when set, filters the list to the orders carrying that client  reference. The cursor is ignored when a reference is given. | 

### Return type

[**SodacardsDevpublicV1ListOrdersResponse**](SodacardsDevpublicV1ListOrdersResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWebhooks

> SodacardsDevpublicV1ListWebhooksResponse ListWebhooks(ctx).Execute()

List webhook endpoints



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SODACARDS/sodacards-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ListWebhooks(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ListWebhooks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWebhooks`: SodacardsDevpublicV1ListWebhooksResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ListWebhooks`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListWebhooksRequest struct via the builder pattern


### Return type

[**SodacardsDevpublicV1ListWebhooksResponse**](SodacardsDevpublicV1ListWebhooksResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Ping

> SodacardsDevpublicV1PingResponse Ping(ctx).Execute()

Ping



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SODACARDS/sodacards-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.Ping(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.Ping``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Ping`: SodacardsDevpublicV1PingResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.Ping`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiPingRequest struct via the builder pattern


### Return type

[**SodacardsDevpublicV1PingResponse**](SodacardsDevpublicV1PingResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PlaceOrder

> SodacardsDevpublicV1PlaceOrderResponse PlaceOrder(ctx).IdempotencyKey(idempotencyKey).SodacardsDevpublicV1PlaceOrderRequest(sodacardsDevpublicV1PlaceOrderRequest).Execute()

Place an order



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SODACARDS/sodacards-go"
)

func main() {
	idempotencyKey := "idempotencyKey_example" // string | A unique key that makes order placement safe to retry: a retried request with the same key never places a second order. Reusing a key with a different body is rejected. Use a UUID you generate per order.
	sodacardsDevpublicV1PlaceOrderRequest := *openapiclient.NewSodacardsDevpublicV1PlaceOrderRequest() // SodacardsDevpublicV1PlaceOrderRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.PlaceOrder(context.Background()).IdempotencyKey(idempotencyKey).SodacardsDevpublicV1PlaceOrderRequest(sodacardsDevpublicV1PlaceOrderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.PlaceOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PlaceOrder`: SodacardsDevpublicV1PlaceOrderResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.PlaceOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPlaceOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **idempotencyKey** | **string** | A unique key that makes order placement safe to retry: a retried request with the same key never places a second order. Reusing a key with a different body is rejected. Use a UUID you generate per order. | 
 **sodacardsDevpublicV1PlaceOrderRequest** | [**SodacardsDevpublicV1PlaceOrderRequest**](SodacardsDevpublicV1PlaceOrderRequest.md) |  | 

### Return type

[**SodacardsDevpublicV1PlaceOrderResponse**](SodacardsDevpublicV1PlaceOrderResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegisterWebhook

> SodacardsDevpublicV1RegisterWebhookResponse RegisterWebhook(ctx).SodacardsDevpublicV1RegisterWebhookRequest(sodacardsDevpublicV1RegisterWebhookRequest).Execute()

Register a webhook endpoint



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SODACARDS/sodacards-go"
)

func main() {
	sodacardsDevpublicV1RegisterWebhookRequest := *openapiclient.NewSodacardsDevpublicV1RegisterWebhookRequest() // SodacardsDevpublicV1RegisterWebhookRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RegisterWebhook(context.Background()).SodacardsDevpublicV1RegisterWebhookRequest(sodacardsDevpublicV1RegisterWebhookRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RegisterWebhook``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegisterWebhook`: SodacardsDevpublicV1RegisterWebhookResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RegisterWebhook`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegisterWebhookRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sodacardsDevpublicV1RegisterWebhookRequest** | [**SodacardsDevpublicV1RegisterWebhookRequest**](SodacardsDevpublicV1RegisterWebhookRequest.md) |  | 

### Return type

[**SodacardsDevpublicV1RegisterWebhookResponse**](SodacardsDevpublicV1RegisterWebhookResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevealOrderCodes

> SodacardsDevpublicV1RevealOrderCodesResponse RevealOrderCodes(ctx, orderId).Execute()

Reveal order codes



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SODACARDS/sodacards-go"
)

func main() {
	orderId := "orderId_example" // string | order_id is the order whose codes to reveal.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RevealOrderCodes(context.Background(), orderId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RevealOrderCodes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevealOrderCodes`: SodacardsDevpublicV1RevealOrderCodesResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RevealOrderCodes`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderId** | **string** | order_id is the order whose codes to reveal. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevealOrderCodesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SodacardsDevpublicV1RevealOrderCodesResponse**](SodacardsDevpublicV1RevealOrderCodesResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RotateWebhookSecret

> SodacardsDevpublicV1RotateWebhookSecretResponse RotateWebhookSecret(ctx, id).Execute()

Rotate a webhook signing secret



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/SODACARDS/sodacards-go"
)

func main() {
	id := "id_example" // string | id is the webhook endpoint whose signing secret to rotate.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.RotateWebhookSecret(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.RotateWebhookSecret``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RotateWebhookSecret`: SodacardsDevpublicV1RotateWebhookSecretResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.RotateWebhookSecret`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id is the webhook endpoint whose signing secret to rotate. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRotateWebhookSecretRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SodacardsDevpublicV1RotateWebhookSecretResponse**](SodacardsDevpublicV1RotateWebhookSecretResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

