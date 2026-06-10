# \ProductAddOnsAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProductsCreateAddon**](ProductAddOnsAPI.md#ProductsCreateAddon) | **Post** /v1/products/{id}/addons | Create Product Add-on
[**ProductsDeleteAddon**](ProductAddOnsAPI.md#ProductsDeleteAddon) | **Delete** /v1/products/{id}/addons/{addonId} | Delete Product Add-on
[**ProductsGetAddon**](ProductAddOnsAPI.md#ProductsGetAddon) | **Get** /v1/products/{id}/addons/{addonId} | Retrieve Product Add-on
[**ProductsListAddons**](ProductAddOnsAPI.md#ProductsListAddons) | **Get** /v1/products/{id}/addons | List Product Add-ons
[**ProductsListAllAddons**](ProductAddOnsAPI.md#ProductsListAllAddons) | **Get** /v1/products/all-addons/list | List All Add-ons
[**ProductsUpdateAddon**](ProductAddOnsAPI.md#ProductsUpdateAddon) | **Patch** /v1/products/{id}/addons/{addonId} | Update Product Add-on



## ProductsCreateAddon

> Addon ProductsCreateAddon(ctx, id).AddonCreate(addonCreate).Execute()

Create Product Add-on



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
	id := "prod_parent_123" // string | The parent product ID.
	addonCreate := *openapiclient.NewAddonCreate("prod_addon_123", float32(0), true) // AddonCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductAddOnsAPI.ProductsCreateAddon(context.Background(), id).AddonCreate(addonCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAddOnsAPI.ProductsCreateAddon``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductsCreateAddon`: Addon
	fmt.Fprintf(os.Stdout, "Response from `ProductAddOnsAPI.ProductsCreateAddon`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The parent product ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductsCreateAddonRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **addonCreate** | [**AddonCreate**](AddonCreate.md) |  | 

### Return type

[**Addon**](Addon.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductsDeleteAddon

> ProductMessageResponseDto ProductsDeleteAddon(ctx, id, addonId).Execute()

Delete Product Add-on



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
	id := "prod_parent_123" // string | The parent product ID.
	addonId := "prod_addon_123" // string | The add-on product ID to remove.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductAddOnsAPI.ProductsDeleteAddon(context.Background(), id, addonId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAddOnsAPI.ProductsDeleteAddon``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductsDeleteAddon`: ProductMessageResponseDto
	fmt.Fprintf(os.Stdout, "Response from `ProductAddOnsAPI.ProductsDeleteAddon`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The parent product ID. | 
**addonId** | **string** | The add-on product ID to remove. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductsDeleteAddonRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ProductMessageResponseDto**](ProductMessageResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductsGetAddon

> Addon ProductsGetAddon(ctx, id, addonId).Execute()

Retrieve Product Add-on



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
	id := "prod_parent_123" // string | The parent product ID.
	addonId := "prod_addon_123" // string | The add-on product ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductAddOnsAPI.ProductsGetAddon(context.Background(), id, addonId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAddOnsAPI.ProductsGetAddon``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductsGetAddon`: Addon
	fmt.Fprintf(os.Stdout, "Response from `ProductAddOnsAPI.ProductsGetAddon`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The parent product ID. | 
**addonId** | **string** | The add-on product ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductsGetAddonRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**Addon**](Addon.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductsListAddons

> []Addon ProductsListAddons(ctx, id).Execute()

List Product Add-ons



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
	id := "prod_parent_123" // string | The parent product ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductAddOnsAPI.ProductsListAddons(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAddOnsAPI.ProductsListAddons``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductsListAddons`: []Addon
	fmt.Fprintf(os.Stdout, "Response from `ProductAddOnsAPI.ProductsListAddons`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The parent product ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductsListAddonsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]Addon**](Addon.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProductsListAllAddons

> ProductsListAllAddons(ctx).Execute()

List All Add-ons



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
	r, err := apiClient.ProductAddOnsAPI.ProductsListAllAddons(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAddOnsAPI.ProductsListAllAddons``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiProductsListAllAddonsRequest struct via the builder pattern


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


## ProductsUpdateAddon

> Addon ProductsUpdateAddon(ctx, id, addonId).AddonUpdate(addonUpdate).Execute()

Update Product Add-on



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
	id := "prod_parent_123" // string | The parent product ID.
	addonId := "prod_addon_123" // string | The add-on product ID.
	addonUpdate := *openapiclient.NewAddonUpdate() // AddonUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductAddOnsAPI.ProductsUpdateAddon(context.Background(), id, addonId).AddonUpdate(addonUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAddOnsAPI.ProductsUpdateAddon``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProductsUpdateAddon`: Addon
	fmt.Fprintf(os.Stdout, "Response from `ProductAddOnsAPI.ProductsUpdateAddon`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The parent product ID. | 
**addonId** | **string** | The add-on product ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProductsUpdateAddonRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **addonUpdate** | [**AddonUpdate**](AddonUpdate.md) |  | 

### Return type

[**Addon**](Addon.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

