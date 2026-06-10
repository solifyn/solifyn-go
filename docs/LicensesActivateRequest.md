# LicensesActivateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** | The license key. | 
**DeviceIdentifier** | **string** | Unique identifier of the device/machine being activated. | 
**Name** | **string** | A user-friendly label/name for the instance. | 

## Methods

### NewLicensesActivateRequest

`func NewLicensesActivateRequest(key string, deviceIdentifier string, name string, ) *LicensesActivateRequest`

NewLicensesActivateRequest instantiates a new LicensesActivateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicensesActivateRequestWithDefaults

`func NewLicensesActivateRequestWithDefaults() *LicensesActivateRequest`

NewLicensesActivateRequestWithDefaults instantiates a new LicensesActivateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *LicensesActivateRequest) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *LicensesActivateRequest) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *LicensesActivateRequest) SetKey(v string)`

SetKey sets Key field to given value.


### GetDeviceIdentifier

`func (o *LicensesActivateRequest) GetDeviceIdentifier() string`

GetDeviceIdentifier returns the DeviceIdentifier field if non-nil, zero value otherwise.

### GetDeviceIdentifierOk

`func (o *LicensesActivateRequest) GetDeviceIdentifierOk() (*string, bool)`

GetDeviceIdentifierOk returns a tuple with the DeviceIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceIdentifier

`func (o *LicensesActivateRequest) SetDeviceIdentifier(v string)`

SetDeviceIdentifier sets DeviceIdentifier field to given value.


### GetName

`func (o *LicensesActivateRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LicensesActivateRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LicensesActivateRequest) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


