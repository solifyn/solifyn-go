# AddonUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MinQuantity** | Pointer to **float32** | Minimum quantity of the addon allowed to be purchased. | [optional] 
**MaxQuantity** | Pointer to **float32** | Maximum quantity of the addon allowed to be purchased (optional). | [optional] 
**PriceOverride** | Pointer to **float32** | Price override for the addon product when purchased with this parent (optional). | [optional] 
**IsSeatAddon** | Pointer to **bool** | Flag indicating if this addon represents a seat/license limit increment. | [optional] 

## Methods

### NewAddonUpdate

`func NewAddonUpdate() *AddonUpdate`

NewAddonUpdate instantiates a new AddonUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddonUpdateWithDefaults

`func NewAddonUpdateWithDefaults() *AddonUpdate`

NewAddonUpdateWithDefaults instantiates a new AddonUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMinQuantity

`func (o *AddonUpdate) GetMinQuantity() float32`

GetMinQuantity returns the MinQuantity field if non-nil, zero value otherwise.

### GetMinQuantityOk

`func (o *AddonUpdate) GetMinQuantityOk() (*float32, bool)`

GetMinQuantityOk returns a tuple with the MinQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinQuantity

`func (o *AddonUpdate) SetMinQuantity(v float32)`

SetMinQuantity sets MinQuantity field to given value.

### HasMinQuantity

`func (o *AddonUpdate) HasMinQuantity() bool`

HasMinQuantity returns a boolean if a field has been set.

### GetMaxQuantity

`func (o *AddonUpdate) GetMaxQuantity() float32`

GetMaxQuantity returns the MaxQuantity field if non-nil, zero value otherwise.

### GetMaxQuantityOk

`func (o *AddonUpdate) GetMaxQuantityOk() (*float32, bool)`

GetMaxQuantityOk returns a tuple with the MaxQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxQuantity

`func (o *AddonUpdate) SetMaxQuantity(v float32)`

SetMaxQuantity sets MaxQuantity field to given value.

### HasMaxQuantity

`func (o *AddonUpdate) HasMaxQuantity() bool`

HasMaxQuantity returns a boolean if a field has been set.

### GetPriceOverride

`func (o *AddonUpdate) GetPriceOverride() float32`

GetPriceOverride returns the PriceOverride field if non-nil, zero value otherwise.

### GetPriceOverrideOk

`func (o *AddonUpdate) GetPriceOverrideOk() (*float32, bool)`

GetPriceOverrideOk returns a tuple with the PriceOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceOverride

`func (o *AddonUpdate) SetPriceOverride(v float32)`

SetPriceOverride sets PriceOverride field to given value.

### HasPriceOverride

`func (o *AddonUpdate) HasPriceOverride() bool`

HasPriceOverride returns a boolean if a field has been set.

### GetIsSeatAddon

`func (o *AddonUpdate) GetIsSeatAddon() bool`

GetIsSeatAddon returns the IsSeatAddon field if non-nil, zero value otherwise.

### GetIsSeatAddonOk

`func (o *AddonUpdate) GetIsSeatAddonOk() (*bool, bool)`

GetIsSeatAddonOk returns a tuple with the IsSeatAddon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSeatAddon

`func (o *AddonUpdate) SetIsSeatAddon(v bool)`

SetIsSeatAddon sets IsSeatAddon field to given value.

### HasIsSeatAddon

`func (o *AddonUpdate) HasIsSeatAddon() bool`

HasIsSeatAddon returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


