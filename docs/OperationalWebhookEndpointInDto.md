# OperationalWebhookEndpointInDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | The URL to send webhook events to. | 
**Description** | Pointer to **string** | Optional description for the endpoint. | [optional] 
**Disabled** | Pointer to **bool** | Whether the endpoint is disabled. | [optional] [default to false]
**FilterTypes** | Pointer to **[]string** | The operational event types this endpoint will receive. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Metadata key-value pairs associated with the endpoint. | [optional] 
**Secret** | Pointer to **string** | Optional custom endpoint signing secret (base64 encoded random bytes optionally prefixed with whsec_). If not set, the server will generate one. | [optional] 
**ThrottleRate** | Pointer to **float32** | Maximum messages per second to send to this endpoint (outgoing messages will be throttled to this rate). | [optional] 
**Uid** | Pointer to **string** | Optional unique user-defined identifier for the endpoint. | [optional] 

## Methods

### NewOperationalWebhookEndpointInDto

`func NewOperationalWebhookEndpointInDto(url string, ) *OperationalWebhookEndpointInDto`

NewOperationalWebhookEndpointInDto instantiates a new OperationalWebhookEndpointInDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationalWebhookEndpointInDtoWithDefaults

`func NewOperationalWebhookEndpointInDtoWithDefaults() *OperationalWebhookEndpointInDto`

NewOperationalWebhookEndpointInDtoWithDefaults instantiates a new OperationalWebhookEndpointInDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *OperationalWebhookEndpointInDto) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *OperationalWebhookEndpointInDto) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *OperationalWebhookEndpointInDto) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetDescription

`func (o *OperationalWebhookEndpointInDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *OperationalWebhookEndpointInDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *OperationalWebhookEndpointInDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *OperationalWebhookEndpointInDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDisabled

`func (o *OperationalWebhookEndpointInDto) GetDisabled() bool`

GetDisabled returns the Disabled field if non-nil, zero value otherwise.

### GetDisabledOk

`func (o *OperationalWebhookEndpointInDto) GetDisabledOk() (*bool, bool)`

GetDisabledOk returns a tuple with the Disabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabled

`func (o *OperationalWebhookEndpointInDto) SetDisabled(v bool)`

SetDisabled sets Disabled field to given value.

### HasDisabled

`func (o *OperationalWebhookEndpointInDto) HasDisabled() bool`

HasDisabled returns a boolean if a field has been set.

### GetFilterTypes

`func (o *OperationalWebhookEndpointInDto) GetFilterTypes() []string`

GetFilterTypes returns the FilterTypes field if non-nil, zero value otherwise.

### GetFilterTypesOk

`func (o *OperationalWebhookEndpointInDto) GetFilterTypesOk() (*[]string, bool)`

GetFilterTypesOk returns a tuple with the FilterTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterTypes

`func (o *OperationalWebhookEndpointInDto) SetFilterTypes(v []string)`

SetFilterTypes sets FilterTypes field to given value.

### HasFilterTypes

`func (o *OperationalWebhookEndpointInDto) HasFilterTypes() bool`

HasFilterTypes returns a boolean if a field has been set.

### GetMetadata

`func (o *OperationalWebhookEndpointInDto) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *OperationalWebhookEndpointInDto) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *OperationalWebhookEndpointInDto) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *OperationalWebhookEndpointInDto) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetSecret

`func (o *OperationalWebhookEndpointInDto) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *OperationalWebhookEndpointInDto) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *OperationalWebhookEndpointInDto) SetSecret(v string)`

SetSecret sets Secret field to given value.

### HasSecret

`func (o *OperationalWebhookEndpointInDto) HasSecret() bool`

HasSecret returns a boolean if a field has been set.

### GetThrottleRate

`func (o *OperationalWebhookEndpointInDto) GetThrottleRate() float32`

GetThrottleRate returns the ThrottleRate field if non-nil, zero value otherwise.

### GetThrottleRateOk

`func (o *OperationalWebhookEndpointInDto) GetThrottleRateOk() (*float32, bool)`

GetThrottleRateOk returns a tuple with the ThrottleRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThrottleRate

`func (o *OperationalWebhookEndpointInDto) SetThrottleRate(v float32)`

SetThrottleRate sets ThrottleRate field to given value.

### HasThrottleRate

`func (o *OperationalWebhookEndpointInDto) HasThrottleRate() bool`

HasThrottleRate returns a boolean if a field has been set.

### GetUid

`func (o *OperationalWebhookEndpointInDto) GetUid() string`

GetUid returns the Uid field if non-nil, zero value otherwise.

### GetUidOk

`func (o *OperationalWebhookEndpointInDto) GetUidOk() (*string, bool)`

GetUidOk returns a tuple with the Uid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUid

`func (o *OperationalWebhookEndpointInDto) SetUid(v string)`

SetUid sets Uid field to given value.

### HasUid

`func (o *OperationalWebhookEndpointInDto) HasUid() bool`

HasUid returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


