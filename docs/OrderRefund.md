# OrderRefund

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RefundId** | **string** | Unique refund identifier. | 
**PaymentId** | **string** | Associated payment ID. | 
**Amount** | **int32** | Refunded amount in cents. | 
**Currency** | **string** | Currency code. | 
**Status** | **string** | Status of refund. | 
**Reason** | Pointer to **string** | Reason for refund. | [optional] 
**IsPartial** | **bool** | Whether it is a partial refund. | 
**CreatedAt** | **time.Time** | Refund creation timestamp. | 

## Methods

### NewOrderRefund

`func NewOrderRefund(refundId string, paymentId string, amount int32, currency string, status string, isPartial bool, createdAt time.Time, ) *OrderRefund`

NewOrderRefund instantiates a new OrderRefund object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderRefundWithDefaults

`func NewOrderRefundWithDefaults() *OrderRefund`

NewOrderRefundWithDefaults instantiates a new OrderRefund object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRefundId

`func (o *OrderRefund) GetRefundId() string`

GetRefundId returns the RefundId field if non-nil, zero value otherwise.

### GetRefundIdOk

`func (o *OrderRefund) GetRefundIdOk() (*string, bool)`

GetRefundIdOk returns a tuple with the RefundId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefundId

`func (o *OrderRefund) SetRefundId(v string)`

SetRefundId sets RefundId field to given value.


### GetPaymentId

`func (o *OrderRefund) GetPaymentId() string`

GetPaymentId returns the PaymentId field if non-nil, zero value otherwise.

### GetPaymentIdOk

`func (o *OrderRefund) GetPaymentIdOk() (*string, bool)`

GetPaymentIdOk returns a tuple with the PaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentId

`func (o *OrderRefund) SetPaymentId(v string)`

SetPaymentId sets PaymentId field to given value.


### GetAmount

`func (o *OrderRefund) GetAmount() int32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *OrderRefund) GetAmountOk() (*int32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *OrderRefund) SetAmount(v int32)`

SetAmount sets Amount field to given value.


### GetCurrency

`func (o *OrderRefund) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *OrderRefund) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *OrderRefund) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetStatus

`func (o *OrderRefund) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OrderRefund) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OrderRefund) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetReason

`func (o *OrderRefund) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *OrderRefund) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *OrderRefund) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *OrderRefund) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetIsPartial

`func (o *OrderRefund) GetIsPartial() bool`

GetIsPartial returns the IsPartial field if non-nil, zero value otherwise.

### GetIsPartialOk

`func (o *OrderRefund) GetIsPartialOk() (*bool, bool)`

GetIsPartialOk returns a tuple with the IsPartial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPartial

`func (o *OrderRefund) SetIsPartial(v bool)`

SetIsPartial sets IsPartial field to given value.


### GetCreatedAt

`func (o *OrderRefund) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OrderRefund) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OrderRefund) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


