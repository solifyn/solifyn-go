# ProductsList200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]Product**](Product.md) |  | 
**Pagination** | [**ProductsList200ResponsePagination**](ProductsList200ResponsePagination.md) |  | 

## Methods

### NewProductsList200Response

`func NewProductsList200Response(items []Product, pagination ProductsList200ResponsePagination, ) *ProductsList200Response`

NewProductsList200Response instantiates a new ProductsList200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductsList200ResponseWithDefaults

`func NewProductsList200ResponseWithDefaults() *ProductsList200Response`

NewProductsList200ResponseWithDefaults instantiates a new ProductsList200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *ProductsList200Response) GetItems() []Product`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ProductsList200Response) GetItemsOk() (*[]Product, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ProductsList200Response) SetItems(v []Product)`

SetItems sets Items field to given value.


### GetPagination

`func (o *ProductsList200Response) GetPagination() ProductsList200ResponsePagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *ProductsList200Response) GetPaginationOk() (*ProductsList200ResponsePagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *ProductsList200Response) SetPagination(v ProductsList200ResponsePagination)`

SetPagination sets Pagination field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


