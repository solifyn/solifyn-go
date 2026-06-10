# \GitHubIntegrationAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GithubGetInstallUrl**](GitHubIntegrationAPI.md#GithubGetInstallUrl) | **Get** /v1/github/install | Get GitHub App Installation URL
[**GithubListRepos**](GitHubIntegrationAPI.md#GithubListRepos) | **Get** /v1/github/repos | List Available GitHub Repositories



## GithubGetInstallUrl

> GithubGetInstallUrl(ctx).ProductId(productId).Execute()

Get GitHub App Installation URL



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
	r, err := apiClient.GitHubIntegrationAPI.GithubGetInstallUrl(context.Background()).ProductId(productId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GitHubIntegrationAPI.GithubGetInstallUrl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGithubGetInstallUrlRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productId** | **string** | Optional Product ID to redirect back to after installation | 

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


## GithubListRepos

> []GithubReposResponseDto GithubListRepos(ctx).Execute()

List Available GitHub Repositories



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
	resp, r, err := apiClient.GitHubIntegrationAPI.GithubListRepos(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GitHubIntegrationAPI.GithubListRepos``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GithubListRepos`: []GithubReposResponseDto
	fmt.Fprintf(os.Stdout, "Response from `GitHubIntegrationAPI.GithubListRepos`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGithubListReposRequest struct via the builder pattern


### Return type

[**[]GithubReposResponseDto**](GithubReposResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

