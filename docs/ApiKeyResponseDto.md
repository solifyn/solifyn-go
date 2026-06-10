# ApiKeyResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**Prefix** | **string** |  | 
**Status** | **string** |  | 
**AllowWrite** | **bool** |  | 
**ApiKey** | Pointer to **string** | The raw API key. Only returned once during creation. | [optional] 
**ExpiresAt** | **time.Time** |  | 
**LastUsedAt** | Pointer to **map[string]interface{}** |  | [optional] 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewApiKeyResponseDto

`func NewApiKeyResponseDto(id string, name string, prefix string, status string, allowWrite bool, expiresAt time.Time, createdAt time.Time, ) *ApiKeyResponseDto`

NewApiKeyResponseDto instantiates a new ApiKeyResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiKeyResponseDtoWithDefaults

`func NewApiKeyResponseDtoWithDefaults() *ApiKeyResponseDto`

NewApiKeyResponseDtoWithDefaults instantiates a new ApiKeyResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ApiKeyResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ApiKeyResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ApiKeyResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ApiKeyResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ApiKeyResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ApiKeyResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetPrefix

`func (o *ApiKeyResponseDto) GetPrefix() string`

GetPrefix returns the Prefix field if non-nil, zero value otherwise.

### GetPrefixOk

`func (o *ApiKeyResponseDto) GetPrefixOk() (*string, bool)`

GetPrefixOk returns a tuple with the Prefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefix

`func (o *ApiKeyResponseDto) SetPrefix(v string)`

SetPrefix sets Prefix field to given value.


### GetStatus

`func (o *ApiKeyResponseDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ApiKeyResponseDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ApiKeyResponseDto) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAllowWrite

`func (o *ApiKeyResponseDto) GetAllowWrite() bool`

GetAllowWrite returns the AllowWrite field if non-nil, zero value otherwise.

### GetAllowWriteOk

`func (o *ApiKeyResponseDto) GetAllowWriteOk() (*bool, bool)`

GetAllowWriteOk returns a tuple with the AllowWrite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowWrite

`func (o *ApiKeyResponseDto) SetAllowWrite(v bool)`

SetAllowWrite sets AllowWrite field to given value.


### GetApiKey

`func (o *ApiKeyResponseDto) GetApiKey() string`

GetApiKey returns the ApiKey field if non-nil, zero value otherwise.

### GetApiKeyOk

`func (o *ApiKeyResponseDto) GetApiKeyOk() (*string, bool)`

GetApiKeyOk returns a tuple with the ApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKey

`func (o *ApiKeyResponseDto) SetApiKey(v string)`

SetApiKey sets ApiKey field to given value.

### HasApiKey

`func (o *ApiKeyResponseDto) HasApiKey() bool`

HasApiKey returns a boolean if a field has been set.

### GetExpiresAt

`func (o *ApiKeyResponseDto) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *ApiKeyResponseDto) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *ApiKeyResponseDto) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetLastUsedAt

`func (o *ApiKeyResponseDto) GetLastUsedAt() map[string]interface{}`

GetLastUsedAt returns the LastUsedAt field if non-nil, zero value otherwise.

### GetLastUsedAtOk

`func (o *ApiKeyResponseDto) GetLastUsedAtOk() (*map[string]interface{}, bool)`

GetLastUsedAtOk returns a tuple with the LastUsedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsedAt

`func (o *ApiKeyResponseDto) SetLastUsedAt(v map[string]interface{})`

SetLastUsedAt sets LastUsedAt field to given value.

### HasLastUsedAt

`func (o *ApiKeyResponseDto) HasLastUsedAt() bool`

HasLastUsedAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ApiKeyResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ApiKeyResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ApiKeyResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


