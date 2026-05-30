# Withdrawal

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The local withdrawal ID | 
**WhopId** | **string** | The Whop withdrawal ID | 
**Amount** | **float32** | The amount withdrawn in cents | 
**Currency** | **string** | Three-letter ISO currency code | 
**Status** | **string** | The status of the withdrawal request | 
**FeeAmount** | Pointer to **float32** | Fee amount charged for the withdrawal in cents | [optional] 
**FeeType** | Pointer to **string** | The fee structure type (inclusive or exclusive) | [optional] 
**MarkupFee** | Pointer to **float32** | Markup fee applied in cents | [optional] 
**Speed** | Pointer to **string** | Speed of withdrawal (standard, instant) | [optional] 
**TraceCode** | Pointer to **string** | Bank trace or reference code for tracking the payout | [optional] 
**PayerName** | Pointer to **string** | The name of the entity or account paying out | [optional] 
**ErrorMessage** | Pointer to **string** | Error message if the withdrawal failed | [optional] 
**BusinessId** | **string** | The business ID associated with this withdrawal | 
**CreatedAt** | **time.Time** | Timestamp when the withdrawal was requested | 
**UpdatedAt** | **time.Time** | Timestamp when the withdrawal status was updated | 

## Methods

### NewWithdrawal

`func NewWithdrawal(id string, whopId string, amount float32, currency string, status string, businessId string, createdAt time.Time, updatedAt time.Time, ) *Withdrawal`

NewWithdrawal instantiates a new Withdrawal object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWithdrawalWithDefaults

`func NewWithdrawalWithDefaults() *Withdrawal`

NewWithdrawalWithDefaults instantiates a new Withdrawal object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Withdrawal) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Withdrawal) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Withdrawal) SetId(v string)`

SetId sets Id field to given value.


### GetWhopId

`func (o *Withdrawal) GetWhopId() string`

GetWhopId returns the WhopId field if non-nil, zero value otherwise.

### GetWhopIdOk

`func (o *Withdrawal) GetWhopIdOk() (*string, bool)`

GetWhopIdOk returns a tuple with the WhopId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhopId

`func (o *Withdrawal) SetWhopId(v string)`

SetWhopId sets WhopId field to given value.


### GetAmount

`func (o *Withdrawal) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *Withdrawal) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *Withdrawal) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### GetCurrency

`func (o *Withdrawal) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Withdrawal) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Withdrawal) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetStatus

`func (o *Withdrawal) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Withdrawal) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Withdrawal) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetFeeAmount

`func (o *Withdrawal) GetFeeAmount() float32`

GetFeeAmount returns the FeeAmount field if non-nil, zero value otherwise.

### GetFeeAmountOk

`func (o *Withdrawal) GetFeeAmountOk() (*float32, bool)`

GetFeeAmountOk returns a tuple with the FeeAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeeAmount

`func (o *Withdrawal) SetFeeAmount(v float32)`

SetFeeAmount sets FeeAmount field to given value.

### HasFeeAmount

`func (o *Withdrawal) HasFeeAmount() bool`

HasFeeAmount returns a boolean if a field has been set.

### GetFeeType

`func (o *Withdrawal) GetFeeType() string`

GetFeeType returns the FeeType field if non-nil, zero value otherwise.

### GetFeeTypeOk

`func (o *Withdrawal) GetFeeTypeOk() (*string, bool)`

GetFeeTypeOk returns a tuple with the FeeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeeType

`func (o *Withdrawal) SetFeeType(v string)`

SetFeeType sets FeeType field to given value.

### HasFeeType

`func (o *Withdrawal) HasFeeType() bool`

HasFeeType returns a boolean if a field has been set.

### GetMarkupFee

`func (o *Withdrawal) GetMarkupFee() float32`

GetMarkupFee returns the MarkupFee field if non-nil, zero value otherwise.

### GetMarkupFeeOk

`func (o *Withdrawal) GetMarkupFeeOk() (*float32, bool)`

GetMarkupFeeOk returns a tuple with the MarkupFee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkupFee

`func (o *Withdrawal) SetMarkupFee(v float32)`

SetMarkupFee sets MarkupFee field to given value.

### HasMarkupFee

`func (o *Withdrawal) HasMarkupFee() bool`

HasMarkupFee returns a boolean if a field has been set.

### GetSpeed

`func (o *Withdrawal) GetSpeed() string`

GetSpeed returns the Speed field if non-nil, zero value otherwise.

### GetSpeedOk

`func (o *Withdrawal) GetSpeedOk() (*string, bool)`

GetSpeedOk returns a tuple with the Speed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpeed

`func (o *Withdrawal) SetSpeed(v string)`

SetSpeed sets Speed field to given value.

### HasSpeed

`func (o *Withdrawal) HasSpeed() bool`

HasSpeed returns a boolean if a field has been set.

### GetTraceCode

`func (o *Withdrawal) GetTraceCode() string`

GetTraceCode returns the TraceCode field if non-nil, zero value otherwise.

### GetTraceCodeOk

`func (o *Withdrawal) GetTraceCodeOk() (*string, bool)`

GetTraceCodeOk returns a tuple with the TraceCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraceCode

`func (o *Withdrawal) SetTraceCode(v string)`

SetTraceCode sets TraceCode field to given value.

### HasTraceCode

`func (o *Withdrawal) HasTraceCode() bool`

HasTraceCode returns a boolean if a field has been set.

### GetPayerName

`func (o *Withdrawal) GetPayerName() string`

GetPayerName returns the PayerName field if non-nil, zero value otherwise.

### GetPayerNameOk

`func (o *Withdrawal) GetPayerNameOk() (*string, bool)`

GetPayerNameOk returns a tuple with the PayerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayerName

`func (o *Withdrawal) SetPayerName(v string)`

SetPayerName sets PayerName field to given value.

### HasPayerName

`func (o *Withdrawal) HasPayerName() bool`

HasPayerName returns a boolean if a field has been set.

### GetErrorMessage

`func (o *Withdrawal) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *Withdrawal) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *Withdrawal) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *Withdrawal) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### GetBusinessId

`func (o *Withdrawal) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *Withdrawal) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *Withdrawal) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetCreatedAt

`func (o *Withdrawal) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Withdrawal) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Withdrawal) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Withdrawal) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Withdrawal) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Withdrawal) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


