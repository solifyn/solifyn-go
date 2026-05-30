# LicensesUpdateInstancePostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InstanceName** | Pointer to **string** | A new human-readable display name for this instance. | [optional] 
**IpAddress** | Pointer to **string** | A new IP address to record for this instance. | [optional] 

## Methods

### NewLicensesUpdateInstancePostRequest

`func NewLicensesUpdateInstancePostRequest() *LicensesUpdateInstancePostRequest`

NewLicensesUpdateInstancePostRequest instantiates a new LicensesUpdateInstancePostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicensesUpdateInstancePostRequestWithDefaults

`func NewLicensesUpdateInstancePostRequestWithDefaults() *LicensesUpdateInstancePostRequest`

NewLicensesUpdateInstancePostRequestWithDefaults instantiates a new LicensesUpdateInstancePostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInstanceName

`func (o *LicensesUpdateInstancePostRequest) GetInstanceName() string`

GetInstanceName returns the InstanceName field if non-nil, zero value otherwise.

### GetInstanceNameOk

`func (o *LicensesUpdateInstancePostRequest) GetInstanceNameOk() (*string, bool)`

GetInstanceNameOk returns a tuple with the InstanceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceName

`func (o *LicensesUpdateInstancePostRequest) SetInstanceName(v string)`

SetInstanceName sets InstanceName field to given value.

### HasInstanceName

`func (o *LicensesUpdateInstancePostRequest) HasInstanceName() bool`

HasInstanceName returns a boolean if a field has been set.

### GetIpAddress

`func (o *LicensesUpdateInstancePostRequest) GetIpAddress() string`

GetIpAddress returns the IpAddress field if non-nil, zero value otherwise.

### GetIpAddressOk

`func (o *LicensesUpdateInstancePostRequest) GetIpAddressOk() (*string, bool)`

GetIpAddressOk returns a tuple with the IpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpAddress

`func (o *LicensesUpdateInstancePostRequest) SetIpAddress(v string)`

SetIpAddress sets IpAddress field to given value.

### HasIpAddress

`func (o *LicensesUpdateInstancePostRequest) HasIpAddress() bool`

HasIpAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


