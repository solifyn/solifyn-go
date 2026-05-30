# UpdateInstanceDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InstanceName** | Pointer to **string** | The updated friendly name of the instance | [optional] 
**IpAddress** | Pointer to **string** | The updated IP address of the client device | [optional] 

## Methods

### NewUpdateInstanceDto

`func NewUpdateInstanceDto() *UpdateInstanceDto`

NewUpdateInstanceDto instantiates a new UpdateInstanceDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateInstanceDtoWithDefaults

`func NewUpdateInstanceDtoWithDefaults() *UpdateInstanceDto`

NewUpdateInstanceDtoWithDefaults instantiates a new UpdateInstanceDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInstanceName

`func (o *UpdateInstanceDto) GetInstanceName() string`

GetInstanceName returns the InstanceName field if non-nil, zero value otherwise.

### GetInstanceNameOk

`func (o *UpdateInstanceDto) GetInstanceNameOk() (*string, bool)`

GetInstanceNameOk returns a tuple with the InstanceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceName

`func (o *UpdateInstanceDto) SetInstanceName(v string)`

SetInstanceName sets InstanceName field to given value.

### HasInstanceName

`func (o *UpdateInstanceDto) HasInstanceName() bool`

HasInstanceName returns a boolean if a field has been set.

### GetIpAddress

`func (o *UpdateInstanceDto) GetIpAddress() string`

GetIpAddress returns the IpAddress field if non-nil, zero value otherwise.

### GetIpAddressOk

`func (o *UpdateInstanceDto) GetIpAddressOk() (*string, bool)`

GetIpAddressOk returns a tuple with the IpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpAddress

`func (o *UpdateInstanceDto) SetIpAddress(v string)`

SetIpAddress sets IpAddress field to given value.

### HasIpAddress

`func (o *UpdateInstanceDto) HasIpAddress() bool`

HasIpAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


