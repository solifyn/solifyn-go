# SubscriptionDetailProduct

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The product unique ID | 
**Name** | **string** | The product name | 
**Price** | **float32** | Product base price | 
**Currency** | **string** | Base currency | 
**Metadata** | Pointer to **map[string]interface{}** | Metadata JSON payload | [optional] 
**PricingType** | **string** | Pricing type, e.g. one-time or renewal | 

## Methods

### NewSubscriptionDetailProduct

`func NewSubscriptionDetailProduct(id string, name string, price float32, currency string, pricingType string, ) *SubscriptionDetailProduct`

NewSubscriptionDetailProduct instantiates a new SubscriptionDetailProduct object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionDetailProductWithDefaults

`func NewSubscriptionDetailProductWithDefaults() *SubscriptionDetailProduct`

NewSubscriptionDetailProductWithDefaults instantiates a new SubscriptionDetailProduct object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SubscriptionDetailProduct) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SubscriptionDetailProduct) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SubscriptionDetailProduct) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *SubscriptionDetailProduct) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SubscriptionDetailProduct) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SubscriptionDetailProduct) SetName(v string)`

SetName sets Name field to given value.


### GetPrice

`func (o *SubscriptionDetailProduct) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *SubscriptionDetailProduct) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *SubscriptionDetailProduct) SetPrice(v float32)`

SetPrice sets Price field to given value.


### GetCurrency

`func (o *SubscriptionDetailProduct) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SubscriptionDetailProduct) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SubscriptionDetailProduct) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetMetadata

`func (o *SubscriptionDetailProduct) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *SubscriptionDetailProduct) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *SubscriptionDetailProduct) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *SubscriptionDetailProduct) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetPricingType

`func (o *SubscriptionDetailProduct) GetPricingType() string`

GetPricingType returns the PricingType field if non-nil, zero value otherwise.

### GetPricingTypeOk

`func (o *SubscriptionDetailProduct) GetPricingTypeOk() (*string, bool)`

GetPricingTypeOk returns a tuple with the PricingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingType

`func (o *SubscriptionDetailProduct) SetPricingType(v string)`

SetPricingType sets PricingType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


