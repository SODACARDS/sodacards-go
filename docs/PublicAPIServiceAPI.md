# \PublicAPIServiceAPI

All URIs are relative to *https://api.sodacards.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PublicAPIServiceGetBalance**](PublicAPIServiceAPI.md#PublicAPIServiceGetBalance) | **Get** /v1/balance | GetBalance
[**PublicAPIServiceRotateWebhookSecret**](PublicAPIServiceAPI.md#PublicAPIServiceRotateWebhookSecret) | **Post** /v1/webhooks/{id}/rotate | RotateWebhookSecret



## PublicAPIServiceGetBalance

> SodacardsDevpublicV1GetBalanceResponse PublicAPIServiceGetBalance(ctx).Execute()

GetBalance



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
	resp, r, err := apiClient.PublicAPIServiceAPI.PublicAPIServiceGetBalance(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicAPIServiceAPI.PublicAPIServiceGetBalance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PublicAPIServiceGetBalance`: SodacardsDevpublicV1GetBalanceResponse
	fmt.Fprintf(os.Stdout, "Response from `PublicAPIServiceAPI.PublicAPIServiceGetBalance`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiPublicAPIServiceGetBalanceRequest struct via the builder pattern


### Return type

[**SodacardsDevpublicV1GetBalanceResponse**](SodacardsDevpublicV1GetBalanceResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PublicAPIServiceRotateWebhookSecret

> SodacardsDevpublicV1RotateWebhookSecretResponse PublicAPIServiceRotateWebhookSecret(ctx, id).Execute()

RotateWebhookSecret



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
	resp, r, err := apiClient.PublicAPIServiceAPI.PublicAPIServiceRotateWebhookSecret(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicAPIServiceAPI.PublicAPIServiceRotateWebhookSecret``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PublicAPIServiceRotateWebhookSecret`: SodacardsDevpublicV1RotateWebhookSecretResponse
	fmt.Fprintf(os.Stdout, "Response from `PublicAPIServiceAPI.PublicAPIServiceRotateWebhookSecret`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id is the webhook endpoint whose signing secret to rotate. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPublicAPIServiceRotateWebhookSecretRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SodacardsDevpublicV1RotateWebhookSecretResponse**](SodacardsDevpublicV1RotateWebhookSecretResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

