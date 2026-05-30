# PayoutVerification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The verification check ID | 
**Status** | **string** | Status of verification (pending, verified, rejected) | 
**Type** | **string** | Verification type (identity, business, address) | 
**Details** | Pointer to **map[string]interface{}** | Details and requirements of the verification check | [optional] 

## Methods

### NewPayoutVerification

`func NewPayoutVerification(id string, status string, type_ string, ) *PayoutVerification`

NewPayoutVerification instantiates a new PayoutVerification object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPayoutVerificationWithDefaults

`func NewPayoutVerificationWithDefaults() *PayoutVerification`

NewPayoutVerificationWithDefaults instantiates a new PayoutVerification object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PayoutVerification) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PayoutVerification) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PayoutVerification) SetId(v string)`

SetId sets Id field to given value.


### GetStatus

`func (o *PayoutVerification) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PayoutVerification) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PayoutVerification) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetType

`func (o *PayoutVerification) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PayoutVerification) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PayoutVerification) SetType(v string)`

SetType sets Type field to given value.


### GetDetails

`func (o *PayoutVerification) GetDetails() map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *PayoutVerification) GetDetailsOk() (*map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *PayoutVerification) SetDetails(v map[string]interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *PayoutVerification) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


