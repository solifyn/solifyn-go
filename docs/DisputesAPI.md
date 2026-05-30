# \DisputesAPI

All URIs are relative to *http://localhost:8000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DisputesGenerateReport**](DisputesAPI.md#DisputesGenerateReport) | **Get** /v1/transactions/disputes/report | Generate Dispute CSV Report
[**DisputesGet**](DisputesAPI.md#DisputesGet) | **Get** /v1/transactions/disputes/{id} | Retrieve Dispute
[**DisputesList**](DisputesAPI.md#DisputesList) | **Get** /v1/transactions/disputes | List Disputes
[**DisputesSubmitEvidence**](DisputesAPI.md#DisputesSubmitEvidence) | **Post** /v1/transactions/disputes/{id}/submit | Submit Dispute Evidence
[**DisputesUpdateEvidence**](DisputesAPI.md#DisputesUpdateEvidence) | **Patch** /v1/transactions/disputes/{id}/evidence | Update Dispute Evidence
[**DisputesUploadEvidenceFile**](DisputesAPI.md#DisputesUploadEvidenceFile) | **Post** /v1/transactions/disputes/upload | Upload Evidence File



## DisputesGenerateReport

> DisputesGenerateReport(ctx).CreatedAtGte(createdAtGte).CreatedAtLte(createdAtLte).Status(status).Execute()

Generate Dispute CSV Report



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
	createdAtGte := "createdAtGte_example" // string | Filter disputes created after this ISO date-time string (optional)
	createdAtLte := "createdAtLte_example" // string | Filter disputes created before this ISO date-time string (optional)
	status := "status_example" // string | Filter disputes by status (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DisputesAPI.DisputesGenerateReport(context.Background()).CreatedAtGte(createdAtGte).CreatedAtLte(createdAtLte).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DisputesAPI.DisputesGenerateReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDisputesGenerateReportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createdAtGte** | **string** | Filter disputes created after this ISO date-time string | 
 **createdAtLte** | **string** | Filter disputes created before this ISO date-time string | 
 **status** | **string** | Filter disputes by status | 

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


## DisputesGet

> Dispute DisputesGet(ctx, id).Execute()

Retrieve Dispute



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
	id := "dsp_123" // string | The dispute ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DisputesAPI.DisputesGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DisputesAPI.DisputesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisputesGet`: Dispute
	fmt.Fprintf(os.Stdout, "Response from `DisputesAPI.DisputesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The dispute ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDisputesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Dispute**](Dispute.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DisputesList

> DisputeList DisputesList(ctx).Page(page).Limit(limit).Status(status).Type_(type_).Execute()

List Disputes



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
	page := "1" // string | Page number for pagination (optional)
	limit := "10" // string | Page size limit for pagination (optional)
	status := "status_example" // string | Filter disputes by status (optional)
	type_ := "type__example" // string | Filter by type: dispute or alert (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DisputesAPI.DisputesList(context.Background()).Page(page).Limit(limit).Status(status).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DisputesAPI.DisputesList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisputesList`: DisputeList
	fmt.Fprintf(os.Stdout, "Response from `DisputesAPI.DisputesList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDisputesListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **string** | Page number for pagination | 
 **limit** | **string** | Page size limit for pagination | 
 **status** | **string** | Filter disputes by status | 
 **type_** | **string** | Filter by type: dispute or alert | 

### Return type

[**DisputeList**](DisputeList.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DisputesSubmitEvidence

> Dispute DisputesSubmitEvidence(ctx, id).Execute()

Submit Dispute Evidence



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
	id := "dsp_123" // string | The dispute ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DisputesAPI.DisputesSubmitEvidence(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DisputesAPI.DisputesSubmitEvidence``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisputesSubmitEvidence`: Dispute
	fmt.Fprintf(os.Stdout, "Response from `DisputesAPI.DisputesSubmitEvidence`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The dispute ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDisputesSubmitEvidenceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Dispute**](Dispute.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DisputesUpdateEvidence

> Dispute DisputesUpdateEvidence(ctx, id).DisputeEvidenceUpdate(disputeEvidenceUpdate).Execute()

Update Dispute Evidence



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
	id := "dsp_123" // string | The dispute ID
	disputeEvidenceUpdate := *openapiclient.NewDisputeEvidenceUpdate() // DisputeEvidenceUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DisputesAPI.DisputesUpdateEvidence(context.Background(), id).DisputeEvidenceUpdate(disputeEvidenceUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DisputesAPI.DisputesUpdateEvidence``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisputesUpdateEvidence`: Dispute
	fmt.Fprintf(os.Stdout, "Response from `DisputesAPI.DisputesUpdateEvidence`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The dispute ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDisputesUpdateEvidenceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **disputeEvidenceUpdate** | [**DisputeEvidenceUpdate**](DisputeEvidenceUpdate.md) |  | 

### Return type

[**Dispute**](Dispute.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DisputesUploadEvidenceFile

> DisputeFileUpload DisputesUploadEvidenceFile(ctx).File(file).Execute()

Upload Evidence File



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
	file := os.NewFile(1234, "some_file") // *os.File | The evidence file to upload (Max 25MB: JPEG, PNG, GIF, WEBP, PDF, MP4, WEBM, QuickTime)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DisputesAPI.DisputesUploadEvidenceFile(context.Background()).File(file).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DisputesAPI.DisputesUploadEvidenceFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisputesUploadEvidenceFile`: DisputeFileUpload
	fmt.Fprintf(os.Stdout, "Response from `DisputesAPI.DisputesUploadEvidenceFile`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDisputesUploadEvidenceFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** | The evidence file to upload (Max 25MB: JPEG, PNG, GIF, WEBP, PDF, MP4, WEBM, QuickTime) | 

### Return type

[**DisputeFileUpload**](DisputeFileUpload.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

