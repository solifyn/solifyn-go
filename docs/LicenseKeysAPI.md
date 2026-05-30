# \LicenseKeysAPI

All URIs are relative to *http://localhost:8000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**LicensesCreate**](LicenseKeysAPI.md#LicensesCreate) | **Post** /v1/licenses | Create License Key
[**LicensesDeleteInstance**](LicenseKeysAPI.md#LicensesDeleteInstance) | **Delete** /v1/licenses/instances/{instanceId} | Force Delete Instance
[**LicensesGet**](LicenseKeysAPI.md#LicensesGet) | **Get** /v1/licenses/{id} | Get License Key
[**LicensesGetInstance**](LicenseKeysAPI.md#LicensesGetInstance) | **Get** /v1/licenses/{id}/instances/{instanceId} | Get License Key Instance
[**LicensesGetInstances**](LicenseKeysAPI.md#LicensesGetInstances) | **Get** /v1/licenses/{id}/instances | Get License Key Instances
[**LicensesList**](LicenseKeysAPI.md#LicensesList) | **Get** /v1/licenses | List License Keys
[**LicensesToggle**](LicenseKeysAPI.md#LicensesToggle) | **Post** /v1/licenses/{id}/toggle | Toggle License Status
[**LicensesUpdate**](LicenseKeysAPI.md#LicensesUpdate) | **Patch** /v1/licenses/{id} | Update License Key
[**LicensesUpdateInstance**](LicenseKeysAPI.md#LicensesUpdateInstance) | **Patch** /v1/licenses/{id}/instances/{instanceId} | Update License Key Instance
[**LicensesUpdateInstancePost**](LicenseKeysAPI.md#LicensesUpdateInstancePost) | **Post** /v1/licenses/{id}/instances/{instanceId} | Update License Key Instance (POST)



## LicensesCreate

> License LicensesCreate(ctx).LicensesCreateRequest(licensesCreateRequest).Execute()

Create License Key



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
	licensesCreateRequest := *openapiclient.NewLicensesCreateRequest("ProductId_example", "CustomerId_example") // LicensesCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysAPI.LicensesCreate(context.Background()).LicensesCreateRequest(licensesCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysAPI.LicensesCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesCreate`: License
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysAPI.LicensesCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLicensesCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **licensesCreateRequest** | [**LicensesCreateRequest**](LicensesCreateRequest.md) |  | 

### Return type

[**License**](License.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LicensesDeleteInstance

> Instance LicensesDeleteInstance(ctx, instanceId).Execute()

Force Delete Instance



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
	instanceId := "inc_123" // string | The unique hardware activation instance ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysAPI.LicensesDeleteInstance(context.Background(), instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysAPI.LicensesDeleteInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesDeleteInstance`: Instance
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysAPI.LicensesDeleteInstance`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | The unique hardware activation instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLicensesDeleteInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Instance**](Instance.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LicensesGet

> License LicensesGet(ctx, id).Execute()

Get License Key



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The unique license key ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysAPI.LicensesGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysAPI.LicensesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesGet`: License
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysAPI.LicensesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique license key ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLicensesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**License**](License.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LicensesGetInstance

> Instance LicensesGetInstance(ctx, id, instanceId).Execute()

Get License Key Instance



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The unique administrative identifier (ID) of the parent license key.
	instanceId := "inc_123" // string | The client-generated instance ID (hardware hash) or the internal database ID of the instance.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysAPI.LicensesGetInstance(context.Background(), id, instanceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysAPI.LicensesGetInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesGetInstance`: Instance
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysAPI.LicensesGetInstance`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique administrative identifier (ID) of the parent license key. | 
**instanceId** | **string** | The client-generated instance ID (hardware hash) or the internal database ID of the instance. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLicensesGetInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**Instance**](Instance.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LicensesGetInstances

> []Instance LicensesGetInstances(ctx, id).Execute()

Get License Key Instances



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
	id := "lic_123" // string | The unique administrative identifier (ID) of the parent license key.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysAPI.LicensesGetInstances(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysAPI.LicensesGetInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesGetInstances`: []Instance
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysAPI.LicensesGetInstances`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique administrative identifier (ID) of the parent license key. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLicensesGetInstancesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]Instance**](Instance.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LicensesList

> []License LicensesList(ctx).Execute()

List License Keys



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
	resp, r, err := apiClient.LicenseKeysAPI.LicensesList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysAPI.LicensesList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesList`: []License
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysAPI.LicensesList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiLicensesListRequest struct via the builder pattern


### Return type

[**[]License**](License.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LicensesToggle

> License LicensesToggle(ctx, id).Execute()

Toggle License Status



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
	id := "lic_123" // string | The unique license key ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysAPI.LicensesToggle(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysAPI.LicensesToggle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesToggle`: License
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysAPI.LicensesToggle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique license key ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLicensesToggleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**License**](License.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LicensesUpdate

> License LicensesUpdate(ctx, id).LicensesUpdateRequest(licensesUpdateRequest).Execute()

Update License Key



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The unique license key ID.
	licensesUpdateRequest := *openapiclient.NewLicensesUpdateRequest() // LicensesUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysAPI.LicensesUpdate(context.Background(), id).LicensesUpdateRequest(licensesUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysAPI.LicensesUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesUpdate`: License
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysAPI.LicensesUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique license key ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLicensesUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **licensesUpdateRequest** | [**LicensesUpdateRequest**](LicensesUpdateRequest.md) |  | 

### Return type

[**License**](License.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LicensesUpdateInstance

> Instance LicensesUpdateInstance(ctx, instanceId, id).LicensesUpdateInstancePostRequest(licensesUpdateInstancePostRequest).Execute()

Update License Key Instance



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
	instanceId := "inc_123" // string | The client-generated instance ID (hardware hash) or the internal database ID of the instance.
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The unique administrative identifier (ID) of the parent license key.
	licensesUpdateInstancePostRequest := *openapiclient.NewLicensesUpdateInstancePostRequest() // LicensesUpdateInstancePostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysAPI.LicensesUpdateInstance(context.Background(), instanceId, id).LicensesUpdateInstancePostRequest(licensesUpdateInstancePostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysAPI.LicensesUpdateInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesUpdateInstance`: Instance
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysAPI.LicensesUpdateInstance`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | The client-generated instance ID (hardware hash) or the internal database ID of the instance. | 
**id** | **string** | The unique administrative identifier (ID) of the parent license key. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLicensesUpdateInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **licensesUpdateInstancePostRequest** | [**LicensesUpdateInstancePostRequest**](LicensesUpdateInstancePostRequest.md) |  | 

### Return type

[**Instance**](Instance.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LicensesUpdateInstancePost

> Instance LicensesUpdateInstancePost(ctx, instanceId, id).LicensesUpdateInstancePostRequest(licensesUpdateInstancePostRequest).Execute()

Update License Key Instance (POST)



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
	instanceId := "inc_123" // string | The client-generated instance ID (hardware hash) or the internal database ID of the instance.
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The unique administrative identifier (ID) of the parent license key.
	licensesUpdateInstancePostRequest := *openapiclient.NewLicensesUpdateInstancePostRequest() // LicensesUpdateInstancePostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysAPI.LicensesUpdateInstancePost(context.Background(), instanceId, id).LicensesUpdateInstancePostRequest(licensesUpdateInstancePostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysAPI.LicensesUpdateInstancePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesUpdateInstancePost`: Instance
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysAPI.LicensesUpdateInstancePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | The client-generated instance ID (hardware hash) or the internal database ID of the instance. | 
**id** | **string** | The unique administrative identifier (ID) of the parent license key. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLicensesUpdateInstancePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **licensesUpdateInstancePostRequest** | [**LicensesUpdateInstancePostRequest**](LicensesUpdateInstancePostRequest.md) |  | 

### Return type

[**Instance**](Instance.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

