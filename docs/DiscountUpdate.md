# DiscountUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Customer-facing name of the discount. | [optional] 
**Type** | Pointer to **string** | Calculation type: percentage or fixed_amount. | [optional] 
**Amount** | Pointer to **float32** | The discount value. | [optional] 
**UsageLimit** | Pointer to **int32** | Maximum number of redemptions allowed. | [optional] 
**ExpiresAt** | Pointer to **time.Time** | Expiration timestamp for the discount. | [optional] 
**SubscriptionCycles** | Pointer to **int32** | Number of subscription cycles this discount applies to. | [optional] 
**RestrictedTo** | Pointer to **[]string** | List of product IDs this discount is restricted to. | [optional] 
**PreserveOnPlanChange** | Pointer to **bool** | Whether to preserve the discount when subscription plan changes. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Custom metadata for the discount. | [optional] 

## Methods

### NewDiscountUpdate

`func NewDiscountUpdate() *DiscountUpdate`

NewDiscountUpdate instantiates a new DiscountUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiscountUpdateWithDefaults

`func NewDiscountUpdateWithDefaults() *DiscountUpdate`

NewDiscountUpdateWithDefaults instantiates a new DiscountUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *DiscountUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DiscountUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DiscountUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *DiscountUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *DiscountUpdate) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DiscountUpdate) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DiscountUpdate) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *DiscountUpdate) HasType() bool`

HasType returns a boolean if a field has been set.

### GetAmount

`func (o *DiscountUpdate) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *DiscountUpdate) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *DiscountUpdate) SetAmount(v float32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *DiscountUpdate) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetUsageLimit

`func (o *DiscountUpdate) GetUsageLimit() int32`

GetUsageLimit returns the UsageLimit field if non-nil, zero value otherwise.

### GetUsageLimitOk

`func (o *DiscountUpdate) GetUsageLimitOk() (*int32, bool)`

GetUsageLimitOk returns a tuple with the UsageLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageLimit

`func (o *DiscountUpdate) SetUsageLimit(v int32)`

SetUsageLimit sets UsageLimit field to given value.

### HasUsageLimit

`func (o *DiscountUpdate) HasUsageLimit() bool`

HasUsageLimit returns a boolean if a field has been set.

### GetExpiresAt

`func (o *DiscountUpdate) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *DiscountUpdate) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *DiscountUpdate) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *DiscountUpdate) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetSubscriptionCycles

`func (o *DiscountUpdate) GetSubscriptionCycles() int32`

GetSubscriptionCycles returns the SubscriptionCycles field if non-nil, zero value otherwise.

### GetSubscriptionCyclesOk

`func (o *DiscountUpdate) GetSubscriptionCyclesOk() (*int32, bool)`

GetSubscriptionCyclesOk returns a tuple with the SubscriptionCycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionCycles

`func (o *DiscountUpdate) SetSubscriptionCycles(v int32)`

SetSubscriptionCycles sets SubscriptionCycles field to given value.

### HasSubscriptionCycles

`func (o *DiscountUpdate) HasSubscriptionCycles() bool`

HasSubscriptionCycles returns a boolean if a field has been set.

### GetRestrictedTo

`func (o *DiscountUpdate) GetRestrictedTo() []string`

GetRestrictedTo returns the RestrictedTo field if non-nil, zero value otherwise.

### GetRestrictedToOk

`func (o *DiscountUpdate) GetRestrictedToOk() (*[]string, bool)`

GetRestrictedToOk returns a tuple with the RestrictedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestrictedTo

`func (o *DiscountUpdate) SetRestrictedTo(v []string)`

SetRestrictedTo sets RestrictedTo field to given value.

### HasRestrictedTo

`func (o *DiscountUpdate) HasRestrictedTo() bool`

HasRestrictedTo returns a boolean if a field has been set.

### GetPreserveOnPlanChange

`func (o *DiscountUpdate) GetPreserveOnPlanChange() bool`

GetPreserveOnPlanChange returns the PreserveOnPlanChange field if non-nil, zero value otherwise.

### GetPreserveOnPlanChangeOk

`func (o *DiscountUpdate) GetPreserveOnPlanChangeOk() (*bool, bool)`

GetPreserveOnPlanChangeOk returns a tuple with the PreserveOnPlanChange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveOnPlanChange

`func (o *DiscountUpdate) SetPreserveOnPlanChange(v bool)`

SetPreserveOnPlanChange sets PreserveOnPlanChange field to given value.

### HasPreserveOnPlanChange

`func (o *DiscountUpdate) HasPreserveOnPlanChange() bool`

HasPreserveOnPlanChange returns a boolean if a field has been set.

### GetMetadata

`func (o *DiscountUpdate) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DiscountUpdate) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DiscountUpdate) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DiscountUpdate) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


