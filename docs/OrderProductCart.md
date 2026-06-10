# OrderProductCart

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Product identifier. | 
**Name** | **string** | Product name. | 
**Quantity** | **int32** | Quantity purchased. | 
**Price** | **int32** | Price per item in cents. | 
**PricingType** | Pointer to **string** | Pricing type, e.g. one-time or renewal. | [optional] 

## Methods

### NewOrderProductCart

`func NewOrderProductCart(id string, name string, quantity int32, price int32, ) *OrderProductCart`

NewOrderProductCart instantiates a new OrderProductCart object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderProductCartWithDefaults

`func NewOrderProductCartWithDefaults() *OrderProductCart`

NewOrderProductCartWithDefaults instantiates a new OrderProductCart object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OrderProductCart) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OrderProductCart) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OrderProductCart) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *OrderProductCart) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OrderProductCart) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OrderProductCart) SetName(v string)`

SetName sets Name field to given value.


### GetQuantity

`func (o *OrderProductCart) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *OrderProductCart) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *OrderProductCart) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.


### GetPrice

`func (o *OrderProductCart) GetPrice() int32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *OrderProductCart) GetPriceOk() (*int32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *OrderProductCart) SetPrice(v int32)`

SetPrice sets Price field to given value.


### GetPricingType

`func (o *OrderProductCart) GetPricingType() string`

GetPricingType returns the PricingType field if non-nil, zero value otherwise.

### GetPricingTypeOk

`func (o *OrderProductCart) GetPricingTypeOk() (*string, bool)`

GetPricingTypeOk returns a tuple with the PricingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingType

`func (o *OrderProductCart) SetPricingType(v string)`

SetPricingType sets PricingType field to given value.

### HasPricingType

`func (o *OrderProductCart) HasPricingType() bool`

HasPricingType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


