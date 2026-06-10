# WebhookSubscriptionPayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The subscription ID. | [optional] 
**Status** | Pointer to **string** | Current status of the subscription. | [optional] 
**CancelAtPeriodEnd** | Pointer to **bool** |  | [optional] 
**RenewalPeriodStart** | Pointer to **NullableTime** |  | [optional] 
**RenewalPeriodEnd** | Pointer to **NullableTime** |  | [optional] 
**Currency** | Pointer to **string** |  | [optional] 
**Amount** | Pointer to **float32** |  | [optional] 
**CustomerId** | Pointer to **NullableString** |  | [optional] 
**CustomerEmail** | Pointer to **NullableString** |  | [optional] 
**CustomerName** | Pointer to **NullableString** |  | [optional] 
**ProductId** | Pointer to **NullableString** |  | [optional] 
**ProductTitle** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewWebhookSubscriptionPayload

`func NewWebhookSubscriptionPayload() *WebhookSubscriptionPayload`

NewWebhookSubscriptionPayload instantiates a new WebhookSubscriptionPayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookSubscriptionPayloadWithDefaults

`func NewWebhookSubscriptionPayloadWithDefaults() *WebhookSubscriptionPayload`

NewWebhookSubscriptionPayloadWithDefaults instantiates a new WebhookSubscriptionPayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WebhookSubscriptionPayload) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WebhookSubscriptionPayload) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WebhookSubscriptionPayload) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *WebhookSubscriptionPayload) HasId() bool`

HasId returns a boolean if a field has been set.

### GetStatus

`func (o *WebhookSubscriptionPayload) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WebhookSubscriptionPayload) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WebhookSubscriptionPayload) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *WebhookSubscriptionPayload) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCancelAtPeriodEnd

`func (o *WebhookSubscriptionPayload) GetCancelAtPeriodEnd() bool`

GetCancelAtPeriodEnd returns the CancelAtPeriodEnd field if non-nil, zero value otherwise.

### GetCancelAtPeriodEndOk

`func (o *WebhookSubscriptionPayload) GetCancelAtPeriodEndOk() (*bool, bool)`

GetCancelAtPeriodEndOk returns a tuple with the CancelAtPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelAtPeriodEnd

`func (o *WebhookSubscriptionPayload) SetCancelAtPeriodEnd(v bool)`

SetCancelAtPeriodEnd sets CancelAtPeriodEnd field to given value.

### HasCancelAtPeriodEnd

`func (o *WebhookSubscriptionPayload) HasCancelAtPeriodEnd() bool`

HasCancelAtPeriodEnd returns a boolean if a field has been set.

### GetRenewalPeriodStart

`func (o *WebhookSubscriptionPayload) GetRenewalPeriodStart() time.Time`

GetRenewalPeriodStart returns the RenewalPeriodStart field if non-nil, zero value otherwise.

### GetRenewalPeriodStartOk

`func (o *WebhookSubscriptionPayload) GetRenewalPeriodStartOk() (*time.Time, bool)`

GetRenewalPeriodStartOk returns a tuple with the RenewalPeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenewalPeriodStart

`func (o *WebhookSubscriptionPayload) SetRenewalPeriodStart(v time.Time)`

SetRenewalPeriodStart sets RenewalPeriodStart field to given value.

### HasRenewalPeriodStart

`func (o *WebhookSubscriptionPayload) HasRenewalPeriodStart() bool`

HasRenewalPeriodStart returns a boolean if a field has been set.

### SetRenewalPeriodStartNil

`func (o *WebhookSubscriptionPayload) SetRenewalPeriodStartNil(b bool)`

 SetRenewalPeriodStartNil sets the value for RenewalPeriodStart to be an explicit nil

### UnsetRenewalPeriodStart
`func (o *WebhookSubscriptionPayload) UnsetRenewalPeriodStart()`

UnsetRenewalPeriodStart ensures that no value is present for RenewalPeriodStart, not even an explicit nil
### GetRenewalPeriodEnd

`func (o *WebhookSubscriptionPayload) GetRenewalPeriodEnd() time.Time`

GetRenewalPeriodEnd returns the RenewalPeriodEnd field if non-nil, zero value otherwise.

### GetRenewalPeriodEndOk

`func (o *WebhookSubscriptionPayload) GetRenewalPeriodEndOk() (*time.Time, bool)`

GetRenewalPeriodEndOk returns a tuple with the RenewalPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenewalPeriodEnd

`func (o *WebhookSubscriptionPayload) SetRenewalPeriodEnd(v time.Time)`

SetRenewalPeriodEnd sets RenewalPeriodEnd field to given value.

### HasRenewalPeriodEnd

`func (o *WebhookSubscriptionPayload) HasRenewalPeriodEnd() bool`

HasRenewalPeriodEnd returns a boolean if a field has been set.

### SetRenewalPeriodEndNil

`func (o *WebhookSubscriptionPayload) SetRenewalPeriodEndNil(b bool)`

 SetRenewalPeriodEndNil sets the value for RenewalPeriodEnd to be an explicit nil

### UnsetRenewalPeriodEnd
`func (o *WebhookSubscriptionPayload) UnsetRenewalPeriodEnd()`

UnsetRenewalPeriodEnd ensures that no value is present for RenewalPeriodEnd, not even an explicit nil
### GetCurrency

`func (o *WebhookSubscriptionPayload) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *WebhookSubscriptionPayload) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *WebhookSubscriptionPayload) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *WebhookSubscriptionPayload) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetAmount

`func (o *WebhookSubscriptionPayload) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *WebhookSubscriptionPayload) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *WebhookSubscriptionPayload) SetAmount(v float32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *WebhookSubscriptionPayload) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCustomerId

`func (o *WebhookSubscriptionPayload) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *WebhookSubscriptionPayload) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *WebhookSubscriptionPayload) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *WebhookSubscriptionPayload) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *WebhookSubscriptionPayload) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *WebhookSubscriptionPayload) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetCustomerEmail

`func (o *WebhookSubscriptionPayload) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *WebhookSubscriptionPayload) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *WebhookSubscriptionPayload) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *WebhookSubscriptionPayload) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *WebhookSubscriptionPayload) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *WebhookSubscriptionPayload) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetCustomerName

`func (o *WebhookSubscriptionPayload) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *WebhookSubscriptionPayload) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *WebhookSubscriptionPayload) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *WebhookSubscriptionPayload) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *WebhookSubscriptionPayload) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *WebhookSubscriptionPayload) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetProductId

`func (o *WebhookSubscriptionPayload) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *WebhookSubscriptionPayload) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *WebhookSubscriptionPayload) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *WebhookSubscriptionPayload) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *WebhookSubscriptionPayload) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *WebhookSubscriptionPayload) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetProductTitle

`func (o *WebhookSubscriptionPayload) GetProductTitle() string`

GetProductTitle returns the ProductTitle field if non-nil, zero value otherwise.

### GetProductTitleOk

`func (o *WebhookSubscriptionPayload) GetProductTitleOk() (*string, bool)`

GetProductTitleOk returns a tuple with the ProductTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductTitle

`func (o *WebhookSubscriptionPayload) SetProductTitle(v string)`

SetProductTitle sets ProductTitle field to given value.

### HasProductTitle

`func (o *WebhookSubscriptionPayload) HasProductTitle() bool`

HasProductTitle returns a boolean if a field has been set.

### SetProductTitleNil

`func (o *WebhookSubscriptionPayload) SetProductTitleNil(b bool)`

 SetProductTitleNil sets the value for ProductTitle to be an explicit nil

### UnsetProductTitle
`func (o *WebhookSubscriptionPayload) UnsetProductTitle()`

UnsetProductTitle ensures that no value is present for ProductTitle, not even an explicit nil
### GetCreatedAt

`func (o *WebhookSubscriptionPayload) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WebhookSubscriptionPayload) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WebhookSubscriptionPayload) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *WebhookSubscriptionPayload) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *WebhookSubscriptionPayload) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *WebhookSubscriptionPayload) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *WebhookSubscriptionPayload) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *WebhookSubscriptionPayload) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *WebhookSubscriptionPayload) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *WebhookSubscriptionPayload) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *WebhookSubscriptionPayload) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *WebhookSubscriptionPayload) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


