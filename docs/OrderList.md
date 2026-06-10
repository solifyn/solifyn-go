# OrderList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]Order**](Order.md) | List of order items. | 
**TotalCount** | **int32** | Total number of items matching filters. | 

## Methods

### NewOrderList

`func NewOrderList(items []Order, totalCount int32, ) *OrderList`

NewOrderList instantiates a new OrderList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderListWithDefaults

`func NewOrderListWithDefaults() *OrderList`

NewOrderListWithDefaults instantiates a new OrderList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *OrderList) GetItems() []Order`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *OrderList) GetItemsOk() (*[]Order, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *OrderList) SetItems(v []Order)`

SetItems sets Items field to given value.


### GetTotalCount

`func (o *OrderList) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *OrderList) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *OrderList) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


