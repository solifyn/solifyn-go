# \CheckoutAPI

All URIs are relative to *http://localhost:8000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CheckoutCreate**](CheckoutAPI.md#CheckoutCreate) | **Post** /v1/checkout/create | Create Checkout Session
[**CheckoutCreateCollection**](CheckoutAPI.md#CheckoutCreateCollection) | **Post** /v1/checkout/collection/create | Create Collection Checkout Session
[**CheckoutCreateSetup**](CheckoutAPI.md#CheckoutCreateSetup) | **Post** /v1/checkout/setup-configuration | Create Setup Checkout Configuration
[**CheckoutGetSession**](CheckoutAPI.md#CheckoutGetSession) | **Get** /v1/checkout/session/{id} | Get Checkout Session Details
[**CheckoutPricePreview**](CheckoutAPI.md#CheckoutPricePreview) | **Get** /v1/checkout/price-preview | Get Converted Price Preview
[**CheckoutSupportedCurrencies**](CheckoutAPI.md#CheckoutSupportedCurrencies) | **Get** /v1/checkout/supported-currencies | Get Supported Currencies



## CheckoutCreate

> CheckoutResponseDto CheckoutCreate(ctx).CreateCheckoutDto(createCheckoutDto).Execute()

Create Checkout Session



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
	createCheckoutDto := *openapiclient.NewCreateCheckoutDto("prod_XXXXXXXXXXX") // CreateCheckoutDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CheckoutAPI.CheckoutCreate(context.Background()).CreateCheckoutDto(createCheckoutDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CheckoutAPI.CheckoutCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckoutCreate`: CheckoutResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CheckoutAPI.CheckoutCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCheckoutCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCheckoutDto** | [**CreateCheckoutDto**](CreateCheckoutDto.md) |  | 

### Return type

[**CheckoutResponseDto**](CheckoutResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckoutCreateCollection

> CheckoutResponseDto CheckoutCreateCollection(ctx).CreateCollectionCheckoutDto(createCollectionCheckoutDto).Execute()

Create Collection Checkout Session



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
	createCollectionCheckoutDto := *openapiclient.NewCreateCollectionCheckoutDto("col_123") // CreateCollectionCheckoutDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CheckoutAPI.CheckoutCreateCollection(context.Background()).CreateCollectionCheckoutDto(createCollectionCheckoutDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CheckoutAPI.CheckoutCreateCollection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckoutCreateCollection`: CheckoutResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CheckoutAPI.CheckoutCreateCollection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCheckoutCreateCollectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCollectionCheckoutDto** | [**CreateCollectionCheckoutDto**](CreateCollectionCheckoutDto.md) |  | 

### Return type

[**CheckoutResponseDto**](CheckoutResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckoutCreateSetup

> CheckoutCreateSetup(ctx).CreateSetupCheckoutDto(createSetupCheckoutDto).Execute()

Create Setup Checkout Configuration



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
	createSetupCheckoutDto := *openapiclient.NewCreateSetupCheckoutDto("biz_xxxxxxxxxxxxxx") // CreateSetupCheckoutDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CheckoutAPI.CheckoutCreateSetup(context.Background()).CreateSetupCheckoutDto(createSetupCheckoutDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CheckoutAPI.CheckoutCreateSetup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCheckoutCreateSetupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createSetupCheckoutDto** | [**CreateSetupCheckoutDto**](CreateSetupCheckoutDto.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckoutGetSession

> CheckoutSessionDetailsDto CheckoutGetSession(ctx, id).Execute()

Get Checkout Session Details



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
	id := "ch_XXXXXXXXXXX" // string | Internal database checkout session ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CheckoutAPI.CheckoutGetSession(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CheckoutAPI.CheckoutGetSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckoutGetSession`: CheckoutSessionDetailsDto
	fmt.Fprintf(os.Stdout, "Response from `CheckoutAPI.CheckoutGetSession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Internal database checkout session ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCheckoutGetSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CheckoutSessionDetailsDto**](CheckoutSessionDetailsDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckoutPricePreview

> PricePreviewResponseDto CheckoutPricePreview(ctx).ProductId(productId).Addons(addons).Currency(currency).Discount(discount).Qty(qty).CustomPrice(customPrice).Execute()

Get Converted Price Preview



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
	productId := "prod_z2o92kEl6cYYX" // string | Public product ID
	addons := "addons_example" // string | 
	currency := "vnd" // string | Target currency code (ISO) (optional)
	discount := "10" // string | Percentage discount rate (optional)
	qty := "1" // string | Number of product units (optional)
	customPrice := "15" // string | Override price for PWYW products (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CheckoutAPI.CheckoutPricePreview(context.Background()).ProductId(productId).Addons(addons).Currency(currency).Discount(discount).Qty(qty).CustomPrice(customPrice).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CheckoutAPI.CheckoutPricePreview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckoutPricePreview`: PricePreviewResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CheckoutAPI.CheckoutPricePreview`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCheckoutPricePreviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productId** | **string** | Public product ID | 
 **addons** | **string** |  | 
 **currency** | **string** | Target currency code (ISO) | 
 **discount** | **string** | Percentage discount rate | 
 **qty** | **string** | Number of product units | 
 **customPrice** | **string** | Override price for PWYW products | 

### Return type

[**PricePreviewResponseDto**](PricePreviewResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckoutSupportedCurrencies

> []SupportedCurrenciesResponseDto CheckoutSupportedCurrencies(ctx).Execute()

Get Supported Currencies



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
	resp, r, err := apiClient.CheckoutAPI.CheckoutSupportedCurrencies(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CheckoutAPI.CheckoutSupportedCurrencies``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckoutSupportedCurrencies`: []SupportedCurrenciesResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CheckoutAPI.CheckoutSupportedCurrencies`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCheckoutSupportedCurrenciesRequest struct via the builder pattern


### Return type

[**[]SupportedCurrenciesResponseDto**](SupportedCurrenciesResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

