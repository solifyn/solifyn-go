# DiscountsList200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]Discount**](Discount.md) |  | 
**Total** | **int32** | Total number of items matching filters. | 
**TotalCount** | **int32** | Total number of items matching filters (alias). | 
**Pagination** | [**DiscountsList200ResponsePagination**](DiscountsList200ResponsePagination.md) |  | 

## Methods

### NewDiscountsList200Response

`func NewDiscountsList200Response(items []Discount, total int32, totalCount int32, pagination DiscountsList200ResponsePagination, ) *DiscountsList200Response`

NewDiscountsList200Response instantiates a new DiscountsList200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiscountsList200ResponseWithDefaults

`func NewDiscountsList200ResponseWithDefaults() *DiscountsList200Response`

NewDiscountsList200ResponseWithDefaults instantiates a new DiscountsList200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *DiscountsList200Response) GetItems() []Discount`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *DiscountsList200Response) GetItemsOk() (*[]Discount, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *DiscountsList200Response) SetItems(v []Discount)`

SetItems sets Items field to given value.


### GetTotal

`func (o *DiscountsList200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *DiscountsList200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *DiscountsList200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetTotalCount

`func (o *DiscountsList200Response) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *DiscountsList200Response) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *DiscountsList200Response) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.


### GetPagination

`func (o *DiscountsList200Response) GetPagination() DiscountsList200ResponsePagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *DiscountsList200Response) GetPaginationOk() (*DiscountsList200ResponsePagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *DiscountsList200Response) SetPagination(v DiscountsList200ResponsePagination)`

SetPagination sets Pagination field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


