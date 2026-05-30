# \BusinessesAPI

All URIs are relative to *http://localhost:8000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BusinessesBillingHistory**](BusinessesAPI.md#BusinessesBillingHistory) | **Get** /v1/user/billing/history | Get Platform Billing History
[**MerchantsGenerateApiKeys**](BusinessesAPI.md#MerchantsGenerateApiKeys) | **Post** /v1/user/whop-api-keys | Rotate Whop API Keys
[**MerchantsUpdatePage**](BusinessesAPI.md#MerchantsUpdatePage) | **Patch** /v1/user/page | Update Page configuration
[**MerchantsUpdateSettings**](BusinessesAPI.md#MerchantsUpdateSettings) | **Patch** /v1/user/settings | Update Merchant Settings
[**MerchantsUpdateTheme**](BusinessesAPI.md#MerchantsUpdateTheme) | **Patch** /v1/user/theme | Update Theme



## BusinessesBillingHistory

> BusinessesBillingHistory(ctx).Execute()

Get Platform Billing History



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
	r, err := apiClient.BusinessesAPI.BusinessesBillingHistory(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BusinessesAPI.BusinessesBillingHistory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiBusinessesBillingHistoryRequest struct via the builder pattern


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


## MerchantsGenerateApiKeys

> WhopApiKeysRotation MerchantsGenerateApiKeys(ctx).Execute()

Rotate Whop API Keys



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
	resp, r, err := apiClient.BusinessesAPI.MerchantsGenerateApiKeys(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BusinessesAPI.MerchantsGenerateApiKeys``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MerchantsGenerateApiKeys`: WhopApiKeysRotation
	fmt.Fprintf(os.Stdout, "Response from `BusinessesAPI.MerchantsGenerateApiKeys`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiMerchantsGenerateApiKeysRequest struct via the builder pattern


### Return type

[**WhopApiKeysRotation**](WhopApiKeysRotation.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MerchantsUpdatePage

> UserPage MerchantsUpdatePage(ctx).UserThemeUpdate(userThemeUpdate).Execute()

Update Page configuration



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
	userThemeUpdate := *openapiclient.NewUserThemeUpdate() // UserThemeUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BusinessesAPI.MerchantsUpdatePage(context.Background()).UserThemeUpdate(userThemeUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BusinessesAPI.MerchantsUpdatePage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MerchantsUpdatePage`: UserPage
	fmt.Fprintf(os.Stdout, "Response from `BusinessesAPI.MerchantsUpdatePage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMerchantsUpdatePageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userThemeUpdate** | [**UserThemeUpdate**](UserThemeUpdate.md) |  | 

### Return type

[**UserPage**](UserPage.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MerchantsUpdateSettings

> UserSettings MerchantsUpdateSettings(ctx).UserSettingsUpdate(userSettingsUpdate).Execute()

Update Merchant Settings



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
	userSettingsUpdate := *openapiclient.NewUserSettingsUpdate() // UserSettingsUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BusinessesAPI.MerchantsUpdateSettings(context.Background()).UserSettingsUpdate(userSettingsUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BusinessesAPI.MerchantsUpdateSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MerchantsUpdateSettings`: UserSettings
	fmt.Fprintf(os.Stdout, "Response from `BusinessesAPI.MerchantsUpdateSettings`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMerchantsUpdateSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userSettingsUpdate** | [**UserSettingsUpdate**](UserSettingsUpdate.md) |  | 

### Return type

[**UserSettings**](UserSettings.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MerchantsUpdateTheme

> UserTheme MerchantsUpdateTheme(ctx).UserThemeUpdate(userThemeUpdate).Execute()

Update Theme



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
	userThemeUpdate := *openapiclient.NewUserThemeUpdate() // UserThemeUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BusinessesAPI.MerchantsUpdateTheme(context.Background()).UserThemeUpdate(userThemeUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BusinessesAPI.MerchantsUpdateTheme``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MerchantsUpdateTheme`: UserTheme
	fmt.Fprintf(os.Stdout, "Response from `BusinessesAPI.MerchantsUpdateTheme`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMerchantsUpdateThemeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userThemeUpdate** | [**UserThemeUpdate**](UserThemeUpdate.md) |  | 

### Return type

[**UserTheme**](UserTheme.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

