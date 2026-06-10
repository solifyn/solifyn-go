# LicenseSubDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Key** | **string** |  | 
**Status** | **string** |  | 
**ActivationLimit** | **float32** |  | 
**ActivationMessage** | **string** |  | 
**ExpiresAt** | **string** |  | 
**Product** | Pointer to [**ProductSubDto**](ProductSubDto.md) |  | [optional] 

## Methods

### NewLicenseSubDto

`func NewLicenseSubDto(id string, key string, status string, activationLimit float32, activationMessage string, expiresAt string, ) *LicenseSubDto`

NewLicenseSubDto instantiates a new LicenseSubDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicenseSubDtoWithDefaults

`func NewLicenseSubDtoWithDefaults() *LicenseSubDto`

NewLicenseSubDtoWithDefaults instantiates a new LicenseSubDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *LicenseSubDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LicenseSubDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LicenseSubDto) SetId(v string)`

SetId sets Id field to given value.


### GetKey

`func (o *LicenseSubDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *LicenseSubDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *LicenseSubDto) SetKey(v string)`

SetKey sets Key field to given value.


### GetStatus

`func (o *LicenseSubDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LicenseSubDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LicenseSubDto) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetActivationLimit

`func (o *LicenseSubDto) GetActivationLimit() float32`

GetActivationLimit returns the ActivationLimit field if non-nil, zero value otherwise.

### GetActivationLimitOk

`func (o *LicenseSubDto) GetActivationLimitOk() (*float32, bool)`

GetActivationLimitOk returns a tuple with the ActivationLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationLimit

`func (o *LicenseSubDto) SetActivationLimit(v float32)`

SetActivationLimit sets ActivationLimit field to given value.


### GetActivationMessage

`func (o *LicenseSubDto) GetActivationMessage() string`

GetActivationMessage returns the ActivationMessage field if non-nil, zero value otherwise.

### GetActivationMessageOk

`func (o *LicenseSubDto) GetActivationMessageOk() (*string, bool)`

GetActivationMessageOk returns a tuple with the ActivationMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationMessage

`func (o *LicenseSubDto) SetActivationMessage(v string)`

SetActivationMessage sets ActivationMessage field to given value.


### GetExpiresAt

`func (o *LicenseSubDto) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *LicenseSubDto) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *LicenseSubDto) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.


### GetProduct

`func (o *LicenseSubDto) GetProduct() ProductSubDto`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *LicenseSubDto) GetProductOk() (*ProductSubDto, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *LicenseSubDto) SetProduct(v ProductSubDto)`

SetProduct sets Product field to given value.

### HasProduct

`func (o *LicenseSubDto) HasProduct() bool`

HasProduct returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


