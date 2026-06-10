# WebhookRefundPayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Internal refund ID. | [optional] 
**PaymentId** | Pointer to **string** |  | [optional] 
**Amount** | Pointer to **string** | Dollar value, 2 d.p. | [optional] 
**Currency** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Reason** | Pointer to **NullableString** |  | [optional] 
**ReferenceValue** | Pointer to **NullableString** |  | [optional] 
**Provider** | Pointer to **NullableString** |  | [optional] 
**ProviderCreatedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewWebhookRefundPayload

`func NewWebhookRefundPayload() *WebhookRefundPayload`

NewWebhookRefundPayload instantiates a new WebhookRefundPayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookRefundPayloadWithDefaults

`func NewWebhookRefundPayloadWithDefaults() *WebhookRefundPayload`

NewWebhookRefundPayloadWithDefaults instantiates a new WebhookRefundPayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WebhookRefundPayload) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WebhookRefundPayload) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WebhookRefundPayload) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *WebhookRefundPayload) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPaymentId

`func (o *WebhookRefundPayload) GetPaymentId() string`

GetPaymentId returns the PaymentId field if non-nil, zero value otherwise.

### GetPaymentIdOk

`func (o *WebhookRefundPayload) GetPaymentIdOk() (*string, bool)`

GetPaymentIdOk returns a tuple with the PaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentId

`func (o *WebhookRefundPayload) SetPaymentId(v string)`

SetPaymentId sets PaymentId field to given value.

### HasPaymentId

`func (o *WebhookRefundPayload) HasPaymentId() bool`

HasPaymentId returns a boolean if a field has been set.

### GetAmount

`func (o *WebhookRefundPayload) GetAmount() string`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *WebhookRefundPayload) GetAmountOk() (*string, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *WebhookRefundPayload) SetAmount(v string)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *WebhookRefundPayload) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCurrency

`func (o *WebhookRefundPayload) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *WebhookRefundPayload) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *WebhookRefundPayload) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *WebhookRefundPayload) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetStatus

`func (o *WebhookRefundPayload) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WebhookRefundPayload) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WebhookRefundPayload) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *WebhookRefundPayload) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetReason

`func (o *WebhookRefundPayload) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *WebhookRefundPayload) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *WebhookRefundPayload) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *WebhookRefundPayload) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *WebhookRefundPayload) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *WebhookRefundPayload) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetReferenceValue

`func (o *WebhookRefundPayload) GetReferenceValue() string`

GetReferenceValue returns the ReferenceValue field if non-nil, zero value otherwise.

### GetReferenceValueOk

`func (o *WebhookRefundPayload) GetReferenceValueOk() (*string, bool)`

GetReferenceValueOk returns a tuple with the ReferenceValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceValue

`func (o *WebhookRefundPayload) SetReferenceValue(v string)`

SetReferenceValue sets ReferenceValue field to given value.

### HasReferenceValue

`func (o *WebhookRefundPayload) HasReferenceValue() bool`

HasReferenceValue returns a boolean if a field has been set.

### SetReferenceValueNil

`func (o *WebhookRefundPayload) SetReferenceValueNil(b bool)`

 SetReferenceValueNil sets the value for ReferenceValue to be an explicit nil

### UnsetReferenceValue
`func (o *WebhookRefundPayload) UnsetReferenceValue()`

UnsetReferenceValue ensures that no value is present for ReferenceValue, not even an explicit nil
### GetProvider

`func (o *WebhookRefundPayload) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *WebhookRefundPayload) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *WebhookRefundPayload) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *WebhookRefundPayload) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *WebhookRefundPayload) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *WebhookRefundPayload) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetProviderCreatedAt

`func (o *WebhookRefundPayload) GetProviderCreatedAt() time.Time`

GetProviderCreatedAt returns the ProviderCreatedAt field if non-nil, zero value otherwise.

### GetProviderCreatedAtOk

`func (o *WebhookRefundPayload) GetProviderCreatedAtOk() (*time.Time, bool)`

GetProviderCreatedAtOk returns a tuple with the ProviderCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderCreatedAt

`func (o *WebhookRefundPayload) SetProviderCreatedAt(v time.Time)`

SetProviderCreatedAt sets ProviderCreatedAt field to given value.

### HasProviderCreatedAt

`func (o *WebhookRefundPayload) HasProviderCreatedAt() bool`

HasProviderCreatedAt returns a boolean if a field has been set.

### SetProviderCreatedAtNil

`func (o *WebhookRefundPayload) SetProviderCreatedAtNil(b bool)`

 SetProviderCreatedAtNil sets the value for ProviderCreatedAt to be an explicit nil

### UnsetProviderCreatedAt
`func (o *WebhookRefundPayload) UnsetProviderCreatedAt()`

UnsetProviderCreatedAt ensures that no value is present for ProviderCreatedAt, not even an explicit nil
### GetCreatedAt

`func (o *WebhookRefundPayload) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WebhookRefundPayload) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WebhookRefundPayload) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *WebhookRefundPayload) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *WebhookRefundPayload) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *WebhookRefundPayload) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *WebhookRefundPayload) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *WebhookRefundPayload) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


