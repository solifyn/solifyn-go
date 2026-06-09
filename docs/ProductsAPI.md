# \ProductsAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProductsArchive**](ProductsAPI.md#ProductsArchive) | **Delete** /v1/products/{id} | Archive Product
[**ProductsCreate**](ProductsAPI.md#ProductsCreate) | **Post** /v1/products | Create Product
[**ProductsGet**](ProductsAPI.md#ProductsGet) | **Get** /v1/products/{id} | Retrieve Product
[**ProductsList**](ProductsAPI.md#ProductsList) | **Get** /v1/products | List Products
[**ProductsUnarchive**](ProductsAPI.md#ProductsUnarchive) | **Post** /v1/products/{id}/unarchive | Unarchive Product
[**ProductsUpdate**](ProductsAPI.md#ProductsUpdate) | **Patch** /v1/products/{id} | Update Product



## ProductsArchive

> ProductsArchive200Response ProductsArchive(ctx, id).Execute()

Archive Product



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
	id := "prod_123" // string | The unique product ID to archive.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductsAPI.ProductsArchive(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductsAPI.ProductsArchive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductsArchive`: ProductsArchive200Response
	fmt.Fprintf(os.Stdout, "Response from `ProductsAPI.ProductsArchive`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique product ID to archive. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductsArchiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductsArchive200Response**](ProductsArchive200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductsCreate

> Product ProductsCreate(ctx).ProductCreate(productCreate).Execute()

Create Product



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
	productCreate := *openapiclient.NewProductCreate("Enterprise SaaS Plan", float32(99), "USD", "saas") // ProductCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductsAPI.ProductsCreate(context.Background()).ProductCreate(productCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductsAPI.ProductsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductsCreate`: Product
	fmt.Fprintf(os.Stdout, "Response from `ProductsAPI.ProductsCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productCreate** | [**ProductCreate**](ProductCreate.md) |  | 

### Return type

[**Product**](Product.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductsGet

> Product ProductsGet(ctx, id).Execute()

Retrieve Product



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
	id := "prod_123" // string | The unique product ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductsAPI.ProductsGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductsAPI.ProductsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductsGet`: Product
	fmt.Fprintf(os.Stdout, "Response from `ProductsAPI.ProductsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique product ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Product**](Product.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductsList

> ProductsList200Response ProductsList(ctx).PricingType(pricingType).Sorting(sorting).Limit(limit).Page(page).IsRecurring(isRecurring).IsArchived(isArchived).Query(query).Id(id).Execute()

List Products



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
	pricingType := "pricingType_example" // string | Filter by pricing type. (optional)
	sorting := "sorting_example" // string | Sorting criterion. Add a minus sign - before the criteria name to sort by descending order. (optional)
	limit := float32(8.14) // float32 | Size of a page, defaults to 10. Maximum is 100. (optional) (default to 10)
	page := float32(8.14) // float32 | Page number, defaults to 1. (optional) (default to 1)
	isRecurring := true // bool | Filter on recurring products (subscriptions). If true, only subscription tiers are returned. If false, only one-time purchase products are returned. (optional)
	isArchived := true // bool | Filter by archived status. (optional)
	query := "query_example" // string | Filter by product name (fuzzy, case-insensitive). (optional)
	id := "id_example" // string | Filter by product ID. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductsAPI.ProductsList(context.Background()).PricingType(pricingType).Sorting(sorting).Limit(limit).Page(page).IsRecurring(isRecurring).IsArchived(isArchived).Query(query).Id(id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductsAPI.ProductsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductsList`: ProductsList200Response
	fmt.Fprintf(os.Stdout, "Response from `ProductsAPI.ProductsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProductsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pricingType** | **string** | Filter by pricing type. | 
 **sorting** | **string** | Sorting criterion. Add a minus sign - before the criteria name to sort by descending order. | 
 **limit** | **float32** | Size of a page, defaults to 10. Maximum is 100. | [default to 10]
 **page** | **float32** | Page number, defaults to 1. | [default to 1]
 **isRecurring** | **bool** | Filter on recurring products (subscriptions). If true, only subscription tiers are returned. If false, only one-time purchase products are returned. | 
 **isArchived** | **bool** | Filter by archived status. | 
 **query** | **string** | Filter by product name (fuzzy, case-insensitive). | 
 **id** | **string** | Filter by product ID. | 

### Return type

[**ProductsList200Response**](ProductsList200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductsUnarchive

> ProductsUnarchive200Response ProductsUnarchive(ctx, id).Execute()

Unarchive Product



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
	id := "prod_123" // string | The unique product ID to unarchive.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductsAPI.ProductsUnarchive(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductsAPI.ProductsUnarchive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductsUnarchive`: ProductsUnarchive200Response
	fmt.Fprintf(os.Stdout, "Response from `ProductsAPI.ProductsUnarchive`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique product ID to unarchive. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductsUnarchiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductsUnarchive200Response**](ProductsUnarchive200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductsUpdate

> ProductMessageResponseDto ProductsUpdate(ctx, id).ProductUpdate(productUpdate).Execute()

Update Product



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
	id := "prod_123" // string | The unique product ID.
	productUpdate := *openapiclient.NewProductUpdate() // ProductUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductsAPI.ProductsUpdate(context.Background(), id).ProductUpdate(productUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductsAPI.ProductsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductsUpdate`: ProductMessageResponseDto
	fmt.Fprintf(os.Stdout, "Response from `ProductsAPI.ProductsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique product ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **productUpdate** | [**ProductUpdate**](ProductUpdate.md) |  | 

### Return type

[**ProductMessageResponseDto**](ProductMessageResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

