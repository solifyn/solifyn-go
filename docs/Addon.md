# Addon

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductId** | **string** | The product ID of the addon product. | 
**MinQuantity** | **float32** | Minimum quantity allowed. | 
**MaxQuantity** | **map[string]interface{}** | Maximum quantity allowed (null if unlimited). | 
**PriceOverride** | **map[string]interface{}** | Price override (null if using base product price). | 
**IsSeatAddon** | **bool** | Flag indicating if this is a seat/license addon. | 

## Methods

### NewAddon

`func NewAddon(productId string, minQuantity float32, maxQuantity map[string]interface{}, priceOverride map[string]interface{}, isSeatAddon bool, ) *Addon`

NewAddon instantiates a new Addon object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddonWithDefaults

`func NewAddonWithDefaults() *Addon`

NewAddonWithDefaults instantiates a new Addon object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductId

`func (o *Addon) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *Addon) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *Addon) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetMinQuantity

`func (o *Addon) GetMinQuantity() float32`

GetMinQuantity returns the MinQuantity field if non-nil, zero value otherwise.

### GetMinQuantityOk

`func (o *Addon) GetMinQuantityOk() (*float32, bool)`

GetMinQuantityOk returns a tuple with the MinQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinQuantity

`func (o *Addon) SetMinQuantity(v float32)`

SetMinQuantity sets MinQuantity field to given value.


### GetMaxQuantity

`func (o *Addon) GetMaxQuantity() map[string]interface{}`

GetMaxQuantity returns the MaxQuantity field if non-nil, zero value otherwise.

### GetMaxQuantityOk

`func (o *Addon) GetMaxQuantityOk() (*map[string]interface{}, bool)`

GetMaxQuantityOk returns a tuple with the MaxQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxQuantity

`func (o *Addon) SetMaxQuantity(v map[string]interface{})`

SetMaxQuantity sets MaxQuantity field to given value.


### GetPriceOverride

`func (o *Addon) GetPriceOverride() map[string]interface{}`

GetPriceOverride returns the PriceOverride field if non-nil, zero value otherwise.

### GetPriceOverrideOk

`func (o *Addon) GetPriceOverrideOk() (*map[string]interface{}, bool)`

GetPriceOverrideOk returns a tuple with the PriceOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceOverride

`func (o *Addon) SetPriceOverride(v map[string]interface{})`

SetPriceOverride sets PriceOverride field to given value.


### GetIsSeatAddon

`func (o *Addon) GetIsSeatAddon() bool`

GetIsSeatAddon returns the IsSeatAddon field if non-nil, zero value otherwise.

### GetIsSeatAddonOk

`func (o *Addon) GetIsSeatAddonOk() (*bool, bool)`

GetIsSeatAddonOk returns a tuple with the IsSeatAddon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSeatAddon

`func (o *Addon) SetIsSeatAddon(v bool)`

SetIsSeatAddon sets IsSeatAddon field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


