# SubscriptionAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FreeDays** | Pointer to **float32** | Number of free days to add (used with action: add_free_days) | [optional] 
**CancellationMode** | Pointer to **string** | Cancellation mode (used with action: cancel) | [optional] 
**VoidPayments** | Pointer to **bool** | Whether to void subsequent payments (used with action: pause) | [optional] 
**AddonProductId** | Pointer to **string** | ID of the addon product to adjust seats for (used with action: adjust_seats) | [optional] 
**NewQuantity** | Pointer to **float32** | The new seat quantity (used with action: adjust_seats) | [optional] 
**ProrationType** | Pointer to **string** | Proration strategy mode (used with action: adjust_seats) | [optional] 
**IdempotencyKey** | Pointer to **string** | A unique idempotency key to prevent duplicate mutative actions for network transient retries. | [optional] 

## Methods

### NewSubscriptionAction

`func NewSubscriptionAction() *SubscriptionAction`

NewSubscriptionAction instantiates a new SubscriptionAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionActionWithDefaults

`func NewSubscriptionActionWithDefaults() *SubscriptionAction`

NewSubscriptionActionWithDefaults instantiates a new SubscriptionAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFreeDays

`func (o *SubscriptionAction) GetFreeDays() float32`

GetFreeDays returns the FreeDays field if non-nil, zero value otherwise.

### GetFreeDaysOk

`func (o *SubscriptionAction) GetFreeDaysOk() (*float32, bool)`

GetFreeDaysOk returns a tuple with the FreeDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreeDays

`func (o *SubscriptionAction) SetFreeDays(v float32)`

SetFreeDays sets FreeDays field to given value.

### HasFreeDays

`func (o *SubscriptionAction) HasFreeDays() bool`

HasFreeDays returns a boolean if a field has been set.

### GetCancellationMode

`func (o *SubscriptionAction) GetCancellationMode() string`

GetCancellationMode returns the CancellationMode field if non-nil, zero value otherwise.

### GetCancellationModeOk

`func (o *SubscriptionAction) GetCancellationModeOk() (*string, bool)`

GetCancellationModeOk returns a tuple with the CancellationMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellationMode

`func (o *SubscriptionAction) SetCancellationMode(v string)`

SetCancellationMode sets CancellationMode field to given value.

### HasCancellationMode

`func (o *SubscriptionAction) HasCancellationMode() bool`

HasCancellationMode returns a boolean if a field has been set.

### GetVoidPayments

`func (o *SubscriptionAction) GetVoidPayments() bool`

GetVoidPayments returns the VoidPayments field if non-nil, zero value otherwise.

### GetVoidPaymentsOk

`func (o *SubscriptionAction) GetVoidPaymentsOk() (*bool, bool)`

GetVoidPaymentsOk returns a tuple with the VoidPayments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoidPayments

`func (o *SubscriptionAction) SetVoidPayments(v bool)`

SetVoidPayments sets VoidPayments field to given value.

### HasVoidPayments

`func (o *SubscriptionAction) HasVoidPayments() bool`

HasVoidPayments returns a boolean if a field has been set.

### GetAddonProductId

`func (o *SubscriptionAction) GetAddonProductId() string`

GetAddonProductId returns the AddonProductId field if non-nil, zero value otherwise.

### GetAddonProductIdOk

`func (o *SubscriptionAction) GetAddonProductIdOk() (*string, bool)`

GetAddonProductIdOk returns a tuple with the AddonProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddonProductId

`func (o *SubscriptionAction) SetAddonProductId(v string)`

SetAddonProductId sets AddonProductId field to given value.

### HasAddonProductId

`func (o *SubscriptionAction) HasAddonProductId() bool`

HasAddonProductId returns a boolean if a field has been set.

### GetNewQuantity

`func (o *SubscriptionAction) GetNewQuantity() float32`

GetNewQuantity returns the NewQuantity field if non-nil, zero value otherwise.

### GetNewQuantityOk

`func (o *SubscriptionAction) GetNewQuantityOk() (*float32, bool)`

GetNewQuantityOk returns a tuple with the NewQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewQuantity

`func (o *SubscriptionAction) SetNewQuantity(v float32)`

SetNewQuantity sets NewQuantity field to given value.

### HasNewQuantity

`func (o *SubscriptionAction) HasNewQuantity() bool`

HasNewQuantity returns a boolean if a field has been set.

### GetProrationType

`func (o *SubscriptionAction) GetProrationType() string`

GetProrationType returns the ProrationType field if non-nil, zero value otherwise.

### GetProrationTypeOk

`func (o *SubscriptionAction) GetProrationTypeOk() (*string, bool)`

GetProrationTypeOk returns a tuple with the ProrationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProrationType

`func (o *SubscriptionAction) SetProrationType(v string)`

SetProrationType sets ProrationType field to given value.

### HasProrationType

`func (o *SubscriptionAction) HasProrationType() bool`

HasProrationType returns a boolean if a field has been set.

### GetIdempotencyKey

`func (o *SubscriptionAction) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *SubscriptionAction) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *SubscriptionAction) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.

### HasIdempotencyKey

`func (o *SubscriptionAction) HasIdempotencyKey() bool`

HasIdempotencyKey returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


