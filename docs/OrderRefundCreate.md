# OrderRefundCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | **int32** | The refund amount in cents. If full refund is true, this can represent the total amount. | 
**IsFullRefund** | **bool** | Whether this is a full refund or a partial refund. | 
**IdempotencyKey** | **string** | A unique idempotency key to prevent double refunds for transient network retries. | 
**AutoRevokeSeats** | Pointer to **bool** | Whether to automatically revoke seat add-ons matching the refund amount. | [optional] 
**RevokeSeats** | Pointer to [**[]RevokeSeatDto**](RevokeSeatDto.md) | List of specific addons and the quantities of seats to revoke. | [optional] 

## Methods

### NewOrderRefundCreate

`func NewOrderRefundCreate(amount int32, isFullRefund bool, idempotencyKey string, ) *OrderRefundCreate`

NewOrderRefundCreate instantiates a new OrderRefundCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderRefundCreateWithDefaults

`func NewOrderRefundCreateWithDefaults() *OrderRefundCreate`

NewOrderRefundCreateWithDefaults instantiates a new OrderRefundCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *OrderRefundCreate) GetAmount() int32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *OrderRefundCreate) GetAmountOk() (*int32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *OrderRefundCreate) SetAmount(v int32)`

SetAmount sets Amount field to given value.


### GetIsFullRefund

`func (o *OrderRefundCreate) GetIsFullRefund() bool`

GetIsFullRefund returns the IsFullRefund field if non-nil, zero value otherwise.

### GetIsFullRefundOk

`func (o *OrderRefundCreate) GetIsFullRefundOk() (*bool, bool)`

GetIsFullRefundOk returns a tuple with the IsFullRefund field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFullRefund

`func (o *OrderRefundCreate) SetIsFullRefund(v bool)`

SetIsFullRefund sets IsFullRefund field to given value.


### GetIdempotencyKey

`func (o *OrderRefundCreate) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *OrderRefundCreate) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *OrderRefundCreate) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetAutoRevokeSeats

`func (o *OrderRefundCreate) GetAutoRevokeSeats() bool`

GetAutoRevokeSeats returns the AutoRevokeSeats field if non-nil, zero value otherwise.

### GetAutoRevokeSeatsOk

`func (o *OrderRefundCreate) GetAutoRevokeSeatsOk() (*bool, bool)`

GetAutoRevokeSeatsOk returns a tuple with the AutoRevokeSeats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoRevokeSeats

`func (o *OrderRefundCreate) SetAutoRevokeSeats(v bool)`

SetAutoRevokeSeats sets AutoRevokeSeats field to given value.

### HasAutoRevokeSeats

`func (o *OrderRefundCreate) HasAutoRevokeSeats() bool`

HasAutoRevokeSeats returns a boolean if a field has been set.

### GetRevokeSeats

`func (o *OrderRefundCreate) GetRevokeSeats() []RevokeSeatDto`

GetRevokeSeats returns the RevokeSeats field if non-nil, zero value otherwise.

### GetRevokeSeatsOk

`func (o *OrderRefundCreate) GetRevokeSeatsOk() (*[]RevokeSeatDto, bool)`

GetRevokeSeatsOk returns a tuple with the RevokeSeats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevokeSeats

`func (o *OrderRefundCreate) SetRevokeSeats(v []RevokeSeatDto)`

SetRevokeSeats sets RevokeSeats field to given value.

### HasRevokeSeats

`func (o *OrderRefundCreate) HasRevokeSeats() bool`

HasRevokeSeats returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


