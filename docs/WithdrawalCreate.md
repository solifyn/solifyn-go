# WithdrawalCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | **float32** | The amount to withdraw in cents (e.g. 1000 for $10.00) | 
**Currency** | **string** | Three-letter ISO currency code (lowercase) | 
**PayoutMethodId** | Pointer to **string** | The ID of the payout method to withdraw to. If omitted, default is used. | [optional] 

## Methods

### NewWithdrawalCreate

`func NewWithdrawalCreate(amount float32, currency string, ) *WithdrawalCreate`

NewWithdrawalCreate instantiates a new WithdrawalCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWithdrawalCreateWithDefaults

`func NewWithdrawalCreateWithDefaults() *WithdrawalCreate`

NewWithdrawalCreateWithDefaults instantiates a new WithdrawalCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *WithdrawalCreate) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *WithdrawalCreate) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *WithdrawalCreate) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### GetCurrency

`func (o *WithdrawalCreate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *WithdrawalCreate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *WithdrawalCreate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetPayoutMethodId

`func (o *WithdrawalCreate) GetPayoutMethodId() string`

GetPayoutMethodId returns the PayoutMethodId field if non-nil, zero value otherwise.

### GetPayoutMethodIdOk

`func (o *WithdrawalCreate) GetPayoutMethodIdOk() (*string, bool)`

GetPayoutMethodIdOk returns a tuple with the PayoutMethodId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayoutMethodId

`func (o *WithdrawalCreate) SetPayoutMethodId(v string)`

SetPayoutMethodId sets PayoutMethodId field to given value.

### HasPayoutMethodId

`func (o *WithdrawalCreate) HasPayoutMethodId() bool`

HasPayoutMethodId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


