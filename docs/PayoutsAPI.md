# \PayoutsAPI

All URIs are relative to *http://localhost:8000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PayoutsCreateWithdrawal**](PayoutsAPI.md#PayoutsCreateWithdrawal) | **Post** /v1/payouts/withdrawals | Create Withdrawal
[**PayoutsGetAccount**](PayoutsAPI.md#PayoutsGetAccount) | **Get** /v1/payouts/account | Retrieve Payout Account
[**PayoutsGetAccountLink**](PayoutsAPI.md#PayoutsGetAccountLink) | **Get** /v1/payouts/account-link | Create Account Link
[**PayoutsGetToken**](PayoutsAPI.md#PayoutsGetToken) | **Get** /v1/payouts/token | Generate Portal Access Token
[**PayoutsGetWithdrawals**](PayoutsAPI.md#PayoutsGetWithdrawals) | **Get** /v1/payouts/withdrawals | Get Withdrawals List
[**PayoutsListMethods**](PayoutsAPI.md#PayoutsListMethods) | **Get** /v1/payouts/methods | List Payout Methods
[**PayoutsListVerifications**](PayoutsAPI.md#PayoutsListVerifications) | **Get** /v1/payouts/verifications | List Verifications
[**PayoutsListWithdrawals**](PayoutsAPI.md#PayoutsListWithdrawals) | **Get** /v1/payouts | List Withdrawals



## PayoutsCreateWithdrawal

> Withdrawal PayoutsCreateWithdrawal(ctx).WithdrawalCreate(withdrawalCreate).Execute()

Create Withdrawal



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
	withdrawalCreate := *openapiclient.NewWithdrawalCreate(float32(1000), "usd") // WithdrawalCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PayoutsAPI.PayoutsCreateWithdrawal(context.Background()).WithdrawalCreate(withdrawalCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PayoutsAPI.PayoutsCreateWithdrawal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PayoutsCreateWithdrawal`: Withdrawal
	fmt.Fprintf(os.Stdout, "Response from `PayoutsAPI.PayoutsCreateWithdrawal`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPayoutsCreateWithdrawalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **withdrawalCreate** | [**WithdrawalCreate**](WithdrawalCreate.md) |  | 

### Return type

[**Withdrawal**](Withdrawal.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PayoutsGetAccount

> PayoutAccount PayoutsGetAccount(ctx).Execute()

Retrieve Payout Account



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
	resp, r, err := apiClient.PayoutsAPI.PayoutsGetAccount(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PayoutsAPI.PayoutsGetAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PayoutsGetAccount`: PayoutAccount
	fmt.Fprintf(os.Stdout, "Response from `PayoutsAPI.PayoutsGetAccount`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiPayoutsGetAccountRequest struct via the builder pattern


### Return type

[**PayoutAccount**](PayoutAccount.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PayoutsGetAccountLink

> PayoutAccountLink PayoutsGetAccountLink(ctx).UseCase(useCase).Execute()

Create Account Link



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
	useCase := "useCase_example" // string | Onboarding link type context (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PayoutsAPI.PayoutsGetAccountLink(context.Background()).UseCase(useCase).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PayoutsAPI.PayoutsGetAccountLink``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PayoutsGetAccountLink`: PayoutAccountLink
	fmt.Fprintf(os.Stdout, "Response from `PayoutsAPI.PayoutsGetAccountLink`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPayoutsGetAccountLinkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **useCase** | **string** | Onboarding link type context | 

### Return type

[**PayoutAccountLink**](PayoutAccountLink.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PayoutsGetToken

> PayoutAccessToken PayoutsGetToken(ctx).Execute()

Generate Portal Access Token



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
	resp, r, err := apiClient.PayoutsAPI.PayoutsGetToken(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PayoutsAPI.PayoutsGetToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PayoutsGetToken`: PayoutAccessToken
	fmt.Fprintf(os.Stdout, "Response from `PayoutsAPI.PayoutsGetToken`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiPayoutsGetTokenRequest struct via the builder pattern


### Return type

[**PayoutAccessToken**](PayoutAccessToken.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PayoutsGetWithdrawals

> WithdrawalList PayoutsGetWithdrawals(ctx).Limit(limit).Page(page).Execute()

Get Withdrawals List



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
	limit := float32(8.14) // float32 | Page size limit (optional)
	page := float32(8.14) // float32 | Page number (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PayoutsAPI.PayoutsGetWithdrawals(context.Background()).Limit(limit).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PayoutsAPI.PayoutsGetWithdrawals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PayoutsGetWithdrawals`: WithdrawalList
	fmt.Fprintf(os.Stdout, "Response from `PayoutsAPI.PayoutsGetWithdrawals`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPayoutsGetWithdrawalsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Page size limit | 
 **page** | **float32** | Page number | 

### Return type

[**WithdrawalList**](WithdrawalList.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PayoutsListMethods

> PayoutMethodList PayoutsListMethods(ctx).Limit(limit).Page(page).Execute()

List Payout Methods



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
	limit := float32(8.14) // float32 |  (optional)
	page := float32(8.14) // float32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PayoutsAPI.PayoutsListMethods(context.Background()).Limit(limit).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PayoutsAPI.PayoutsListMethods``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PayoutsListMethods`: PayoutMethodList
	fmt.Fprintf(os.Stdout, "Response from `PayoutsAPI.PayoutsListMethods`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPayoutsListMethodsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** |  | 
 **page** | **float32** |  | 

### Return type

[**PayoutMethodList**](PayoutMethodList.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PayoutsListVerifications

> PayoutVerificationList PayoutsListVerifications(ctx).Limit(limit).Page(page).Execute()

List Verifications



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
	limit := float32(8.14) // float32 |  (optional)
	page := float32(8.14) // float32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PayoutsAPI.PayoutsListVerifications(context.Background()).Limit(limit).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PayoutsAPI.PayoutsListVerifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PayoutsListVerifications`: PayoutVerificationList
	fmt.Fprintf(os.Stdout, "Response from `PayoutsAPI.PayoutsListVerifications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPayoutsListVerificationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** |  | 
 **page** | **float32** |  | 

### Return type

[**PayoutVerificationList**](PayoutVerificationList.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PayoutsListWithdrawals

> WithdrawalList PayoutsListWithdrawals(ctx).Limit(limit).Page(page).Execute()

List Withdrawals



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
	limit := float32(8.14) // float32 | Page size limit (optional)
	page := float32(8.14) // float32 | Page number (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PayoutsAPI.PayoutsListWithdrawals(context.Background()).Limit(limit).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PayoutsAPI.PayoutsListWithdrawals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PayoutsListWithdrawals`: WithdrawalList
	fmt.Fprintf(os.Stdout, "Response from `PayoutsAPI.PayoutsListWithdrawals`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPayoutsListWithdrawalsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **float32** | Page size limit | 
 **page** | **float32** | Page number | 

### Return type

[**WithdrawalList**](WithdrawalList.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

