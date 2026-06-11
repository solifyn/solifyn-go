# \FramerIntegrationAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FramerCreateTemplate**](FramerIntegrationAPI.md#FramerCreateTemplate) | **Post** /v1/framer/templates | Create Framer Template
[**FramerDeleteTemplate**](FramerIntegrationAPI.md#FramerDeleteTemplate) | **Delete** /v1/framer/templates/{id} | Delete Framer Template
[**FramerGetTemplate**](FramerIntegrationAPI.md#FramerGetTemplate) | **Get** /v1/framer/templates/{id} | Retrieve Framer Template
[**FramerListTemplates**](FramerIntegrationAPI.md#FramerListTemplates) | **Get** /v1/framer/templates | List Framer Templates
[**FramerUpdateTemplate**](FramerIntegrationAPI.md#FramerUpdateTemplate) | **Put** /v1/framer/templates/{id} | Update Framer Template



## FramerCreateTemplate

> FramerTemplateResponseDto FramerCreateTemplate(ctx).CreateFramerTemplateDto(createFramerTemplateDto).Execute()

Create Framer Template



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
	createFramerTemplateDto := *openapiclient.NewCreateFramerTemplateDto("Portfolio Template", "https://framer.com/projects/xyz") // CreateFramerTemplateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FramerIntegrationAPI.FramerCreateTemplate(context.Background()).CreateFramerTemplateDto(createFramerTemplateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FramerIntegrationAPI.FramerCreateTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FramerCreateTemplate`: FramerTemplateResponseDto
	fmt.Fprintf(os.Stdout, "Response from `FramerIntegrationAPI.FramerCreateTemplate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFramerCreateTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createFramerTemplateDto** | [**CreateFramerTemplateDto**](CreateFramerTemplateDto.md) |  | 

### Return type

[**FramerTemplateResponseDto**](FramerTemplateResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FramerDeleteTemplate

> FramerDeleteTemplate(ctx, id).Execute()

Delete Framer Template



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
	id := "id_example" // string | The Framer template ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FramerIntegrationAPI.FramerDeleteTemplate(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FramerIntegrationAPI.FramerDeleteTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Framer template ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFramerDeleteTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## FramerGetTemplate

> FramerTemplateResponseDto FramerGetTemplate(ctx, id).Execute()

Retrieve Framer Template



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
	id := "id_example" // string | The Framer template ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FramerIntegrationAPI.FramerGetTemplate(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FramerIntegrationAPI.FramerGetTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FramerGetTemplate`: FramerTemplateResponseDto
	fmt.Fprintf(os.Stdout, "Response from `FramerIntegrationAPI.FramerGetTemplate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Framer template ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFramerGetTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FramerTemplateResponseDto**](FramerTemplateResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FramerListTemplates

> []FramerTemplateResponseDto FramerListTemplates(ctx).Execute()

List Framer Templates



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
	resp, r, err := apiClient.FramerIntegrationAPI.FramerListTemplates(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FramerIntegrationAPI.FramerListTemplates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FramerListTemplates`: []FramerTemplateResponseDto
	fmt.Fprintf(os.Stdout, "Response from `FramerIntegrationAPI.FramerListTemplates`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiFramerListTemplatesRequest struct via the builder pattern


### Return type

[**[]FramerTemplateResponseDto**](FramerTemplateResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FramerUpdateTemplate

> FramerTemplateResponseDto FramerUpdateTemplate(ctx, id).UpdateFramerTemplateDto(updateFramerTemplateDto).Execute()

Update Framer Template



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
	id := "id_example" // string | The Framer template ID
	updateFramerTemplateDto := *openapiclient.NewUpdateFramerTemplateDto() // UpdateFramerTemplateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FramerIntegrationAPI.FramerUpdateTemplate(context.Background(), id).UpdateFramerTemplateDto(updateFramerTemplateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FramerIntegrationAPI.FramerUpdateTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FramerUpdateTemplate`: FramerTemplateResponseDto
	fmt.Fprintf(os.Stdout, "Response from `FramerIntegrationAPI.FramerUpdateTemplate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The Framer template ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiFramerUpdateTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateFramerTemplateDto** | [**UpdateFramerTemplateDto**](UpdateFramerTemplateDto.md) |  | 

### Return type

[**FramerTemplateResponseDto**](FramerTemplateResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

