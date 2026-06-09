# \RefundsChargebacksAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RefundsCreate**](RefundsChargebacksAPI.md#RefundsCreate) | **Post** /v1/orders/{id}/refund | Create Refund
[**RefundsGet**](RefundsChargebacksAPI.md#RefundsGet) | **Get** /v1/refunds/{id} | Retrieve Refund details
[**RefundsList**](RefundsChargebacksAPI.md#RefundsList) | **Get** /v1/refunds | List Refunds



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
	r, err := apiClient.RefundsChargebacksAPI.RefundsCreate(context.Background(), id).OrderRefundCreate(orderRefundCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RefundsChargebacksAPI.RefundsCreate``: %v\n", err)
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


## RefundsGet

> Refund RefundsGet(ctx, id).Execute()

Retrieve Refund details



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
	id := "ref_123" // string | Refund ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RefundsChargebacksAPI.RefundsGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RefundsChargebacksAPI.RefundsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RefundsGet`: Refund
	fmt.Fprintf(os.Stdout, "Response from `RefundsChargebacksAPI.RefundsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Refund ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRefundsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Refund**](Refund.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RefundsList

> []Refund RefundsList(ctx).Execute()

List Refunds



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
	resp, r, err := apiClient.RefundsChargebacksAPI.RefundsList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RefundsChargebacksAPI.RefundsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RefundsList`: []Refund
	fmt.Fprintf(os.Stdout, "Response from `RefundsChargebacksAPI.RefundsList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRefundsListRequest struct via the builder pattern


### Return type

[**[]Refund**](Refund.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

