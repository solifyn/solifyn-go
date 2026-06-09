# \SubscriptionsAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SubscriptionsAction**](SubscriptionsAPI.md#SubscriptionsAction) | **Post** /v1/subscriptions/{subscriptionId}/{action} | Subscription Action
[**SubscriptionsGet**](SubscriptionsAPI.md#SubscriptionsGet) | **Get** /v1/subscriptions/{id} | Retrieve Subscription Details
[**SubscriptionsList**](SubscriptionsAPI.md#SubscriptionsList) | **Get** /v1/subscriptions | List Subscriptions



## SubscriptionsAction

> SubscriptionsAction201Response SubscriptionsAction(ctx, subscriptionId, action).SubscriptionAction(subscriptionAction).Execute()

Subscription Action



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
	subscriptionId := "mem_123" // string | The customer subscription ID
	action := "action_example" // string | The subscription task to execute
	subscriptionAction := *openapiclient.NewSubscriptionAction() // SubscriptionAction | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionsAPI.SubscriptionsAction(context.Background(), subscriptionId, action).SubscriptionAction(subscriptionAction).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionsAPI.SubscriptionsAction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubscriptionsAction`: SubscriptionsAction201Response
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionsAPI.SubscriptionsAction`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**subscriptionId** | **string** | The customer subscription ID | 
**action** | **string** | The subscription task to execute | 

### Other Parameters

Other parameters are passed through a pointer to a apiSubscriptionsActionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **subscriptionAction** | [**SubscriptionAction**](SubscriptionAction.md) |  | 

### Return type

[**SubscriptionsAction201Response**](SubscriptionsAction201Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubscriptionsGet

> SubscriptionDetail SubscriptionsGet(ctx, id).Execute()

Retrieve Subscription Details



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
	id := "mem_123" // string | The customer subscription ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionsAPI.SubscriptionsGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionsAPI.SubscriptionsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubscriptionsGet`: SubscriptionDetail
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionsAPI.SubscriptionsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The customer subscription ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiSubscriptionsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SubscriptionDetail**](SubscriptionDetail.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubscriptionsList

> SubscriptionList SubscriptionsList(ctx).CustomerId(customerId).Execute()

List Subscriptions



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
	customerId := "customerId_example" // string | Filter subscriptions by customer ID. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionsAPI.SubscriptionsList(context.Background()).CustomerId(customerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionsAPI.SubscriptionsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubscriptionsList`: SubscriptionList
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionsAPI.SubscriptionsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSubscriptionsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customerId** | **string** | Filter subscriptions by customer ID. | 

### Return type

[**SubscriptionList**](SubscriptionList.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

