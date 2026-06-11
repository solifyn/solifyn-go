# \EntitlementsAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EntitlementsCreate**](EntitlementsAPI.md#EntitlementsCreate) | **Post** /v1/entitlements | Create Entitlement
[**EntitlementsDelete**](EntitlementsAPI.md#EntitlementsDelete) | **Delete** /v1/entitlements/{id} | Delete Entitlement
[**EntitlementsGet**](EntitlementsAPI.md#EntitlementsGet) | **Get** /v1/entitlements/{id} | Retrieve Entitlement
[**EntitlementsList**](EntitlementsAPI.md#EntitlementsList) | **Get** /v1/entitlements | List Entitlements
[**EntitlementsUpdate**](EntitlementsAPI.md#EntitlementsUpdate) | **Patch** /v1/entitlements/{id} | Update Entitlement



## EntitlementsCreate

> EntitlementDetailResponseDto EntitlementsCreate(ctx).CreateEntitlementDto(createEntitlementDto).Execute()

Create Entitlement



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
	createEntitlementDto := *openapiclient.NewCreateEntitlementDto("Premium GitHub Access", "GITHUB") // CreateEntitlementDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EntitlementsAPI.EntitlementsCreate(context.Background()).CreateEntitlementDto(createEntitlementDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementsAPI.EntitlementsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EntitlementsCreate`: EntitlementDetailResponseDto
	fmt.Fprintf(os.Stdout, "Response from `EntitlementsAPI.EntitlementsCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEntitlementsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createEntitlementDto** | [**CreateEntitlementDto**](CreateEntitlementDto.md) |  | 

### Return type

[**EntitlementDetailResponseDto**](EntitlementDetailResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EntitlementsDelete

> EntitlementDetailResponseDto EntitlementsDelete(ctx, id).Execute()

Delete Entitlement



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
	id := "ent_8Z1aB2cD3eF4gH5iJ6kL7m" // string | The unique entitlement ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EntitlementsAPI.EntitlementsDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementsAPI.EntitlementsDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EntitlementsDelete`: EntitlementDetailResponseDto
	fmt.Fprintf(os.Stdout, "Response from `EntitlementsAPI.EntitlementsDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique entitlement ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEntitlementsDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EntitlementDetailResponseDto**](EntitlementDetailResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EntitlementsGet

> EntitlementDetailResponseDto EntitlementsGet(ctx, id).Execute()

Retrieve Entitlement



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
	id := "ent_8Z1aB2cD3eF4gH5iJ6kL7m" // string | The unique entitlement ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EntitlementsAPI.EntitlementsGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementsAPI.EntitlementsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EntitlementsGet`: EntitlementDetailResponseDto
	fmt.Fprintf(os.Stdout, "Response from `EntitlementsAPI.EntitlementsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique entitlement ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEntitlementsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EntitlementDetailResponseDto**](EntitlementDetailResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EntitlementsList

> []EntitlementDetailResponseDto EntitlementsList(ctx).Execute()

List Entitlements



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
	resp, r, err := apiClient.EntitlementsAPI.EntitlementsList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementsAPI.EntitlementsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EntitlementsList`: []EntitlementDetailResponseDto
	fmt.Fprintf(os.Stdout, "Response from `EntitlementsAPI.EntitlementsList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiEntitlementsListRequest struct via the builder pattern


### Return type

[**[]EntitlementDetailResponseDto**](EntitlementDetailResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EntitlementsUpdate

> EntitlementDetailResponseDto EntitlementsUpdate(ctx, id).UpdateEntitlementDto(updateEntitlementDto).Execute()

Update Entitlement



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
	id := "ent_8Z1aB2cD3eF4gH5iJ6kL7m" // string | The unique entitlement ID.
	updateEntitlementDto := *openapiclient.NewUpdateEntitlementDto() // UpdateEntitlementDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EntitlementsAPI.EntitlementsUpdate(context.Background(), id).UpdateEntitlementDto(updateEntitlementDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementsAPI.EntitlementsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EntitlementsUpdate`: EntitlementDetailResponseDto
	fmt.Fprintf(os.Stdout, "Response from `EntitlementsAPI.EntitlementsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique entitlement ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEntitlementsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateEntitlementDto** | [**UpdateEntitlementDto**](UpdateEntitlementDto.md) |  | 

### Return type

[**EntitlementDetailResponseDto**](EntitlementDetailResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

