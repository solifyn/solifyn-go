# RevokeSeatDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductId** | **string** | The product ID of the addon (Whop Product ID or local ID). | 
**Quantity** | **int32** | The number of seats to revoke/deduct. | 

## Methods

### NewRevokeSeatDto

`func NewRevokeSeatDto(productId string, quantity int32, ) *RevokeSeatDto`

NewRevokeSeatDto instantiates a new RevokeSeatDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRevokeSeatDtoWithDefaults

`func NewRevokeSeatDtoWithDefaults() *RevokeSeatDto`

NewRevokeSeatDtoWithDefaults instantiates a new RevokeSeatDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductId

`func (o *RevokeSeatDto) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *RevokeSeatDto) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *RevokeSeatDto) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetQuantity

`func (o *RevokeSeatDto) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *RevokeSeatDto) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *RevokeSeatDto) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


