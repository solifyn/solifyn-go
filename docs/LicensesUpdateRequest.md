# LicensesUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] 
**ActivationLimit** | Pointer to **int32** |  | [optional] 
**ExpiresAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewLicensesUpdateRequest

`func NewLicensesUpdateRequest() *LicensesUpdateRequest`

NewLicensesUpdateRequest instantiates a new LicensesUpdateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicensesUpdateRequestWithDefaults

`func NewLicensesUpdateRequestWithDefaults() *LicensesUpdateRequest`

NewLicensesUpdateRequestWithDefaults instantiates a new LicensesUpdateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *LicensesUpdateRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LicensesUpdateRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LicensesUpdateRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *LicensesUpdateRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetActivationLimit

`func (o *LicensesUpdateRequest) GetActivationLimit() int32`

GetActivationLimit returns the ActivationLimit field if non-nil, zero value otherwise.

### GetActivationLimitOk

`func (o *LicensesUpdateRequest) GetActivationLimitOk() (*int32, bool)`

GetActivationLimitOk returns a tuple with the ActivationLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationLimit

`func (o *LicensesUpdateRequest) SetActivationLimit(v int32)`

SetActivationLimit sets ActivationLimit field to given value.

### HasActivationLimit

`func (o *LicensesUpdateRequest) HasActivationLimit() bool`

HasActivationLimit returns a boolean if a field has been set.

### GetExpiresAt

`func (o *LicensesUpdateRequest) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *LicensesUpdateRequest) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *LicensesUpdateRequest) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *LicensesUpdateRequest) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


