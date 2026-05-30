# SubscriptionSeatAdjustment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Indicates if the seat adjustment was successful | 
**SubscriptionId** | **string** | The customer subscription ID | 
**AddonProductId** | **string** | The unique ID of the addon product | 
**OldQuantity** | **float32** | The previous seat quantity | 
**NewQuantity** | **float32** | The new seat quantity after adjustment | 
**QuantityDelta** | **float32** | The difference in seat quantity | 
**ProrationType** | **string** | The proration strategy type applied | 
**CostImpact** | **float32** | Calculated pro-rata price cost impact in currency unit (charged or credited) | 
**Currency** | **string** | Billing currency | 

## Methods

### NewSubscriptionSeatAdjustment

`func NewSubscriptionSeatAdjustment(success bool, subscriptionId string, addonProductId string, oldQuantity float32, newQuantity float32, quantityDelta float32, prorationType string, costImpact float32, currency string, ) *SubscriptionSeatAdjustment`

NewSubscriptionSeatAdjustment instantiates a new SubscriptionSeatAdjustment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionSeatAdjustmentWithDefaults

`func NewSubscriptionSeatAdjustmentWithDefaults() *SubscriptionSeatAdjustment`

NewSubscriptionSeatAdjustmentWithDefaults instantiates a new SubscriptionSeatAdjustment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *SubscriptionSeatAdjustment) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *SubscriptionSeatAdjustment) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *SubscriptionSeatAdjustment) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetSubscriptionId

`func (o *SubscriptionSeatAdjustment) GetSubscriptionId() string`

GetSubscriptionId returns the SubscriptionId field if non-nil, zero value otherwise.

### GetSubscriptionIdOk

`func (o *SubscriptionSeatAdjustment) GetSubscriptionIdOk() (*string, bool)`

GetSubscriptionIdOk returns a tuple with the SubscriptionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionId

`func (o *SubscriptionSeatAdjustment) SetSubscriptionId(v string)`

SetSubscriptionId sets SubscriptionId field to given value.


### GetAddonProductId

`func (o *SubscriptionSeatAdjustment) GetAddonProductId() string`

GetAddonProductId returns the AddonProductId field if non-nil, zero value otherwise.

### GetAddonProductIdOk

`func (o *SubscriptionSeatAdjustment) GetAddonProductIdOk() (*string, bool)`

GetAddonProductIdOk returns a tuple with the AddonProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddonProductId

`func (o *SubscriptionSeatAdjustment) SetAddonProductId(v string)`

SetAddonProductId sets AddonProductId field to given value.


### GetOldQuantity

`func (o *SubscriptionSeatAdjustment) GetOldQuantity() float32`

GetOldQuantity returns the OldQuantity field if non-nil, zero value otherwise.

### GetOldQuantityOk

`func (o *SubscriptionSeatAdjustment) GetOldQuantityOk() (*float32, bool)`

GetOldQuantityOk returns a tuple with the OldQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldQuantity

`func (o *SubscriptionSeatAdjustment) SetOldQuantity(v float32)`

SetOldQuantity sets OldQuantity field to given value.


### GetNewQuantity

`func (o *SubscriptionSeatAdjustment) GetNewQuantity() float32`

GetNewQuantity returns the NewQuantity field if non-nil, zero value otherwise.

### GetNewQuantityOk

`func (o *SubscriptionSeatAdjustment) GetNewQuantityOk() (*float32, bool)`

GetNewQuantityOk returns a tuple with the NewQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewQuantity

`func (o *SubscriptionSeatAdjustment) SetNewQuantity(v float32)`

SetNewQuantity sets NewQuantity field to given value.


### GetQuantityDelta

`func (o *SubscriptionSeatAdjustment) GetQuantityDelta() float32`

GetQuantityDelta returns the QuantityDelta field if non-nil, zero value otherwise.

### GetQuantityDeltaOk

`func (o *SubscriptionSeatAdjustment) GetQuantityDeltaOk() (*float32, bool)`

GetQuantityDeltaOk returns a tuple with the QuantityDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityDelta

`func (o *SubscriptionSeatAdjustment) SetQuantityDelta(v float32)`

SetQuantityDelta sets QuantityDelta field to given value.


### GetProrationType

`func (o *SubscriptionSeatAdjustment) GetProrationType() string`

GetProrationType returns the ProrationType field if non-nil, zero value otherwise.

### GetProrationTypeOk

`func (o *SubscriptionSeatAdjustment) GetProrationTypeOk() (*string, bool)`

GetProrationTypeOk returns a tuple with the ProrationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProrationType

`func (o *SubscriptionSeatAdjustment) SetProrationType(v string)`

SetProrationType sets ProrationType field to given value.


### GetCostImpact

`func (o *SubscriptionSeatAdjustment) GetCostImpact() float32`

GetCostImpact returns the CostImpact field if non-nil, zero value otherwise.

### GetCostImpactOk

`func (o *SubscriptionSeatAdjustment) GetCostImpactOk() (*float32, bool)`

GetCostImpactOk returns a tuple with the CostImpact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostImpact

`func (o *SubscriptionSeatAdjustment) SetCostImpact(v float32)`

SetCostImpact sets CostImpact field to given value.


### GetCurrency

`func (o *SubscriptionSeatAdjustment) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SubscriptionSeatAdjustment) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SubscriptionSeatAdjustment) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


