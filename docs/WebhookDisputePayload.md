# WebhookDisputePayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Internal dispute ID. | [optional] 
**PaymentId** | Pointer to **string** |  | [optional] 
**Amount** | Pointer to **string** | Dollar value, 2 d.p. | [optional] 
**Currency** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Reason** | Pointer to **string** |  | [optional] 
**Editable** | Pointer to **bool** |  | [optional] 
**NeedsResponseBy** | Pointer to **time.Time** |  | [optional] 
**CustomerName** | Pointer to **string** |  | [optional] 
**CustomerEmail** | Pointer to **string** |  | [optional] 
**Notes** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewWebhookDisputePayload

`func NewWebhookDisputePayload() *WebhookDisputePayload`

NewWebhookDisputePayload instantiates a new WebhookDisputePayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookDisputePayloadWithDefaults

`func NewWebhookDisputePayloadWithDefaults() *WebhookDisputePayload`

NewWebhookDisputePayloadWithDefaults instantiates a new WebhookDisputePayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WebhookDisputePayload) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WebhookDisputePayload) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WebhookDisputePayload) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *WebhookDisputePayload) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPaymentId

`func (o *WebhookDisputePayload) GetPaymentId() string`

GetPaymentId returns the PaymentId field if non-nil, zero value otherwise.

### GetPaymentIdOk

`func (o *WebhookDisputePayload) GetPaymentIdOk() (*string, bool)`

GetPaymentIdOk returns a tuple with the PaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentId

`func (o *WebhookDisputePayload) SetPaymentId(v string)`

SetPaymentId sets PaymentId field to given value.

### HasPaymentId

`func (o *WebhookDisputePayload) HasPaymentId() bool`

HasPaymentId returns a boolean if a field has been set.

### GetAmount

`func (o *WebhookDisputePayload) GetAmount() string`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *WebhookDisputePayload) GetAmountOk() (*string, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *WebhookDisputePayload) SetAmount(v string)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *WebhookDisputePayload) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCurrency

`func (o *WebhookDisputePayload) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *WebhookDisputePayload) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *WebhookDisputePayload) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *WebhookDisputePayload) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetStatus

`func (o *WebhookDisputePayload) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WebhookDisputePayload) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WebhookDisputePayload) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *WebhookDisputePayload) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetReason

`func (o *WebhookDisputePayload) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *WebhookDisputePayload) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *WebhookDisputePayload) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *WebhookDisputePayload) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetEditable

`func (o *WebhookDisputePayload) GetEditable() bool`

GetEditable returns the Editable field if non-nil, zero value otherwise.

### GetEditableOk

`func (o *WebhookDisputePayload) GetEditableOk() (*bool, bool)`

GetEditableOk returns a tuple with the Editable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEditable

`func (o *WebhookDisputePayload) SetEditable(v bool)`

SetEditable sets Editable field to given value.

### HasEditable

`func (o *WebhookDisputePayload) HasEditable() bool`

HasEditable returns a boolean if a field has been set.

### GetNeedsResponseBy

`func (o *WebhookDisputePayload) GetNeedsResponseBy() time.Time`

GetNeedsResponseBy returns the NeedsResponseBy field if non-nil, zero value otherwise.

### GetNeedsResponseByOk

`func (o *WebhookDisputePayload) GetNeedsResponseByOk() (*time.Time, bool)`

GetNeedsResponseByOk returns a tuple with the NeedsResponseBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeedsResponseBy

`func (o *WebhookDisputePayload) SetNeedsResponseBy(v time.Time)`

SetNeedsResponseBy sets NeedsResponseBy field to given value.

### HasNeedsResponseBy

`func (o *WebhookDisputePayload) HasNeedsResponseBy() bool`

HasNeedsResponseBy returns a boolean if a field has been set.

### GetCustomerName

`func (o *WebhookDisputePayload) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *WebhookDisputePayload) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *WebhookDisputePayload) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *WebhookDisputePayload) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### GetCustomerEmail

`func (o *WebhookDisputePayload) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *WebhookDisputePayload) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *WebhookDisputePayload) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *WebhookDisputePayload) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### GetNotes

`func (o *WebhookDisputePayload) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *WebhookDisputePayload) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *WebhookDisputePayload) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *WebhookDisputePayload) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetCreatedAt

`func (o *WebhookDisputePayload) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WebhookDisputePayload) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WebhookDisputePayload) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *WebhookDisputePayload) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *WebhookDisputePayload) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *WebhookDisputePayload) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *WebhookDisputePayload) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *WebhookDisputePayload) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


