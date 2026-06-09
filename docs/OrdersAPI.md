# \OrdersAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OrdersGet**](OrdersAPI.md#OrdersGet) | **Get** /v1/orders/{id} | Retrieve Order
[**OrdersGetInvoice**](OrdersAPI.md#OrdersGetInvoice) | **Get** /v1/orders/{id}/invoice | Get Order Invoice
[**OrdersList**](OrdersAPI.md#OrdersList) | **Get** /v1/orders | List Orders
[**OrdersUpdate**](OrdersAPI.md#OrdersUpdate) | **Patch** /v1/orders/{id} | Update Order Billing Address
[**RefundsCreate**](OrdersAPI.md#RefundsCreate) | **Post** /v1/orders/{id}/refund | Create Refund



## OrdersGet

> Order OrdersGet(ctx, id).Execute()

Retrieve Order



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
	id := "pay_123" // string | The unique order/payment ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrdersAPI.OrdersGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrdersAPI.OrdersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrdersGet`: Order
	fmt.Fprintf(os.Stdout, "Response from `OrdersAPI.OrdersGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique order/payment ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrdersGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Order**](Order.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrdersGetInvoice

> Invoice OrdersGetInvoice(ctx, id).Execute()

Get Order Invoice



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
	id := "pay_123" // string | The unique order/payment ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrdersAPI.OrdersGetInvoice(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrdersAPI.OrdersGetInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrdersGetInvoice`: Invoice
	fmt.Fprintf(os.Stdout, "Response from `OrdersAPI.OrdersGetInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique order/payment ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrdersGetInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Invoice**](Invoice.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrdersList

> OrderList OrdersList(ctx).CreatedAtLte(createdAtLte).CreatedAtGte(createdAtGte).ProductId(productId).CustomerId(customerId).Status(status).PageSize(pageSize).PageNumber(pageNumber).Execute()

List Orders



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
	createdAtLte := "createdAtLte_example" // string | Filter by creation date less than or equal to. (optional)
	createdAtGte := "createdAtGte_example" // string | Filter by creation date greater than or equal to. (optional)
	productId := "productId_example" // string | Filter by product identifier. (optional)
	customerId := "customerId_example" // string | Filter by customer identifier. (optional)
	status := "status_example" // string | Filter by order/payment status. (optional)
	pageSize := float32(8.14) // float32 | Size of a page, defaults to 10. Maximum is 100. (optional) (default to 10)
	pageNumber := float32(8.14) // float32 | Page number, defaults to 1. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrdersAPI.OrdersList(context.Background()).CreatedAtLte(createdAtLte).CreatedAtGte(createdAtGte).ProductId(productId).CustomerId(customerId).Status(status).PageSize(pageSize).PageNumber(pageNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrdersAPI.OrdersList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrdersList`: OrderList
	fmt.Fprintf(os.Stdout, "Response from `OrdersAPI.OrdersList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOrdersListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createdAtLte** | **string** | Filter by creation date less than or equal to. | 
 **createdAtGte** | **string** | Filter by creation date greater than or equal to. | 
 **productId** | **string** | Filter by product identifier. | 
 **customerId** | **string** | Filter by customer identifier. | 
 **status** | **string** | Filter by order/payment status. | 
 **pageSize** | **float32** | Size of a page, defaults to 10. Maximum is 100. | [default to 10]
 **pageNumber** | **float32** | Page number, defaults to 1. | [default to 1]

### Return type

[**OrderList**](OrderList.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrdersUpdate

> Order OrdersUpdate(ctx, id).OrderUpdate(orderUpdate).Execute()

Update Order Billing Address



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
	id := "pay_123" // string | The unique order/payment ID.
	orderUpdate := *openapiclient.NewOrderUpdate() // OrderUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrdersAPI.OrdersUpdate(context.Background(), id).OrderUpdate(orderUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrdersAPI.OrdersUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrdersUpdate`: Order
	fmt.Fprintf(os.Stdout, "Response from `OrdersAPI.OrdersUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique order/payment ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiOrdersUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **orderUpdate** | [**OrderUpdate**](OrderUpdate.md) |  | 

### Return type

[**Order**](Order.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RefundsCreate

> RefundsCreate(ctx, id).OrderRefundCreate(orderRefundCreate).Execute()

Create Refund



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
	id := "pay_123" // string | The unique order/payment ID.
	orderRefundCreate := *openapiclient.NewOrderRefundCreate(int32(1000), true, "ref_idem_98sdufhskjfsd") // OrderRefundCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OrdersAPI.RefundsCreate(context.Background(), id).OrderRefundCreate(orderRefundCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrdersAPI.RefundsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique order/payment ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRefundsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **orderRefundCreate** | [**OrderRefundCreate**](OrderRefundCreate.md) |  | 

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

