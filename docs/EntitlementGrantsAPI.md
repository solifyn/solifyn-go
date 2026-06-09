# \EntitlementGrantsAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EntitlementGrantsGet**](EntitlementGrantsAPI.md#EntitlementGrantsGet) | **Get** /v1/entitlement-grants/{id} | Retrieve Entitlement Grant
[**EntitlementGrantsList**](EntitlementGrantsAPI.md#EntitlementGrantsList) | **Get** /v1/entitlement-grants | List Entitlement Grants
[**EntitlementGrantsRetry**](EntitlementGrantsAPI.md#EntitlementGrantsRetry) | **Post** /v1/entitlement-grants/{id}/retry | Retry Entitlement Grant Delivery
[**EntitlementGrantsRevoke**](EntitlementGrantsAPI.md#EntitlementGrantsRevoke) | **Post** /v1/entitlement-grants/{id}/revoke | Manually Revoke Entitlement Grant



## EntitlementGrantsGet

> EntitlementGrantResponseDto EntitlementGrantsGet(ctx, id).Execute()

Retrieve Entitlement Grant



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
	id := "id_example" // string | The unique grant ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EntitlementGrantsAPI.EntitlementGrantsGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementGrantsAPI.EntitlementGrantsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EntitlementGrantsGet`: EntitlementGrantResponseDto
	fmt.Fprintf(os.Stdout, "Response from `EntitlementGrantsAPI.EntitlementGrantsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique grant ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiEntitlementGrantsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EntitlementGrantResponseDto**](EntitlementGrantResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EntitlementGrantsList

> []EntitlementGrantResponseDto EntitlementGrantsList(ctx).Status(status).Execute()

List Entitlement Grants



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
	status := "status_example" // string | Filter by status (PENDING, DELIVERED, FAILED, REVOKED) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EntitlementGrantsAPI.EntitlementGrantsList(context.Background()).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementGrantsAPI.EntitlementGrantsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EntitlementGrantsList`: []EntitlementGrantResponseDto
	fmt.Fprintf(os.Stdout, "Response from `EntitlementGrantsAPI.EntitlementGrantsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEntitlementGrantsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** | Filter by status (PENDING, DELIVERED, FAILED, REVOKED) | 

### Return type

[**[]EntitlementGrantResponseDto**](EntitlementGrantResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EntitlementGrantsRetry

> EntitlementGrantResponseDto EntitlementGrantsRetry(ctx, id).Execute()

Retry Entitlement Grant Delivery



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
	id := "id_example" // string | The unique grant ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EntitlementGrantsAPI.EntitlementGrantsRetry(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementGrantsAPI.EntitlementGrantsRetry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EntitlementGrantsRetry`: EntitlementGrantResponseDto
	fmt.Fprintf(os.Stdout, "Response from `EntitlementGrantsAPI.EntitlementGrantsRetry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique grant ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiEntitlementGrantsRetryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EntitlementGrantResponseDto**](EntitlementGrantResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EntitlementGrantsRevoke

> EntitlementGrantResponseDto EntitlementGrantsRevoke(ctx, id).Execute()

Manually Revoke Entitlement Grant



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
	id := "id_example" // string | The unique grant ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EntitlementGrantsAPI.EntitlementGrantsRevoke(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementGrantsAPI.EntitlementGrantsRevoke``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EntitlementGrantsRevoke`: EntitlementGrantResponseDto
	fmt.Fprintf(os.Stdout, "Response from `EntitlementGrantsAPI.EntitlementGrantsRevoke`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique grant ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiEntitlementGrantsRevokeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EntitlementGrantResponseDto**](EntitlementGrantResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

