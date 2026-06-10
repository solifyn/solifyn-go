# \WebhookEndpointAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OperationalWebhookControllerCreate**](WebhookEndpointAPI.md#OperationalWebhookControllerCreate) | **Post** /v1/operational-webhook/endpoint | Create Operational Webhook Endpoint
[**OperationalWebhookControllerDelete**](WebhookEndpointAPI.md#OperationalWebhookControllerDelete) | **Delete** /v1/operational-webhook/endpoint/{id} | Delete Operational Webhook Endpoint
[**OperationalWebhookControllerGet**](WebhookEndpointAPI.md#OperationalWebhookControllerGet) | **Get** /v1/operational-webhook/endpoint/{id} | Get Operational Webhook Endpoint
[**OperationalWebhookControllerGetHeaders**](WebhookEndpointAPI.md#OperationalWebhookControllerGetHeaders) | **Get** /v1/operational-webhook/endpoint/{id}/headers | Get Operational Webhook Endpoint Headers
[**OperationalWebhookControllerGetSecret**](WebhookEndpointAPI.md#OperationalWebhookControllerGetSecret) | **Get** /v1/operational-webhook/endpoint/{id}/secret | Get Operational Webhook Endpoint Secret
[**OperationalWebhookControllerList**](WebhookEndpointAPI.md#OperationalWebhookControllerList) | **Get** /v1/operational-webhook/endpoint | List Operational Webhook Endpoints
[**OperationalWebhookControllerRotateSecret**](WebhookEndpointAPI.md#OperationalWebhookControllerRotateSecret) | **Post** /v1/operational-webhook/endpoint/{id}/secret/rotate | Rotate Operational Webhook Endpoint Secret
[**OperationalWebhookControllerUpdate**](WebhookEndpointAPI.md#OperationalWebhookControllerUpdate) | **Put** /v1/operational-webhook/endpoint/{id} | Update Operational Webhook Endpoint
[**OperationalWebhookControllerUpdateHeaders**](WebhookEndpointAPI.md#OperationalWebhookControllerUpdateHeaders) | **Put** /v1/operational-webhook/endpoint/{id}/headers | Set Operational Webhook Endpoint Headers



## OperationalWebhookControllerCreate

> OperationalWebhookEndpointResponseDto OperationalWebhookControllerCreate(ctx).OperationalWebhookEndpointInDto(operationalWebhookEndpointInDto).Execute()

Create Operational Webhook Endpoint

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	operationalWebhookEndpointInDto := *openapiclient.NewOperationalWebhookEndpointInDto("https://example.com/webhook/") // OperationalWebhookEndpointInDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhookEndpointAPI.OperationalWebhookControllerCreate(context.Background()).OperationalWebhookEndpointInDto(operationalWebhookEndpointInDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhookEndpointAPI.OperationalWebhookControllerCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperationalWebhookControllerCreate`: OperationalWebhookEndpointResponseDto
	fmt.Fprintf(os.Stdout, "Response from `WebhookEndpointAPI.OperationalWebhookControllerCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperationalWebhookControllerCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **operationalWebhookEndpointInDto** | [**OperationalWebhookEndpointInDto**](OperationalWebhookEndpointInDto.md) |  | 

### Return type

[**OperationalWebhookEndpointResponseDto**](OperationalWebhookEndpointResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperationalWebhookControllerDelete

> OperationalWebhookControllerDelete(ctx, id).Execute()

Delete Operational Webhook Endpoint

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | The endpoint ID or UID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.WebhookEndpointAPI.OperationalWebhookControllerDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhookEndpointAPI.OperationalWebhookControllerDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The endpoint ID or UID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperationalWebhookControllerDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperationalWebhookControllerGet

> OperationalWebhookEndpointResponseDto OperationalWebhookControllerGet(ctx, id).Execute()

Get Operational Webhook Endpoint

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | The endpoint ID or UID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhookEndpointAPI.OperationalWebhookControllerGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhookEndpointAPI.OperationalWebhookControllerGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperationalWebhookControllerGet`: OperationalWebhookEndpointResponseDto
	fmt.Fprintf(os.Stdout, "Response from `WebhookEndpointAPI.OperationalWebhookControllerGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The endpoint ID or UID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperationalWebhookControllerGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperationalWebhookEndpointResponseDto**](OperationalWebhookEndpointResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperationalWebhookControllerGetHeaders

> OperationalWebhookEndpointHeadersResponseDto OperationalWebhookControllerGetHeaders(ctx, id).Execute()

Get Operational Webhook Endpoint Headers

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | The endpoint ID or UID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhookEndpointAPI.OperationalWebhookControllerGetHeaders(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhookEndpointAPI.OperationalWebhookControllerGetHeaders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperationalWebhookControllerGetHeaders`: OperationalWebhookEndpointHeadersResponseDto
	fmt.Fprintf(os.Stdout, "Response from `WebhookEndpointAPI.OperationalWebhookControllerGetHeaders`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The endpoint ID or UID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperationalWebhookControllerGetHeadersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperationalWebhookEndpointHeadersResponseDto**](OperationalWebhookEndpointHeadersResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperationalWebhookControllerGetSecret

> OperationalWebhookEndpointSecretResponseDto OperationalWebhookControllerGetSecret(ctx, id).Execute()

Get Operational Webhook Endpoint Secret

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | The endpoint ID or UID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhookEndpointAPI.OperationalWebhookControllerGetSecret(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhookEndpointAPI.OperationalWebhookControllerGetSecret``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperationalWebhookControllerGetSecret`: OperationalWebhookEndpointSecretResponseDto
	fmt.Fprintf(os.Stdout, "Response from `WebhookEndpointAPI.OperationalWebhookControllerGetSecret`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The endpoint ID or UID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperationalWebhookControllerGetSecretRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperationalWebhookEndpointSecretResponseDto**](OperationalWebhookEndpointSecretResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperationalWebhookControllerList

> OperationalWebhookEndpointListResponseDto OperationalWebhookControllerList(ctx).Execute()

List Operational Webhook Endpoints

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhookEndpointAPI.OperationalWebhookControllerList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhookEndpointAPI.OperationalWebhookControllerList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperationalWebhookControllerList`: OperationalWebhookEndpointListResponseDto
	fmt.Fprintf(os.Stdout, "Response from `WebhookEndpointAPI.OperationalWebhookControllerList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperationalWebhookControllerListRequest struct via the builder pattern


### Return type

[**OperationalWebhookEndpointListResponseDto**](OperationalWebhookEndpointListResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperationalWebhookControllerRotateSecret

> OperationalWebhookControllerRotateSecret(ctx, id).OperationalWebhookEndpointSecretInDto(operationalWebhookEndpointSecretInDto).Execute()

Rotate Operational Webhook Endpoint Secret

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | The endpoint ID or UID
	operationalWebhookEndpointSecretInDto := *openapiclient.NewOperationalWebhookEndpointSecretInDto() // OperationalWebhookEndpointSecretInDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.WebhookEndpointAPI.OperationalWebhookControllerRotateSecret(context.Background(), id).OperationalWebhookEndpointSecretInDto(operationalWebhookEndpointSecretInDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhookEndpointAPI.OperationalWebhookControllerRotateSecret``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The endpoint ID or UID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperationalWebhookControllerRotateSecretRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **operationalWebhookEndpointSecretInDto** | [**OperationalWebhookEndpointSecretInDto**](OperationalWebhookEndpointSecretInDto.md) |  | 

### Return type

 (empty response body)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperationalWebhookControllerUpdate

> OperationalWebhookEndpointResponseDto OperationalWebhookControllerUpdate(ctx, id).OperationalWebhookEndpointUpdateDto(operationalWebhookEndpointUpdateDto).Execute()

Update Operational Webhook Endpoint

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | The endpoint ID or UID
	operationalWebhookEndpointUpdateDto := *openapiclient.NewOperationalWebhookEndpointUpdateDto("https://example.com/new-webhook/") // OperationalWebhookEndpointUpdateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhookEndpointAPI.OperationalWebhookControllerUpdate(context.Background(), id).OperationalWebhookEndpointUpdateDto(operationalWebhookEndpointUpdateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhookEndpointAPI.OperationalWebhookControllerUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperationalWebhookControllerUpdate`: OperationalWebhookEndpointResponseDto
	fmt.Fprintf(os.Stdout, "Response from `WebhookEndpointAPI.OperationalWebhookControllerUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The endpoint ID or UID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperationalWebhookControllerUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **operationalWebhookEndpointUpdateDto** | [**OperationalWebhookEndpointUpdateDto**](OperationalWebhookEndpointUpdateDto.md) |  | 

### Return type

[**OperationalWebhookEndpointResponseDto**](OperationalWebhookEndpointResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperationalWebhookControllerUpdateHeaders

> OperationalWebhookControllerUpdateHeaders(ctx, id).OperationalWebhookEndpointHeadersInDto(operationalWebhookEndpointHeadersInDto).Execute()

Set Operational Webhook Endpoint Headers

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | The endpoint ID or UID
	operationalWebhookEndpointHeadersInDto := *openapiclient.NewOperationalWebhookEndpointHeadersInDto(map[string]interface{}({"X-Example":"123","X-Foobar":"Bar"})) // OperationalWebhookEndpointHeadersInDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.WebhookEndpointAPI.OperationalWebhookControllerUpdateHeaders(context.Background(), id).OperationalWebhookEndpointHeadersInDto(operationalWebhookEndpointHeadersInDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhookEndpointAPI.OperationalWebhookControllerUpdateHeaders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The endpoint ID or UID | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperationalWebhookControllerUpdateHeadersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **operationalWebhookEndpointHeadersInDto** | [**OperationalWebhookEndpointHeadersInDto**](OperationalWebhookEndpointHeadersInDto.md) |  | 

### Return type

 (empty response body)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

