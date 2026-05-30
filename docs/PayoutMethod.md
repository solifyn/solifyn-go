# PayoutMethod

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The payout method ID | 
**Type** | **string** | Type of payout method (e.g. bank_account, stripe) | 
**Status** | **string** | Status of the payout method | 
**Details** | Pointer to **map[string]interface{}** | Metadata and details of the bank/card associated | [optional] 

## Methods

### NewPayoutMethod

`func NewPayoutMethod(id string, type_ string, status string, ) *PayoutMethod`

NewPayoutMethod instantiates a new PayoutMethod object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPayoutMethodWithDefaults

`func NewPayoutMethodWithDefaults() *PayoutMethod`

NewPayoutMethodWithDefaults instantiates a new PayoutMethod object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PayoutMethod) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PayoutMethod) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PayoutMethod) SetId(v string)`

SetId sets Id field to given value.


### GetType

`func (o *PayoutMethod) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PayoutMethod) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PayoutMethod) SetType(v string)`

SetType sets Type field to given value.


### GetStatus

`func (o *PayoutMethod) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PayoutMethod) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PayoutMethod) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetDetails

`func (o *PayoutMethod) GetDetails() map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *PayoutMethod) GetDetailsOk() (*map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *PayoutMethod) SetDetails(v map[string]interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *PayoutMethod) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


