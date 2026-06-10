# DiscountCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** | Unique discount code string (will be automatically capitalized). | 
**Name** | Pointer to **string** | Customer-facing name of the discount. | [optional] 
**Type** | **string** | Calculation type: percentage or fixed_amount. | 
**Amount** | **float32** | The discount value. If percentage, enter value like 10 for 10%. If fixed_amount, enter value like 10 for $10.00. | 
**UsageLimit** | Pointer to **NullableInt32** | Maximum number of redemptions allowed. | [optional] 
**ExpiresAt** | Pointer to **NullableTime** | Expiration timestamp for the discount. | [optional] 
**SubscriptionCycles** | Pointer to **NullableInt32** | Number of subscription cycles this discount applies to. | [optional] 
**RestrictedTo** | Pointer to **[]string** | List of product IDs this discount is restricted to. | [optional] 
**PreserveOnPlanChange** | Pointer to **bool** | Whether to preserve the discount when subscription plan changes. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Custom metadata for the discount. | [optional] 

## Methods

### NewDiscountCreate

`func NewDiscountCreate(code string, type_ string, amount float32, ) *DiscountCreate`

NewDiscountCreate instantiates a new DiscountCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiscountCreateWithDefaults

`func NewDiscountCreateWithDefaults() *DiscountCreate`

NewDiscountCreateWithDefaults instantiates a new DiscountCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *DiscountCreate) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *DiscountCreate) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *DiscountCreate) SetCode(v string)`

SetCode sets Code field to given value.


### GetName

`func (o *DiscountCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DiscountCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DiscountCreate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *DiscountCreate) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *DiscountCreate) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DiscountCreate) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DiscountCreate) SetType(v string)`

SetType sets Type field to given value.


### GetAmount

`func (o *DiscountCreate) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *DiscountCreate) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *DiscountCreate) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### GetUsageLimit

`func (o *DiscountCreate) GetUsageLimit() int32`

GetUsageLimit returns the UsageLimit field if non-nil, zero value otherwise.

### GetUsageLimitOk

`func (o *DiscountCreate) GetUsageLimitOk() (*int32, bool)`

GetUsageLimitOk returns a tuple with the UsageLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageLimit

`func (o *DiscountCreate) SetUsageLimit(v int32)`

SetUsageLimit sets UsageLimit field to given value.

### HasUsageLimit

`func (o *DiscountCreate) HasUsageLimit() bool`

HasUsageLimit returns a boolean if a field has been set.

### SetUsageLimitNil

`func (o *DiscountCreate) SetUsageLimitNil(b bool)`

 SetUsageLimitNil sets the value for UsageLimit to be an explicit nil

### UnsetUsageLimit
`func (o *DiscountCreate) UnsetUsageLimit()`

UnsetUsageLimit ensures that no value is present for UsageLimit, not even an explicit nil
### GetExpiresAt

`func (o *DiscountCreate) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *DiscountCreate) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *DiscountCreate) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *DiscountCreate) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *DiscountCreate) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *DiscountCreate) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetSubscriptionCycles

`func (o *DiscountCreate) GetSubscriptionCycles() int32`

GetSubscriptionCycles returns the SubscriptionCycles field if non-nil, zero value otherwise.

### GetSubscriptionCyclesOk

`func (o *DiscountCreate) GetSubscriptionCyclesOk() (*int32, bool)`

GetSubscriptionCyclesOk returns a tuple with the SubscriptionCycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionCycles

`func (o *DiscountCreate) SetSubscriptionCycles(v int32)`

SetSubscriptionCycles sets SubscriptionCycles field to given value.

### HasSubscriptionCycles

`func (o *DiscountCreate) HasSubscriptionCycles() bool`

HasSubscriptionCycles returns a boolean if a field has been set.

### SetSubscriptionCyclesNil

`func (o *DiscountCreate) SetSubscriptionCyclesNil(b bool)`

 SetSubscriptionCyclesNil sets the value for SubscriptionCycles to be an explicit nil

### UnsetSubscriptionCycles
`func (o *DiscountCreate) UnsetSubscriptionCycles()`

UnsetSubscriptionCycles ensures that no value is present for SubscriptionCycles, not even an explicit nil
### GetRestrictedTo

`func (o *DiscountCreate) GetRestrictedTo() []string`

GetRestrictedTo returns the RestrictedTo field if non-nil, zero value otherwise.

### GetRestrictedToOk

`func (o *DiscountCreate) GetRestrictedToOk() (*[]string, bool)`

GetRestrictedToOk returns a tuple with the RestrictedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestrictedTo

`func (o *DiscountCreate) SetRestrictedTo(v []string)`

SetRestrictedTo sets RestrictedTo field to given value.

### HasRestrictedTo

`func (o *DiscountCreate) HasRestrictedTo() bool`

HasRestrictedTo returns a boolean if a field has been set.

### GetPreserveOnPlanChange

`func (o *DiscountCreate) GetPreserveOnPlanChange() bool`

GetPreserveOnPlanChange returns the PreserveOnPlanChange field if non-nil, zero value otherwise.

### GetPreserveOnPlanChangeOk

`func (o *DiscountCreate) GetPreserveOnPlanChangeOk() (*bool, bool)`

GetPreserveOnPlanChangeOk returns a tuple with the PreserveOnPlanChange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveOnPlanChange

`func (o *DiscountCreate) SetPreserveOnPlanChange(v bool)`

SetPreserveOnPlanChange sets PreserveOnPlanChange field to given value.

### HasPreserveOnPlanChange

`func (o *DiscountCreate) HasPreserveOnPlanChange() bool`

HasPreserveOnPlanChange returns a boolean if a field has been set.

### GetMetadata

`func (o *DiscountCreate) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DiscountCreate) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DiscountCreate) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DiscountCreate) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


