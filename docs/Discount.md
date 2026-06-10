# Discount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique prefix-based identifier of the discount (e.g., &#x60;disc_cs8f67sd7f6fw3fs&#x60;). | 
**DiscountId** | **string** | Alias for the unique identifier of the discount. | 
**Code** | **string** | The unique discount code (e.g. SAVE10) used during checkout. | 
**Name** | Pointer to **string** | The customer-facing name of the discount code (e.g. Summer Sale). | [optional] 
**Type** | **string** | The discount calculation type: percentage or fixed_amount. | 
**Amount** | **int32** | The discount value. For percentage type, it is in basis points (e.g. 1000 &#x3D; 10.00%). For fixed_amount type, it is in cents (e.g. 1000 &#x3D; $10.00). | 
**UsageLimit** | **NullableInt32** | Maximum number of times this discount code can be redeemed. Null represents unlimited usage. | 
**TimesUsed** | **int32** | The number of times this discount code has been successfully redeemed. | 
**ExpiresAt** | **NullableTime** | The expiration timestamp after which the discount code is no longer valid. | 
**Status** | **string** | The current status of the discount. | 
**BusinessId** | **string** | The unique identifier associated with the business this discount belongs to. | 
**CreatedAt** | **time.Time** | Timestamp indicating exactly when the discount was created. | 
**UpdatedAt** | **time.Time** | Timestamp indicating when the discount was last updated. | 

## Methods

### NewDiscount

`func NewDiscount(id string, discountId string, code string, type_ string, amount int32, usageLimit NullableInt32, timesUsed int32, expiresAt NullableTime, status string, businessId string, createdAt time.Time, updatedAt time.Time, ) *Discount`

NewDiscount instantiates a new Discount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiscountWithDefaults

`func NewDiscountWithDefaults() *Discount`

NewDiscountWithDefaults instantiates a new Discount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Discount) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Discount) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Discount) SetId(v string)`

SetId sets Id field to given value.


### GetDiscountId

`func (o *Discount) GetDiscountId() string`

GetDiscountId returns the DiscountId field if non-nil, zero value otherwise.

### GetDiscountIdOk

`func (o *Discount) GetDiscountIdOk() (*string, bool)`

GetDiscountIdOk returns a tuple with the DiscountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountId

`func (o *Discount) SetDiscountId(v string)`

SetDiscountId sets DiscountId field to given value.


### GetCode

`func (o *Discount) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *Discount) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *Discount) SetCode(v string)`

SetCode sets Code field to given value.


### GetName

`func (o *Discount) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Discount) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Discount) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Discount) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *Discount) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Discount) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Discount) SetType(v string)`

SetType sets Type field to given value.


### GetAmount

`func (o *Discount) GetAmount() int32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *Discount) GetAmountOk() (*int32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *Discount) SetAmount(v int32)`

SetAmount sets Amount field to given value.


### GetUsageLimit

`func (o *Discount) GetUsageLimit() int32`

GetUsageLimit returns the UsageLimit field if non-nil, zero value otherwise.

### GetUsageLimitOk

`func (o *Discount) GetUsageLimitOk() (*int32, bool)`

GetUsageLimitOk returns a tuple with the UsageLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageLimit

`func (o *Discount) SetUsageLimit(v int32)`

SetUsageLimit sets UsageLimit field to given value.


### SetUsageLimitNil

`func (o *Discount) SetUsageLimitNil(b bool)`

 SetUsageLimitNil sets the value for UsageLimit to be an explicit nil

### UnsetUsageLimit
`func (o *Discount) UnsetUsageLimit()`

UnsetUsageLimit ensures that no value is present for UsageLimit, not even an explicit nil
### GetTimesUsed

`func (o *Discount) GetTimesUsed() int32`

GetTimesUsed returns the TimesUsed field if non-nil, zero value otherwise.

### GetTimesUsedOk

`func (o *Discount) GetTimesUsedOk() (*int32, bool)`

GetTimesUsedOk returns a tuple with the TimesUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimesUsed

`func (o *Discount) SetTimesUsed(v int32)`

SetTimesUsed sets TimesUsed field to given value.


### GetExpiresAt

`func (o *Discount) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *Discount) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *Discount) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### SetExpiresAtNil

`func (o *Discount) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *Discount) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetStatus

`func (o *Discount) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Discount) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Discount) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetBusinessId

`func (o *Discount) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *Discount) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *Discount) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetCreatedAt

`func (o *Discount) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Discount) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Discount) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Discount) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Discount) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Discount) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


