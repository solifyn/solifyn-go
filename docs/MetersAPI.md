# \MetersAPI

All URIs are relative to *http://localhost:8000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EventsIngest**](MetersAPI.md#EventsIngest) | **Post** /v1/meters/ingest | Ingest Events
[**MetersCreate**](MetersAPI.md#MetersCreate) | **Post** /v1/meters | Create Meter
[**MetersGet**](MetersAPI.md#MetersGet) | **Get** /v1/meters/{id} | Retrieve Meter
[**MetersGetEvents**](MetersAPI.md#MetersGetEvents) | **Get** /v1/meters/{id}/events | List Meter Events
[**MetersGetQuantities**](MetersAPI.md#MetersGetQuantities) | **Get** /v1/meters/{id}/quantities | Get Meter Quantities
[**MetersList**](MetersAPI.md#MetersList) | **Get** /v1/meters | List Meters
[**MetersUpdate**](MetersAPI.md#MetersUpdate) | **Patch** /v1/meters/{id} | Update Meter



## EventsIngest

> MeterIngestResponseDto EventsIngest(ctx).MeterIngestRequestDto(meterIngestRequestDto).Execute()

Ingest Events



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
	meterIngestRequestDto := *openapiclient.NewMeterIngestRequestDto([]openapiclient.MeterIngestEventDto{*openapiclient.NewMeterIngestEventDto("evt_9Y3kP4qR7tU1vW2xZ5aB6c", "cus_8n7m6l5k4j3h2g1f0e9d8c", "api.request")}) // MeterIngestRequestDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetersAPI.EventsIngest(context.Background()).MeterIngestRequestDto(meterIngestRequestDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetersAPI.EventsIngest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EventsIngest`: MeterIngestResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MetersAPI.EventsIngest`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEventsIngestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **meterIngestRequestDto** | [**MeterIngestRequestDto**](MeterIngestRequestDto.md) |  | 

### Return type

[**MeterIngestResponseDto**](MeterIngestResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MetersCreate

> MeterResponseDto MetersCreate(ctx).CreateMeterDto(createMeterDto).Execute()

Create Meter



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
	createMeterDto := *openapiclient.NewCreateMeterDto("API Request Count", "api.request", "COUNT") // CreateMeterDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetersAPI.MetersCreate(context.Background()).CreateMeterDto(createMeterDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetersAPI.MetersCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetersCreate`: MeterResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MetersAPI.MetersCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMetersCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createMeterDto** | [**CreateMeterDto**](CreateMeterDto.md) |  | 

### Return type

[**MeterResponseDto**](MeterResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MetersGet

> MeterDetailResponseDto MetersGet(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

Retrieve Meter



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
	id := "mtr_8Z1aB2cD3eF4gH5iJ6kL7m" // string | The unique meter ID.
	startDate := "startDate_example" // string | 
	endDate := "endDate_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetersAPI.MetersGet(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetersAPI.MetersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetersGet`: MeterDetailResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MetersAPI.MetersGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique meter ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiMetersGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** |  | 
 **endDate** | **string** |  | 

### Return type

[**MeterDetailResponseDto**](MeterDetailResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MetersGetEvents

> MeterEventsResponseDto MetersGetEvents(ctx, id).Limit(limit).Execute()

List Meter Events



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
	id := "mtr_8Z1aB2cD3eF4gH5iJ6kL7m" // string | The unique meter ID.
	limit := float32(8.14) // float32 | Maximum number of usage events to return. (optional) (default to 100)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetersAPI.MetersGetEvents(context.Background(), id).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetersAPI.MetersGetEvents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetersGetEvents`: MeterEventsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MetersAPI.MetersGetEvents`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique meter ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiMetersGetEventsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **float32** | Maximum number of usage events to return. | [default to 100]

### Return type

[**MeterEventsResponseDto**](MeterEventsResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MetersGetQuantities

> MeterQuantitiesResponseDto MetersGetQuantities(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

Get Meter Quantities



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
	id := "mtr_8Z1aB2cD3eF4gH5iJ6kL7m" // string | The unique meter ID.
	startDate := "startDate_example" // string | Inclusive start date in ISO 8601 format. (optional)
	endDate := "endDate_example" // string | Inclusive end date in ISO 8601 format. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetersAPI.MetersGetQuantities(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetersAPI.MetersGetQuantities``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetersGetQuantities`: MeterQuantitiesResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MetersAPI.MetersGetQuantities`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique meter ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiMetersGetQuantitiesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Inclusive start date in ISO 8601 format. | 
 **endDate** | **string** | Inclusive end date in ISO 8601 format. | 

### Return type

[**MeterQuantitiesResponseDto**](MeterQuantitiesResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MetersList

> []MeterResponseDto MetersList(ctx).Status(status).Execute()

List Meters



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
	status := "status_example" // string | Filter by meter status. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetersAPI.MetersList(context.Background()).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetersAPI.MetersList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetersList`: []MeterResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MetersAPI.MetersList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMetersListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** | Filter by meter status. | 

### Return type

[**[]MeterResponseDto**](MeterResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MetersUpdate

> MeterResponseDto MetersUpdate(ctx, id).UpdateMeterDto(updateMeterDto).Execute()

Update Meter



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
	id := "mtr_8Z1aB2cD3eF4gH5iJ6kL7m" // string | The unique meter ID.
	updateMeterDto := *openapiclient.NewUpdateMeterDto() // UpdateMeterDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetersAPI.MetersUpdate(context.Background(), id).UpdateMeterDto(updateMeterDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetersAPI.MetersUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetersUpdate`: MeterResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MetersAPI.MetersUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The unique meter ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiMetersUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateMeterDto** | [**UpdateMeterDto**](UpdateMeterDto.md) |  | 

### Return type

[**MeterResponseDto**](MeterResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

