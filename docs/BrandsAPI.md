# \BrandsAPI

All URIs are relative to *http://localhost:8000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BrandsCreate**](BrandsAPI.md#BrandsCreate) | **Post** /v1/user/brand | Create Brand
[**BrandsGet**](BrandsAPI.md#BrandsGet) | **Get** /v1/user/brand/{id} | Retrieve Brand
[**BrandsList**](BrandsAPI.md#BrandsList) | **Get** /v1/user/brands | List Brands
[**BrandsUpdate**](BrandsAPI.md#BrandsUpdate) | **Patch** /v1/user/brand/{id} | Update Brand



## BrandsCreate

> Brand BrandsCreate(ctx).BrandCreate(brandCreate).Execute()

Create Brand



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
	brandCreate := *openapiclient.NewBrandCreate("Acme Corp") // BrandCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.BrandsCreate(context.Background()).BrandCreate(brandCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.BrandsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BrandsCreate`: Brand
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.BrandsCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBrandsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **brandCreate** | [**BrandCreate**](BrandCreate.md) |  | 

### Return type

[**Brand**](Brand.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BrandsGet

> Brand BrandsGet(ctx, id).Execute()

Retrieve Brand



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
	id := "brd_123" // string | The brand ID to retrieve

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.BrandsGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.BrandsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BrandsGet`: Brand
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.BrandsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The brand ID to retrieve | 

### Other Parameters

Other parameters are passed through a pointer to a apiBrandsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Brand**](Brand.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BrandsList

> []Brand BrandsList(ctx).Execute()

List Brands



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
	resp, r, err := apiClient.BrandsAPI.BrandsList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.BrandsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BrandsList`: []Brand
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.BrandsList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiBrandsListRequest struct via the builder pattern


### Return type

[**[]Brand**](Brand.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BrandsUpdate

> Brand BrandsUpdate(ctx, id).BrandUpdate(brandUpdate).Execute()

Update Brand



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
	id := "brd_123" // string | The brand ID to update
	brandUpdate := *openapiclient.NewBrandUpdate() // BrandUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandsAPI.BrandsUpdate(context.Background(), id).BrandUpdate(brandUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandsAPI.BrandsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BrandsUpdate`: Brand
	fmt.Fprintf(os.Stdout, "Response from `BrandsAPI.BrandsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The brand ID to update | 

### Other Parameters

Other parameters are passed through a pointer to a apiBrandsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **brandUpdate** | [**BrandUpdate**](BrandUpdate.md) |  | 

### Return type

[**Brand**](Brand.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

