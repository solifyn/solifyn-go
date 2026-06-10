# AddonCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductId** | **string** | The product ID of the addon product. | 
**MinQuantity** | **float32** | Minimum quantity of the addon allowed to be purchased. | [default to 0]
**MaxQuantity** | Pointer to **float32** | Maximum quantity of the addon allowed to be purchased (optional). | [optional] 
**PriceOverride** | Pointer to **float32** | Price override for the addon product when purchased with this parent (optional). | [optional] 
**IsSeatAddon** | **bool** | Flag indicating if this addon represents a seat/license limit increment. | [default to false]

## Methods

### NewAddonCreate

`func NewAddonCreate(productId string, minQuantity float32, isSeatAddon bool, ) *AddonCreate`

NewAddonCreate instantiates a new AddonCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddonCreateWithDefaults

`func NewAddonCreateWithDefaults() *AddonCreate`

NewAddonCreateWithDefaults instantiates a new AddonCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductId

`func (o *AddonCreate) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *AddonCreate) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *AddonCreate) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetMinQuantity

`func (o *AddonCreate) GetMinQuantity() float32`

GetMinQuantity returns the MinQuantity field if non-nil, zero value otherwise.

### GetMinQuantityOk

`func (o *AddonCreate) GetMinQuantityOk() (*float32, bool)`

GetMinQuantityOk returns a tuple with the MinQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinQuantity

`func (o *AddonCreate) SetMinQuantity(v float32)`

SetMinQuantity sets MinQuantity field to given value.


### GetMaxQuantity

`func (o *AddonCreate) GetMaxQuantity() float32`

GetMaxQuantity returns the MaxQuantity field if non-nil, zero value otherwise.

### GetMaxQuantityOk

`func (o *AddonCreate) GetMaxQuantityOk() (*float32, bool)`

GetMaxQuantityOk returns a tuple with the MaxQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxQuantity

`func (o *AddonCreate) SetMaxQuantity(v float32)`

SetMaxQuantity sets MaxQuantity field to given value.

### HasMaxQuantity

`func (o *AddonCreate) HasMaxQuantity() bool`

HasMaxQuantity returns a boolean if a field has been set.

### GetPriceOverride

`func (o *AddonCreate) GetPriceOverride() float32`

GetPriceOverride returns the PriceOverride field if non-nil, zero value otherwise.

### GetPriceOverrideOk

`func (o *AddonCreate) GetPriceOverrideOk() (*float32, bool)`

GetPriceOverrideOk returns a tuple with the PriceOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceOverride

`func (o *AddonCreate) SetPriceOverride(v float32)`

SetPriceOverride sets PriceOverride field to given value.

### HasPriceOverride

`func (o *AddonCreate) HasPriceOverride() bool`

HasPriceOverride returns a boolean if a field has been set.

### GetIsSeatAddon

`func (o *AddonCreate) GetIsSeatAddon() bool`

GetIsSeatAddon returns the IsSeatAddon field if non-nil, zero value otherwise.

### GetIsSeatAddonOk

`func (o *AddonCreate) GetIsSeatAddonOk() (*bool, bool)`

GetIsSeatAddonOk returns a tuple with the IsSeatAddon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSeatAddon

`func (o *AddonCreate) SetIsSeatAddon(v bool)`

SetIsSeatAddon sets IsSeatAddon field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


