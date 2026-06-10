# \DeveloperAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeveloperCreateApiKey**](DeveloperAPI.md#DeveloperCreateApiKey) | **Post** /v1/developer/api-keys | Create Developer API Key
[**DeveloperCreateWebhook**](DeveloperAPI.md#DeveloperCreateWebhook) | **Post** /v1/developer/webhooks | Create Webhook Endpoint
[**DeveloperDeleteWebhook**](DeveloperAPI.md#DeveloperDeleteWebhook) | **Delete** /v1/developer/webhooks/{id} | Delete Webhook Endpoint
[**DeveloperGetAppPortal**](DeveloperAPI.md#DeveloperGetAppPortal) | **Get** /v1/developer/webhooks/app-portal | Retrieve Hosted Webhooks Portal URL
[**DeveloperGetWebhook**](DeveloperAPI.md#DeveloperGetWebhook) | **Get** /v1/developer/webhooks/{id} | Retrieve Webhook Endpoint Details
[**DeveloperListApiKeys**](DeveloperAPI.md#DeveloperListApiKeys) | **Get** /v1/developer/api-keys | List Developer API Keys
[**DeveloperListWebhookDeliveries**](DeveloperAPI.md#DeveloperListWebhookDeliveries) | **Get** /v1/developer/webhooks/{id}/deliveries | Retrieve Webhook Delivery Logs
[**DeveloperListWebhooks**](DeveloperAPI.md#DeveloperListWebhooks) | **Get** /v1/developer/webhooks | List Webhook Endpoints
[**DeveloperRevokeApiKey**](DeveloperAPI.md#DeveloperRevokeApiKey) | **Delete** /v1/developer/api-keys/{id} | Revoke API Key
[**DeveloperUpdateWebhook**](DeveloperAPI.md#DeveloperUpdateWebhook) | **Patch** /v1/developer/webhooks/{id} | Update Webhook Endpoint



## DeveloperCreateApiKey

> ApiKeyResponseDto DeveloperCreateApiKey(ctx).CreateApiKeyDto(createApiKeyDto).Execute()

Create Developer API Key

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/solifyn/solifyn-go"
)

func main() {
	createApiKeyDto := *openapiclient.NewCreateApiKeyDto("Production Key") // CreateApiKeyDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeveloperAPI.DeveloperCreateApiKey(context.Background()).CreateApiKeyDto(createApiKeyDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeveloperAPI.DeveloperCreateApiKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeveloperCreateApiKey`: ApiKeyResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DeveloperAPI.DeveloperCreateApiKey`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeveloperCreateApiKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createApiKeyDto** | [**CreateApiKeyDto**](CreateApiKeyDto.md) |  | 

### Return type

[**ApiKeyResponseDto**](ApiKeyResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeveloperCreateWebhook

> WebhookEndpointResponseDto DeveloperCreateWebhook(ctx).CreateWebhookEndpointDto(createWebhookEndpointDto).Execute()

Create Webhook Endpoint

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/solifyn/solifyn-go"
)

func main() {
	createWebhookEndpointDto := *openapiclient.NewCreateWebhookEndpointDto("https://api.example.com/webhooks", []string{"Events_example"}) // CreateWebhookEndpointDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeveloperAPI.DeveloperCreateWebhook(context.Background()).CreateWebhookEndpointDto(createWebhookEndpointDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeveloperAPI.DeveloperCreateWebhook``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeveloperCreateWebhook`: WebhookEndpointResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DeveloperAPI.DeveloperCreateWebhook`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeveloperCreateWebhookRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createWebhookEndpointDto** | [**CreateWebhookEndpointDto**](CreateWebhookEndpointDto.md) |  | 

### Return type

[**WebhookEndpointResponseDto**](WebhookEndpointResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeveloperDeleteWebhook

> DeveloperDeleteWebhook(ctx, id).Execute()

Delete Webhook Endpoint

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/solifyn/solifyn-go"
)

func main() {
	id := "id_example" // string | The webhook endpoint ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeveloperAPI.DeveloperDeleteWebhook(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeveloperAPI.DeveloperDeleteWebhook``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The webhook endpoint ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeveloperDeleteWebhookRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeveloperGetAppPortal

> AppPortalUrlResponseDto DeveloperGetAppPortal(ctx).Execute()

Retrieve Hosted Webhooks Portal URL

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/solifyn/solifyn-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeveloperAPI.DeveloperGetAppPortal(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeveloperAPI.DeveloperGetAppPortal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeveloperGetAppPortal`: AppPortalUrlResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DeveloperAPI.DeveloperGetAppPortal`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDeveloperGetAppPortalRequest struct via the builder pattern


### Return type

[**AppPortalUrlResponseDto**](AppPortalUrlResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeveloperGetWebhook

> WebhookEndpointResponseDto DeveloperGetWebhook(ctx, id).Execute()

Retrieve Webhook Endpoint Details

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/solifyn/solifyn-go"
)

func main() {
	id := "id_example" // string | The webhook endpoint ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeveloperAPI.DeveloperGetWebhook(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeveloperAPI.DeveloperGetWebhook``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeveloperGetWebhook`: WebhookEndpointResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DeveloperAPI.DeveloperGetWebhook`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The webhook endpoint ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeveloperGetWebhookRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**WebhookEndpointResponseDto**](WebhookEndpointResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeveloperListApiKeys

> []ApiKeyResponseDto DeveloperListApiKeys(ctx).Execute()

List Developer API Keys

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/solifyn/solifyn-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeveloperAPI.DeveloperListApiKeys(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeveloperAPI.DeveloperListApiKeys``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeveloperListApiKeys`: []ApiKeyResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DeveloperAPI.DeveloperListApiKeys`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDeveloperListApiKeysRequest struct via the builder pattern


### Return type

[**[]ApiKeyResponseDto**](ApiKeyResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeveloperListWebhookDeliveries

> []WebhookDeliveryResponseDto DeveloperListWebhookDeliveries(ctx, id).Execute()

Retrieve Webhook Delivery Logs

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/solifyn/solifyn-go"
)

func main() {
	id := "id_example" // string | The webhook endpoint ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeveloperAPI.DeveloperListWebhookDeliveries(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeveloperAPI.DeveloperListWebhookDeliveries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeveloperListWebhookDeliveries`: []WebhookDeliveryResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DeveloperAPI.DeveloperListWebhookDeliveries`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The webhook endpoint ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeveloperListWebhookDeliveriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]WebhookDeliveryResponseDto**](WebhookDeliveryResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeveloperListWebhooks

> []WebhookEndpointResponseDto DeveloperListWebhooks(ctx).Execute()

List Webhook Endpoints

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/solifyn/solifyn-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeveloperAPI.DeveloperListWebhooks(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeveloperAPI.DeveloperListWebhooks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeveloperListWebhooks`: []WebhookEndpointResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DeveloperAPI.DeveloperListWebhooks`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDeveloperListWebhooksRequest struct via the builder pattern


### Return type

[**[]WebhookEndpointResponseDto**](WebhookEndpointResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeveloperRevokeApiKey

> DeveloperRevokeApiKey(ctx, id).Execute()

Revoke API Key

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/solifyn/solifyn-go"
)

func main() {
	id := "id_example" // string | The API key ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeveloperAPI.DeveloperRevokeApiKey(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeveloperAPI.DeveloperRevokeApiKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The API key ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeveloperRevokeApiKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeveloperUpdateWebhook

> WebhookEndpointResponseDto DeveloperUpdateWebhook(ctx, id).UpdateWebhookEndpointDto(updateWebhookEndpointDto).Execute()

Update Webhook Endpoint

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/solifyn/solifyn-go"
)

func main() {
	id := "id_example" // string | The webhook endpoint ID
	updateWebhookEndpointDto := *openapiclient.NewUpdateWebhookEndpointDto() // UpdateWebhookEndpointDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeveloperAPI.DeveloperUpdateWebhook(context.Background(), id).UpdateWebhookEndpointDto(updateWebhookEndpointDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeveloperAPI.DeveloperUpdateWebhook``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeveloperUpdateWebhook`: WebhookEndpointResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DeveloperAPI.DeveloperUpdateWebhook`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The webhook endpoint ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeveloperUpdateWebhookRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateWebhookEndpointDto** | [**UpdateWebhookEndpointDto**](UpdateWebhookEndpointDto.md) |  | 

### Return type

[**WebhookEndpointResponseDto**](WebhookEndpointResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

