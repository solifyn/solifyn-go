# Refund

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The refund ID | 
**WhopId** | **string** | The Whop Refund ID | 
**IdempotencyKey** | Pointer to **NullableString** | Client-generated key to prevent duplicate refunds | [optional] 
**Amount** | **float32** | Refunded amount | 
**Currency** | **string** | Currency code | 
**Status** | **string** | Status of the refund | 
**Provider** | Pointer to **NullableString** | The payment provider used | [optional] 
**Reason** | Pointer to **NullableString** | Reason for the refund | [optional] 
**ReferenceValue** | Pointer to **NullableString** | Acquirer Reference Number (ARN) or tracking number | [optional] 
**PaymentId** | **string** | The associated Payment ID | 
**ProviderCreatedAt** | Pointer to **NullableTime** | Timestamp when the refund was processed by the provider | [optional] 
**CreatedAt** | **time.Time** | Timestamp when the refund was created in our system | 
**UpdatedAt** | **time.Time** | Timestamp when the refund was last updated | 

## Methods

### NewRefund

`func NewRefund(id string, whopId string, amount float32, currency string, status string, paymentId string, createdAt time.Time, updatedAt time.Time, ) *Refund`

NewRefund instantiates a new Refund object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRefundWithDefaults

`func NewRefundWithDefaults() *Refund`

NewRefundWithDefaults instantiates a new Refund object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Refund) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Refund) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Refund) SetId(v string)`

SetId sets Id field to given value.


### GetWhopId

`func (o *Refund) GetWhopId() string`

GetWhopId returns the WhopId field if non-nil, zero value otherwise.

### GetWhopIdOk

`func (o *Refund) GetWhopIdOk() (*string, bool)`

GetWhopIdOk returns a tuple with the WhopId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhopId

`func (o *Refund) SetWhopId(v string)`

SetWhopId sets WhopId field to given value.


### GetIdempotencyKey

`func (o *Refund) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *Refund) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *Refund) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.

### HasIdempotencyKey

`func (o *Refund) HasIdempotencyKey() bool`

HasIdempotencyKey returns a boolean if a field has been set.

### SetIdempotencyKeyNil

`func (o *Refund) SetIdempotencyKeyNil(b bool)`

 SetIdempotencyKeyNil sets the value for IdempotencyKey to be an explicit nil

### UnsetIdempotencyKey
`func (o *Refund) UnsetIdempotencyKey()`

UnsetIdempotencyKey ensures that no value is present for IdempotencyKey, not even an explicit nil
### GetAmount

`func (o *Refund) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *Refund) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *Refund) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### GetCurrency

`func (o *Refund) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Refund) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Refund) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetStatus

`func (o *Refund) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Refund) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Refund) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetProvider

`func (o *Refund) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *Refund) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *Refund) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *Refund) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *Refund) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *Refund) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetReason

`func (o *Refund) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *Refund) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *Refund) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *Refund) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *Refund) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *Refund) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetReferenceValue

`func (o *Refund) GetReferenceValue() string`

GetReferenceValue returns the ReferenceValue field if non-nil, zero value otherwise.

### GetReferenceValueOk

`func (o *Refund) GetReferenceValueOk() (*string, bool)`

GetReferenceValueOk returns a tuple with the ReferenceValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceValue

`func (o *Refund) SetReferenceValue(v string)`

SetReferenceValue sets ReferenceValue field to given value.

### HasReferenceValue

`func (o *Refund) HasReferenceValue() bool`

HasReferenceValue returns a boolean if a field has been set.

### SetReferenceValueNil

`func (o *Refund) SetReferenceValueNil(b bool)`

 SetReferenceValueNil sets the value for ReferenceValue to be an explicit nil

### UnsetReferenceValue
`func (o *Refund) UnsetReferenceValue()`

UnsetReferenceValue ensures that no value is present for ReferenceValue, not even an explicit nil
### GetPaymentId

`func (o *Refund) GetPaymentId() string`

GetPaymentId returns the PaymentId field if non-nil, zero value otherwise.

### GetPaymentIdOk

`func (o *Refund) GetPaymentIdOk() (*string, bool)`

GetPaymentIdOk returns a tuple with the PaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentId

`func (o *Refund) SetPaymentId(v string)`

SetPaymentId sets PaymentId field to given value.


### GetProviderCreatedAt

`func (o *Refund) GetProviderCreatedAt() time.Time`

GetProviderCreatedAt returns the ProviderCreatedAt field if non-nil, zero value otherwise.

### GetProviderCreatedAtOk

`func (o *Refund) GetProviderCreatedAtOk() (*time.Time, bool)`

GetProviderCreatedAtOk returns a tuple with the ProviderCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderCreatedAt

`func (o *Refund) SetProviderCreatedAt(v time.Time)`

SetProviderCreatedAt sets ProviderCreatedAt field to given value.

### HasProviderCreatedAt

`func (o *Refund) HasProviderCreatedAt() bool`

HasProviderCreatedAt returns a boolean if a field has been set.

### SetProviderCreatedAtNil

`func (o *Refund) SetProviderCreatedAtNil(b bool)`

 SetProviderCreatedAtNil sets the value for ProviderCreatedAt to be an explicit nil

### UnsetProviderCreatedAt
`func (o *Refund) UnsetProviderCreatedAt()`

UnsetProviderCreatedAt ensures that no value is present for ProviderCreatedAt, not even an explicit nil
### GetCreatedAt

`func (o *Refund) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Refund) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Refund) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Refund) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Refund) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Refund) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


