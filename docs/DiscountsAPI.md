# \DiscountsAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DiscountsCreate**](DiscountsAPI.md#DiscountsCreate) | **Post** /v1/discounts | Create Discount
[**DiscountsDelete**](DiscountsAPI.md#DiscountsDelete) | **Delete** /v1/discounts/{id} | Delete Discount
[**DiscountsGet**](DiscountsAPI.md#DiscountsGet) | **Get** /v1/discounts/{id} | Retrieve Discount
[**DiscountsList**](DiscountsAPI.md#DiscountsList) | **Get** /v1/discounts | List Discounts
[**DiscountsUpdate**](DiscountsAPI.md#DiscountsUpdate) | **Patch** /v1/discounts/{id} | Update Discount
[**DiscountsValidate**](DiscountsAPI.md#DiscountsValidate) | **Get** /v1/discounts/validate | Validate Code



## DiscountsCreate

> Discount DiscountsCreate(ctx).DiscountCreate(discountCreate).Execute()

Create Discount



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
	discountCreate := *openapiclient.NewDiscountCreate("Code_example", "Type_example", float32(123)) // DiscountCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DiscountsAPI.DiscountsCreate(context.Background()).DiscountCreate(discountCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DiscountsAPI.DiscountsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DiscountsCreate`: Discount
	fmt.Fprintf(os.Stdout, "Response from `DiscountsAPI.DiscountsCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDiscountsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **discountCreate** | [**DiscountCreate**](DiscountCreate.md) |  | 

### Return type

[**Discount**](Discount.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DiscountsDelete

> LicensesDeactivate200Response DiscountsDelete(ctx, id).Execute()

Delete Discount



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
	id := "disc_123" // string | The unique discount ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DiscountsAPI.DiscountsDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DiscountsAPI.DiscountsDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DiscountsDelete`: LicensesDeactivate200Response
	fmt.Fprintf(os.Stdout, "Response from `DiscountsAPI.DiscountsDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique discount ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDiscountsDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LicensesDeactivate200Response**](LicensesDeactivate200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DiscountsGet

> Discount DiscountsGet(ctx, id).Execute()

Retrieve Discount



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
	id := "disc_123" // string | The unique discount ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DiscountsAPI.DiscountsGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DiscountsAPI.DiscountsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DiscountsGet`: Discount
	fmt.Fprintf(os.Stdout, "Response from `DiscountsAPI.DiscountsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique discount ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDiscountsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Discount**](Discount.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DiscountsList

> DiscountsList200Response DiscountsList(ctx).Sorting(sorting).Limit(limit).Page(page).Query(query).Id(id).Execute()

List Discounts



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
	sorting := "sorting_example" // string | Sorting criterion. Add a minus sign - before the criteria name to sort by descending order. (optional)
	limit := float32(8.14) // float32 | Size of a page, defaults to 10. Maximum is 100. (optional) (default to 10)
	page := float32(8.14) // float32 | Page number, defaults to 1. (optional) (default to 1)
	query := "query_example" // string | Filter by discount code (fuzzy, case-insensitive). (optional)
	id := "id_example" // string | Filter by discount ID. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DiscountsAPI.DiscountsList(context.Background()).Sorting(sorting).Limit(limit).Page(page).Query(query).Id(id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DiscountsAPI.DiscountsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DiscountsList`: DiscountsList200Response
	fmt.Fprintf(os.Stdout, "Response from `DiscountsAPI.DiscountsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDiscountsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sorting** | **string** | Sorting criterion. Add a minus sign - before the criteria name to sort by descending order. | 
 **limit** | **float32** | Size of a page, defaults to 10. Maximum is 100. | [default to 10]
 **page** | **float32** | Page number, defaults to 1. | [default to 1]
 **query** | **string** | Filter by discount code (fuzzy, case-insensitive). | 
 **id** | **string** | Filter by discount ID. | 

### Return type

[**DiscountsList200Response**](DiscountsList200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DiscountsUpdate

> Discount DiscountsUpdate(ctx, id).DiscountUpdate(discountUpdate).Execute()

Update Discount



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
	id := "disc_123" // string | The unique discount ID.
	discountUpdate := *openapiclient.NewDiscountUpdate() // DiscountUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DiscountsAPI.DiscountsUpdate(context.Background(), id).DiscountUpdate(discountUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DiscountsAPI.DiscountsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DiscountsUpdate`: Discount
	fmt.Fprintf(os.Stdout, "Response from `DiscountsAPI.DiscountsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique discount ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDiscountsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **discountUpdate** | [**DiscountUpdate**](DiscountUpdate.md) |  | 

### Return type

[**Discount**](Discount.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DiscountsValidate

> Discount DiscountsValidate(ctx).Code(code).BusinessId(businessId).Execute()

Validate Code



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
	code := "SAVE20" // string | The plain discount code string
	businessId := "biz_123" // string | The business database ID context

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DiscountsAPI.DiscountsValidate(context.Background()).Code(code).BusinessId(businessId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DiscountsAPI.DiscountsValidate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DiscountsValidate`: Discount
	fmt.Fprintf(os.Stdout, "Response from `DiscountsAPI.DiscountsValidate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDiscountsValidateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **code** | **string** | The plain discount code string | 
 **businessId** | **string** | The business database ID context | 

### Return type

[**Discount**](Discount.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

