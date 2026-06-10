# ResolvedAddon

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductId** | **string** | Unique product ID of the addon | 
**Name** | **string** | Display name of the addon | 
**ImageUrl** | **map[string]interface{}** | URL of the addon image | 
**Quantity** | **float32** | The purchased quantity of the addon | 

## Methods

### NewResolvedAddon

`func NewResolvedAddon(productId string, name string, imageUrl map[string]interface{}, quantity float32, ) *ResolvedAddon`

NewResolvedAddon instantiates a new ResolvedAddon object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResolvedAddonWithDefaults

`func NewResolvedAddonWithDefaults() *ResolvedAddon`

NewResolvedAddonWithDefaults instantiates a new ResolvedAddon object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductId

`func (o *ResolvedAddon) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ResolvedAddon) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ResolvedAddon) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetName

`func (o *ResolvedAddon) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ResolvedAddon) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ResolvedAddon) SetName(v string)`

SetName sets Name field to given value.


### GetImageUrl

`func (o *ResolvedAddon) GetImageUrl() map[string]interface{}`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *ResolvedAddon) GetImageUrlOk() (*map[string]interface{}, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *ResolvedAddon) SetImageUrl(v map[string]interface{})`

SetImageUrl sets ImageUrl field to given value.


### SetImageUrlNil

`func (o *ResolvedAddon) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *ResolvedAddon) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetQuantity

`func (o *ResolvedAddon) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ResolvedAddon) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ResolvedAddon) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


