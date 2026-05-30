# CustomerListResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]CustomerResponseDto**](CustomerResponseDto.md) | List of customers | 
**TotalCount** | **float32** | Total count of customers matching the filters | 

## Methods

### NewCustomerListResponseDto

`func NewCustomerListResponseDto(items []CustomerResponseDto, totalCount float32, ) *CustomerListResponseDto`

NewCustomerListResponseDto instantiates a new CustomerListResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerListResponseDtoWithDefaults

`func NewCustomerListResponseDtoWithDefaults() *CustomerListResponseDto`

NewCustomerListResponseDtoWithDefaults instantiates a new CustomerListResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *CustomerListResponseDto) GetItems() []CustomerResponseDto`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *CustomerListResponseDto) GetItemsOk() (*[]CustomerResponseDto, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *CustomerListResponseDto) SetItems(v []CustomerResponseDto)`

SetItems sets Items field to given value.


### GetTotalCount

`func (o *CustomerListResponseDto) GetTotalCount() float32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *CustomerListResponseDto) GetTotalCountOk() (*float32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *CustomerListResponseDto) SetTotalCount(v float32)`

SetTotalCount sets TotalCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


