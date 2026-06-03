# CreateApiKeyDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | The user-friendly name of the API key. | 
**AllowWrite** | Pointer to **bool** | Whether the API key is allowed to make mutating write requests. | [optional] [default to true]

## Methods

### NewCreateApiKeyDto

`func NewCreateApiKeyDto(name string, ) *CreateApiKeyDto`

NewCreateApiKeyDto instantiates a new CreateApiKeyDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateApiKeyDtoWithDefaults

`func NewCreateApiKeyDtoWithDefaults() *CreateApiKeyDto`

NewCreateApiKeyDtoWithDefaults instantiates a new CreateApiKeyDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateApiKeyDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateApiKeyDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateApiKeyDto) SetName(v string)`

SetName sets Name field to given value.


### GetAllowWrite

`func (o *CreateApiKeyDto) GetAllowWrite() bool`

GetAllowWrite returns the AllowWrite field if non-nil, zero value otherwise.

### GetAllowWriteOk

`func (o *CreateApiKeyDto) GetAllowWriteOk() (*bool, bool)`

GetAllowWriteOk returns a tuple with the AllowWrite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowWrite

`func (o *CreateApiKeyDto) SetAllowWrite(v bool)`

SetAllowWrite sets AllowWrite field to given value.

### HasAllowWrite

`func (o *CreateApiKeyDto) HasAllowWrite() bool`

HasAllowWrite returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


