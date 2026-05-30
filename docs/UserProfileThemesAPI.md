# \UserProfileThemesAPI

All URIs are relative to *http://localhost:8000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**UsersGetMyPage**](UserProfileThemesAPI.md#UsersGetMyPage) | **Get** /v1/user/my-page | Get My Page details
[**UsersGetMyTheme**](UserProfileThemesAPI.md#UsersGetMyTheme) | **Get** /v1/user/my-theme | Get My Theme
[**UsersGetSettings**](UserProfileThemesAPI.md#UsersGetSettings) | **Get** /v1/user/settings | Retrieve User Settings
[**UsersGetStats**](UserProfileThemesAPI.md#UsersGetStats) | **Get** /v1/user/dashboard-stats | Get Dashboard Statistics
[**UsersGetThemeBySubdomain**](UserProfileThemesAPI.md#UsersGetThemeBySubdomain) | **Get** /v1/user/theme/{subdomain} | Get Theme by Subdomain



## UsersGetMyPage

> UserPage UsersGetMyPage(ctx).Execute()

Get My Page details



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
	resp, r, err := apiClient.UserProfileThemesAPI.UsersGetMyPage(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserProfileThemesAPI.UsersGetMyPage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UsersGetMyPage`: UserPage
	fmt.Fprintf(os.Stdout, "Response from `UserProfileThemesAPI.UsersGetMyPage`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiUsersGetMyPageRequest struct via the builder pattern


### Return type

[**UserPage**](UserPage.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UsersGetMyTheme

> UserTheme UsersGetMyTheme(ctx).Execute()

Get My Theme



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
	resp, r, err := apiClient.UserProfileThemesAPI.UsersGetMyTheme(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserProfileThemesAPI.UsersGetMyTheme``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UsersGetMyTheme`: UserTheme
	fmt.Fprintf(os.Stdout, "Response from `UserProfileThemesAPI.UsersGetMyTheme`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiUsersGetMyThemeRequest struct via the builder pattern


### Return type

[**UserTheme**](UserTheme.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UsersGetSettings

> UserSettings UsersGetSettings(ctx).Execute()

Retrieve User Settings



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
	resp, r, err := apiClient.UserProfileThemesAPI.UsersGetSettings(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserProfileThemesAPI.UsersGetSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UsersGetSettings`: UserSettings
	fmt.Fprintf(os.Stdout, "Response from `UserProfileThemesAPI.UsersGetSettings`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiUsersGetSettingsRequest struct via the builder pattern


### Return type

[**UserSettings**](UserSettings.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UsersGetStats

> UserStats UsersGetStats(ctx).Execute()

Get Dashboard Statistics



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
	resp, r, err := apiClient.UserProfileThemesAPI.UsersGetStats(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserProfileThemesAPI.UsersGetStats``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UsersGetStats`: UserStats
	fmt.Fprintf(os.Stdout, "Response from `UserProfileThemesAPI.UsersGetStats`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiUsersGetStatsRequest struct via the builder pattern


### Return type

[**UserStats**](UserStats.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UsersGetThemeBySubdomain

> UserTheme UsersGetThemeBySubdomain(ctx, subdomain).Execute()

Get Theme by Subdomain



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
	subdomain := "acme" // string | The subdomain of the store

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserProfileThemesAPI.UsersGetThemeBySubdomain(context.Background(), subdomain).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserProfileThemesAPI.UsersGetThemeBySubdomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UsersGetThemeBySubdomain`: UserTheme
	fmt.Fprintf(os.Stdout, "Response from `UserProfileThemesAPI.UsersGetThemeBySubdomain`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**subdomain** | **string** | The subdomain of the store | 

### Other Parameters

Other parameters are passed through a pointer to a apiUsersGetThemeBySubdomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UserTheme**](UserTheme.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

