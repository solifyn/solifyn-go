# \CheckoutLinksAPI

All URIs are relative to *http://localhost:8000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CheckoutLinksCreate**](CheckoutLinksAPI.md#CheckoutLinksCreate) | **Post** /v1/checkout-links | Create Checkout Link
[**CheckoutLinksDelete**](CheckoutLinksAPI.md#CheckoutLinksDelete) | **Delete** /v1/checkout-links/{id} | Delete Checkout Link
[**CheckoutLinksGet**](CheckoutLinksAPI.md#CheckoutLinksGet) | **Get** /v1/checkout-links/{id} | Retrieve Checkout Link Details
[**CheckoutLinksList**](CheckoutLinksAPI.md#CheckoutLinksList) | **Get** /v1/checkout-links | List Checkout Links
[**CheckoutLinksUpdate**](CheckoutLinksAPI.md#CheckoutLinksUpdate) | **Patch** /v1/checkout-links/{id} | Update Checkout Link



## CheckoutLinksCreate

> CheckoutLinkResponseDto CheckoutLinksCreate(ctx).CreateCheckoutLinkDto(createCheckoutLinkDto).Execute()

Create Checkout Link



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
	createCheckoutLinkDto := *openapiclient.NewCreateCheckoutLinkDto("prod_123") // CreateCheckoutLinkDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CheckoutLinksAPI.CheckoutLinksCreate(context.Background()).CreateCheckoutLinkDto(createCheckoutLinkDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CheckoutLinksAPI.CheckoutLinksCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckoutLinksCreate`: CheckoutLinkResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CheckoutLinksAPI.CheckoutLinksCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCheckoutLinksCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCheckoutLinkDto** | [**CreateCheckoutLinkDto**](CreateCheckoutLinkDto.md) |  | 

### Return type

[**CheckoutLinkResponseDto**](CheckoutLinkResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckoutLinksDelete

> CheckoutLinkMessageResponseDto CheckoutLinksDelete(ctx, id).Execute()

Delete Checkout Link



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
	id := "chk_123" // string | Checkout Link ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CheckoutLinksAPI.CheckoutLinksDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CheckoutLinksAPI.CheckoutLinksDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckoutLinksDelete`: CheckoutLinkMessageResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CheckoutLinksAPI.CheckoutLinksDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Checkout Link ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCheckoutLinksDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CheckoutLinkMessageResponseDto**](CheckoutLinkMessageResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckoutLinksGet

> CheckoutLinkResponseDto CheckoutLinksGet(ctx, id).Execute()

Retrieve Checkout Link Details



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
	id := "chk_123" // string | Checkout Link ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CheckoutLinksAPI.CheckoutLinksGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CheckoutLinksAPI.CheckoutLinksGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckoutLinksGet`: CheckoutLinkResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CheckoutLinksAPI.CheckoutLinksGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Checkout Link ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCheckoutLinksGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CheckoutLinkResponseDto**](CheckoutLinkResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckoutLinksList

> []CheckoutLinkResponseDto CheckoutLinksList(ctx).Execute()

List Checkout Links



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
	resp, r, err := apiClient.CheckoutLinksAPI.CheckoutLinksList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CheckoutLinksAPI.CheckoutLinksList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckoutLinksList`: []CheckoutLinkResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CheckoutLinksAPI.CheckoutLinksList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCheckoutLinksListRequest struct via the builder pattern


### Return type

[**[]CheckoutLinkResponseDto**](CheckoutLinkResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckoutLinksUpdate

> CheckoutLinkMessageResponseDto CheckoutLinksUpdate(ctx, id).UpdateCheckoutLinkDto(updateCheckoutLinkDto).Execute()

Update Checkout Link



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
	id := "chk_123" // string | Checkout Link ID
	updateCheckoutLinkDto := *openapiclient.NewUpdateCheckoutLinkDto() // UpdateCheckoutLinkDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CheckoutLinksAPI.CheckoutLinksUpdate(context.Background(), id).UpdateCheckoutLinkDto(updateCheckoutLinkDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CheckoutLinksAPI.CheckoutLinksUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckoutLinksUpdate`: CheckoutLinkMessageResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CheckoutLinksAPI.CheckoutLinksUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Checkout Link ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCheckoutLinksUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCheckoutLinkDto** | [**UpdateCheckoutLinkDto**](UpdateCheckoutLinkDto.md) |  | 

### Return type

[**CheckoutLinkMessageResponseDto**](CheckoutLinkMessageResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

