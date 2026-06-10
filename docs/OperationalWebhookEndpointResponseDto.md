# OperationalWebhookEndpointResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Url** | **string** |  | 
**Description** | **string** |  | 
**Disabled** | **bool** |  | 
**FilterTypes** | **[]string** |  | 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 
**ThrottleRate** | **float32** |  | 
**Uid** | Pointer to **map[string]interface{}** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 
**Secret** | Pointer to **string** | The endpoint&#39;s raw secret (only returned on POST creation). | [optional] 

## Methods

### NewOperationalWebhookEndpointResponseDto

`func NewOperationalWebhookEndpointResponseDto(id string, url string, description string, disabled bool, filterTypes []string, throttleRate float32, createdAt time.Time, updatedAt time.Time, ) *OperationalWebhookEndpointResponseDto`

NewOperationalWebhookEndpointResponseDto instantiates a new OperationalWebhookEndpointResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationalWebhookEndpointResponseDtoWithDefaults

`func NewOperationalWebhookEndpointResponseDtoWithDefaults() *OperationalWebhookEndpointResponseDto`

NewOperationalWebhookEndpointResponseDtoWithDefaults instantiates a new OperationalWebhookEndpointResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperationalWebhookEndpointResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperationalWebhookEndpointResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperationalWebhookEndpointResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetUrl

`func (o *OperationalWebhookEndpointResponseDto) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *OperationalWebhookEndpointResponseDto) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *OperationalWebhookEndpointResponseDto) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetDescription

`func (o *OperationalWebhookEndpointResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *OperationalWebhookEndpointResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *OperationalWebhookEndpointResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetDisabled

`func (o *OperationalWebhookEndpointResponseDto) GetDisabled() bool`

GetDisabled returns the Disabled field if non-nil, zero value otherwise.

### GetDisabledOk

`func (o *OperationalWebhookEndpointResponseDto) GetDisabledOk() (*bool, bool)`

GetDisabledOk returns a tuple with the Disabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabled

`func (o *OperationalWebhookEndpointResponseDto) SetDisabled(v bool)`

SetDisabled sets Disabled field to given value.


### GetFilterTypes

`func (o *OperationalWebhookEndpointResponseDto) GetFilterTypes() []string`

GetFilterTypes returns the FilterTypes field if non-nil, zero value otherwise.

### GetFilterTypesOk

`func (o *OperationalWebhookEndpointResponseDto) GetFilterTypesOk() (*[]string, bool)`

GetFilterTypesOk returns a tuple with the FilterTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterTypes

`func (o *OperationalWebhookEndpointResponseDto) SetFilterTypes(v []string)`

SetFilterTypes sets FilterTypes field to given value.


### GetMetadata

`func (o *OperationalWebhookEndpointResponseDto) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *OperationalWebhookEndpointResponseDto) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *OperationalWebhookEndpointResponseDto) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *OperationalWebhookEndpointResponseDto) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetThrottleRate

`func (o *OperationalWebhookEndpointResponseDto) GetThrottleRate() float32`

GetThrottleRate returns the ThrottleRate field if non-nil, zero value otherwise.

### GetThrottleRateOk

`func (o *OperationalWebhookEndpointResponseDto) GetThrottleRateOk() (*float32, bool)`

GetThrottleRateOk returns a tuple with the ThrottleRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThrottleRate

`func (o *OperationalWebhookEndpointResponseDto) SetThrottleRate(v float32)`

SetThrottleRate sets ThrottleRate field to given value.


### GetUid

`func (o *OperationalWebhookEndpointResponseDto) GetUid() map[string]interface{}`

GetUid returns the Uid field if non-nil, zero value otherwise.

### GetUidOk

`func (o *OperationalWebhookEndpointResponseDto) GetUidOk() (*map[string]interface{}, bool)`

GetUidOk returns a tuple with the Uid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUid

`func (o *OperationalWebhookEndpointResponseDto) SetUid(v map[string]interface{})`

SetUid sets Uid field to given value.

### HasUid

`func (o *OperationalWebhookEndpointResponseDto) HasUid() bool`

HasUid returns a boolean if a field has been set.

### GetCreatedAt

`func (o *OperationalWebhookEndpointResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperationalWebhookEndpointResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperationalWebhookEndpointResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *OperationalWebhookEndpointResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperationalWebhookEndpointResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperationalWebhookEndpointResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetSecret

`func (o *OperationalWebhookEndpointResponseDto) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *OperationalWebhookEndpointResponseDto) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *OperationalWebhookEndpointResponseDto) SetSecret(v string)`

SetSecret sets Secret field to given value.

### HasSecret

`func (o *OperationalWebhookEndpointResponseDto) HasSecret() bool`

HasSecret returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


