# WithdrawalList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]Withdrawal**](Withdrawal.md) | List of withdrawals | 
**TotalCount** | **float32** | Total count of withdrawals matching filters | 

## Methods

### NewWithdrawalList

`func NewWithdrawalList(items []Withdrawal, totalCount float32, ) *WithdrawalList`

NewWithdrawalList instantiates a new WithdrawalList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWithdrawalListWithDefaults

`func NewWithdrawalListWithDefaults() *WithdrawalList`

NewWithdrawalListWithDefaults instantiates a new WithdrawalList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *WithdrawalList) GetItems() []Withdrawal`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *WithdrawalList) GetItemsOk() (*[]Withdrawal, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *WithdrawalList) SetItems(v []Withdrawal)`

SetItems sets Items field to given value.


### GetTotalCount

`func (o *WithdrawalList) GetTotalCount() float32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *WithdrawalList) GetTotalCountOk() (*float32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *WithdrawalList) SetTotalCount(v float32)`

SetTotalCount sets TotalCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


