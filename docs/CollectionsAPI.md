# \CollectionsAPI

All URIs are relative to *https://api.solifyn.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CollectionsAddProducts**](CollectionsAPI.md#CollectionsAddProducts) | **Post** /v1/collections/{id}/products | Add Products to Collection
[**CollectionsArchive**](CollectionsAPI.md#CollectionsArchive) | **Delete** /v1/collections/{id} | Archive Collection
[**CollectionsCreate**](CollectionsAPI.md#CollectionsCreate) | **Post** /v1/collections | Create Collection
[**CollectionsDeleteProduct**](CollectionsAPI.md#CollectionsDeleteProduct) | **Delete** /v1/collections/{id}/products/{productId} | Remove Product from Collection
[**CollectionsGet**](CollectionsAPI.md#CollectionsGet) | **Get** /v1/collections/{id} | Retrieve Collection
[**CollectionsList**](CollectionsAPI.md#CollectionsList) | **Get** /v1/collections | List Collections
[**CollectionsListArchived**](CollectionsAPI.md#CollectionsListArchived) | **Get** /v1/collections/archived | List Archived Collections
[**CollectionsUnarchive**](CollectionsAPI.md#CollectionsUnarchive) | **Post** /v1/collections/{id}/unarchive | Unarchive Collection
[**CollectionsUpdate**](CollectionsAPI.md#CollectionsUpdate) | **Patch** /v1/collections/{id} | Update Collection
[**CollectionsUpdateProduct**](CollectionsAPI.md#CollectionsUpdateProduct) | **Patch** /v1/collections/{id}/products/{productId} | Update Collection Product



## CollectionsAddProducts

> CollectionResponseDto CollectionsAddProducts(ctx, id).AddCollectionProductsDto(addCollectionProductsDto).Execute()

Add Products to Collection



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
	id := "col_123" // string | Collection ID
	addCollectionProductsDto := *openapiclient.NewAddCollectionProductsDto([]openapiclient.CollectionProductEntry{*openapiclient.NewCollectionProductEntry("prod_123", float32(1))}) // AddCollectionProductsDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsAddProducts(context.Background(), id).AddCollectionProductsDto(addCollectionProductsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsAddProducts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsAddProducts`: CollectionResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsAddProducts`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Collection ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsAddProductsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **addCollectionProductsDto** | [**AddCollectionProductsDto**](AddCollectionProductsDto.md) |  | 

### Return type

[**CollectionResponseDto**](CollectionResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsArchive

> CollectionArchivedResponseDto CollectionsArchive(ctx, id).Execute()

Archive Collection



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
	id := "col_123" // string | Collection ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsArchive(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsArchive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsArchive`: CollectionArchivedResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsArchive`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Collection ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsArchiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CollectionArchivedResponseDto**](CollectionArchivedResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsCreate

> CollectionResponseDto CollectionsCreate(ctx).CreateCollectionDto(createCollectionDto).Execute()

Create Collection



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
	createCollectionDto := *openapiclient.NewCreateCollectionDto("Winter Course Bundle", []openapiclient.CollectionProductEntry{*openapiclient.NewCollectionProductEntry("prod_123", float32(1))}) // CreateCollectionDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsCreate(context.Background()).CreateCollectionDto(createCollectionDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsCreate`: CollectionResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCollectionDto** | [**CreateCollectionDto**](CreateCollectionDto.md) |  | 

### Return type

[**CollectionResponseDto**](CollectionResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsDeleteProduct

> CollectionProductDeletedResponseDto CollectionsDeleteProduct(ctx, id, productId).Execute()

Remove Product from Collection



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
	id := "col_123" // string | Collection ID
	productId := "prod_123" // string | Product ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsDeleteProduct(context.Background(), id, productId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsDeleteProduct``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsDeleteProduct`: CollectionProductDeletedResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsDeleteProduct`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Collection ID | 
**productId** | **string** | Product ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsDeleteProductRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CollectionProductDeletedResponseDto**](CollectionProductDeletedResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsGet

> CollectionDetailResponseDto CollectionsGet(ctx, id).Execute()

Retrieve Collection



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
	id := "col_123" // string | Collection ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsGet`: CollectionDetailResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Collection ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CollectionDetailResponseDto**](CollectionDetailResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsList

> []CollectionResponseDto CollectionsList(ctx).Execute()

List Collections



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
	resp, r, err := apiClient.CollectionsAPI.CollectionsList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsList`: []CollectionResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsListRequest struct via the builder pattern


### Return type

[**[]CollectionResponseDto**](CollectionResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsListArchived

> []CollectionResponseDto CollectionsListArchived(ctx).Execute()

List Archived Collections



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
	resp, r, err := apiClient.CollectionsAPI.CollectionsListArchived(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsListArchived``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsListArchived`: []CollectionResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsListArchived`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsListArchivedRequest struct via the builder pattern


### Return type

[**[]CollectionResponseDto**](CollectionResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsUnarchive

> CollectionUnarchivedResponseDto CollectionsUnarchive(ctx, id).Execute()

Unarchive Collection



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
	id := "col_123" // string | Collection ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsUnarchive(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsUnarchive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsUnarchive`: CollectionUnarchivedResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsUnarchive`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Collection ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsUnarchiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CollectionUnarchivedResponseDto**](CollectionUnarchivedResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsUpdate

> CollectionUpdatedResponseDto CollectionsUpdate(ctx, id).UpdateCollectionDto(updateCollectionDto).Execute()

Update Collection



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
	id := "col_123" // string | Collection ID
	updateCollectionDto := *openapiclient.NewUpdateCollectionDto() // UpdateCollectionDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsUpdate(context.Background(), id).UpdateCollectionDto(updateCollectionDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsUpdate`: CollectionUpdatedResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Collection ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCollectionDto** | [**UpdateCollectionDto**](UpdateCollectionDto.md) |  | 

### Return type

[**CollectionUpdatedResponseDto**](CollectionUpdatedResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CollectionsUpdateProduct

> CollectionProductUpdatedResponseDto CollectionsUpdateProduct(ctx, id, productId).UpdateCollectionProductDto(updateCollectionProductDto).Execute()

Update Collection Product



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
	id := "col_123" // string | Collection ID
	productId := "prod_123" // string | Product ID
	updateCollectionProductDto := *openapiclient.NewUpdateCollectionProductDto(float32(2)) // UpdateCollectionProductDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsAPI.CollectionsUpdateProduct(context.Background(), id, productId).UpdateCollectionProductDto(updateCollectionProductDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsAPI.CollectionsUpdateProduct``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CollectionsUpdateProduct`: CollectionProductUpdatedResponseDto
	fmt.Fprintf(os.Stdout, "Response from `CollectionsAPI.CollectionsUpdateProduct`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Collection ID | 
**productId** | **string** | Product ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCollectionsUpdateProductRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateCollectionProductDto** | [**UpdateCollectionProductDto**](UpdateCollectionProductDto.md) |  | 

### Return type

[**CollectionProductUpdatedResponseDto**](CollectionProductUpdatedResponseDto.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

