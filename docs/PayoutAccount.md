# PayoutAccount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The payout account ID | 
**Status** | **string** | Status of the payout account onboarding | 
**Capabilities** | Pointer to **map[string]interface{}** | Onboarding capability status flags (e.g., transfers, payouts) | [optional] 

## Methods

### NewPayoutAccount

`func NewPayoutAccount(id string, status string, ) *PayoutAccount`

NewPayoutAccount instantiates a new PayoutAccount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPayoutAccountWithDefaults

`func NewPayoutAccountWithDefaults() *PayoutAccount`

NewPayoutAccountWithDefaults instantiates a new PayoutAccount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PayoutAccount) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PayoutAccount) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PayoutAccount) SetId(v string)`

SetId sets Id field to given value.


### GetStatus

`func (o *PayoutAccount) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PayoutAccount) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PayoutAccount) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCapabilities

`func (o *PayoutAccount) GetCapabilities() map[string]interface{}`

GetCapabilities returns the Capabilities field if non-nil, zero value otherwise.

### GetCapabilitiesOk

`func (o *PayoutAccount) GetCapabilitiesOk() (*map[string]interface{}, bool)`

GetCapabilitiesOk returns a tuple with the Capabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapabilities

`func (o *PayoutAccount) SetCapabilities(v map[string]interface{})`

SetCapabilities sets Capabilities field to given value.

### HasCapabilities

`func (o *PayoutAccount) HasCapabilities() bool`

HasCapabilities returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


