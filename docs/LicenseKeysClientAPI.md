# \LicenseKeysClientAPI

All URIs are relative to *http://localhost:8000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**LicensesActivate**](LicenseKeysClientAPI.md#LicensesActivate) | **Post** /v1/licenses/activate | Activate License Key
[**LicensesDeactivate**](LicenseKeysClientAPI.md#LicensesDeactivate) | **Post** /v1/licenses/deactivate/{instanceId} | Deactivate Instance
[**LicensesInstances**](LicenseKeysClientAPI.md#LicensesInstances) | **Get** /v1/licenses/instances/{licenseId} | Get Active Instances
[**LicensesVerify**](LicenseKeysClientAPI.md#LicensesVerify) | **Post** /v1/licenses/verify | Validate License Key



## LicensesActivate

> Instance LicensesActivate(ctx).LicensesActivateRequest(licensesActivateRequest).Execute()

Activate License Key



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
	licensesActivateRequest := *openapiclient.NewLicensesActivateRequest("Key_example", "DeviceIdentifier_example", "Name_example") // LicensesActivateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysClientAPI.LicensesActivate(context.Background()).LicensesActivateRequest(licensesActivateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysClientAPI.LicensesActivate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesActivate`: Instance
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysClientAPI.LicensesActivate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLicensesActivateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **licensesActivateRequest** | [**LicensesActivateRequest**](LicensesActivateRequest.md) |  | 

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


## LicensesDeactivate

> LicensesDeactivate200Response LicensesDeactivate(ctx, instanceId).LicensesDeactivateRequest(licensesDeactivateRequest).Execute()

Deactivate Instance



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
	instanceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The unique device instance ID.
	licensesDeactivateRequest := *openapiclient.NewLicensesDeactivateRequest("Key_example") // LicensesDeactivateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysClientAPI.LicensesDeactivate(context.Background(), instanceId).LicensesDeactivateRequest(licensesDeactivateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysClientAPI.LicensesDeactivate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesDeactivate`: LicensesDeactivate200Response
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysClientAPI.LicensesDeactivate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**instanceId** | **string** | The unique device instance ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLicensesDeactivateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **licensesDeactivateRequest** | [**LicensesDeactivateRequest**](LicensesDeactivateRequest.md) |  | 

### Return type

[**LicensesDeactivate200Response**](LicensesDeactivate200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LicensesInstances

> []Instance LicensesInstances(ctx, licenseId).Execute()

Get Active Instances



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
	licenseId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The unique license key ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysClientAPI.LicensesInstances(context.Background(), licenseId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysClientAPI.LicensesInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesInstances`: []Instance
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysClientAPI.LicensesInstances`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**licenseId** | **string** | The unique license key ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLicensesInstancesRequest struct via the builder pattern


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


## LicensesVerify

> LicenseValidationResponse LicensesVerify(ctx).LicensesVerifyRequest(licensesVerifyRequest).Execute()

Validate License Key



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
	licensesVerifyRequest := *openapiclient.NewLicensesVerifyRequest("Key_example", "ProductId_example") // LicensesVerifyRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicenseKeysClientAPI.LicensesVerify(context.Background()).LicensesVerifyRequest(licensesVerifyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicenseKeysClientAPI.LicensesVerify``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LicensesVerify`: LicenseValidationResponse
	fmt.Fprintf(os.Stdout, "Response from `LicenseKeysClientAPI.LicensesVerify`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLicensesVerifyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **licensesVerifyRequest** | [**LicensesVerifyRequest**](LicensesVerifyRequest.md) |  | 

### Return type

[**LicenseValidationResponse**](LicenseValidationResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

