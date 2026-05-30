# UpdateCustomerDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | The customer friendly full name | [optional] 
**Phone** | Pointer to **string** | The customer telephone/phone number | [optional] 
**Username** | Pointer to **string** | The username of the customer (e.g. Discord, Whop) | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Custom key-value metadata associated with the customer | [optional] 

## Methods

### NewUpdateCustomerDto

`func NewUpdateCustomerDto() *UpdateCustomerDto`

NewUpdateCustomerDto instantiates a new UpdateCustomerDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateCustomerDtoWithDefaults

`func NewUpdateCustomerDtoWithDefaults() *UpdateCustomerDto`

NewUpdateCustomerDtoWithDefaults instantiates a new UpdateCustomerDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateCustomerDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateCustomerDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateCustomerDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateCustomerDto) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPhone

`func (o *UpdateCustomerDto) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *UpdateCustomerDto) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *UpdateCustomerDto) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *UpdateCustomerDto) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetUsername

`func (o *UpdateCustomerDto) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *UpdateCustomerDto) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *UpdateCustomerDto) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *UpdateCustomerDto) HasUsername() bool`

HasUsername returns a boolean if a field has been set.

### GetMetadata

`func (o *UpdateCustomerDto) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *UpdateCustomerDto) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *UpdateCustomerDto) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *UpdateCustomerDto) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


