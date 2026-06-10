# \DiscordIntegrationAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DiscordGetInstallUrl**](DiscordIntegrationAPI.md#DiscordGetInstallUrl) | **Get** /v1/discord/install | Get Discord Bot Installation URL
[**DiscordListRoles**](DiscordIntegrationAPI.md#DiscordListRoles) | **Get** /v1/discord/roles | List Guild Discord Roles



## DiscordGetInstallUrl

> DiscordGetInstallUrl(ctx).ProductId(productId).Execute()

Get Discord Bot Installation URL



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
	productId := "productId_example" // string | Optional Product ID to redirect back to after installation (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DiscordIntegrationAPI.DiscordGetInstallUrl(context.Background()).ProductId(productId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DiscordIntegrationAPI.DiscordGetInstallUrl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDiscordGetInstallUrlRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productId** | **string** | Optional Product ID to redirect back to after installation | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DiscordListRoles

> []DiscordRolesResponseDto DiscordListRoles(ctx).Execute()

List Guild Discord Roles



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
	resp, r, err := apiClient.DiscordIntegrationAPI.DiscordListRoles(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DiscordIntegrationAPI.DiscordListRoles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DiscordListRoles`: []DiscordRolesResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DiscordIntegrationAPI.DiscordListRoles`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDiscordListRolesRequest struct via the builder pattern


### Return type

[**[]DiscordRolesResponseDto**](DiscordRolesResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

