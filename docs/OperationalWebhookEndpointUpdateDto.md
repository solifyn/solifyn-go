# OperationalWebhookEndpointUpdateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | The URL to send webhook events to. | 
**Description** | Pointer to **string** | Optional description for the endpoint. | [optional] 
**Disabled** | Pointer to **bool** | Whether the endpoint is disabled. | [optional] 
**FilterTypes** | Pointer to **[]string** | The operational event types this endpoint will receive. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Metadata key-value pairs associated with the endpoint. | [optional] 
**ThrottleRate** | Pointer to **float32** | Maximum messages per second to send to this endpoint. | [optional] 
**Uid** | Pointer to **string** | Optional unique user-defined identifier for the endpoint. | [optional] 

## Methods

### NewOperationalWebhookEndpointUpdateDto

`func NewOperationalWebhookEndpointUpdateDto(url string, ) *OperationalWebhookEndpointUpdateDto`

NewOperationalWebhookEndpointUpdateDto instantiates a new OperationalWebhookEndpointUpdateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationalWebhookEndpointUpdateDtoWithDefaults

`func NewOperationalWebhookEndpointUpdateDtoWithDefaults() *OperationalWebhookEndpointUpdateDto`

NewOperationalWebhookEndpointUpdateDtoWithDefaults instantiates a new OperationalWebhookEndpointUpdateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *OperationalWebhookEndpointUpdateDto) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *OperationalWebhookEndpointUpdateDto) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *OperationalWebhookEndpointUpdateDto) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetDescription

`func (o *OperationalWebhookEndpointUpdateDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *OperationalWebhookEndpointUpdateDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *OperationalWebhookEndpointUpdateDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *OperationalWebhookEndpointUpdateDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDisabled

`func (o *OperationalWebhookEndpointUpdateDto) GetDisabled() bool`

GetDisabled returns the Disabled field if non-nil, zero value otherwise.

### GetDisabledOk

`func (o *OperationalWebhookEndpointUpdateDto) GetDisabledOk() (*bool, bool)`

GetDisabledOk returns a tuple with the Disabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabled

`func (o *OperationalWebhookEndpointUpdateDto) SetDisabled(v bool)`

SetDisabled sets Disabled field to given value.

### HasDisabled

`func (o *OperationalWebhookEndpointUpdateDto) HasDisabled() bool`

HasDisabled returns a boolean if a field has been set.

### GetFilterTypes

`func (o *OperationalWebhookEndpointUpdateDto) GetFilterTypes() []string`

GetFilterTypes returns the FilterTypes field if non-nil, zero value otherwise.

### GetFilterTypesOk

`func (o *OperationalWebhookEndpointUpdateDto) GetFilterTypesOk() (*[]string, bool)`

GetFilterTypesOk returns a tuple with the FilterTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterTypes

`func (o *OperationalWebhookEndpointUpdateDto) SetFilterTypes(v []string)`

SetFilterTypes sets FilterTypes field to given value.

### HasFilterTypes

`func (o *OperationalWebhookEndpointUpdateDto) HasFilterTypes() bool`

HasFilterTypes returns a boolean if a field has been set.

### GetMetadata

`func (o *OperationalWebhookEndpointUpdateDto) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *OperationalWebhookEndpointUpdateDto) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *OperationalWebhookEndpointUpdateDto) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *OperationalWebhookEndpointUpdateDto) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetThrottleRate

`func (o *OperationalWebhookEndpointUpdateDto) GetThrottleRate() float32`

GetThrottleRate returns the ThrottleRate field if non-nil, zero value otherwise.

### GetThrottleRateOk

`func (o *OperationalWebhookEndpointUpdateDto) GetThrottleRateOk() (*float32, bool)`

GetThrottleRateOk returns a tuple with the ThrottleRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThrottleRate

`func (o *OperationalWebhookEndpointUpdateDto) SetThrottleRate(v float32)`

SetThrottleRate sets ThrottleRate field to given value.

### HasThrottleRate

`func (o *OperationalWebhookEndpointUpdateDto) HasThrottleRate() bool`

HasThrottleRate returns a boolean if a field has been set.

### GetUid

`func (o *OperationalWebhookEndpointUpdateDto) GetUid() string`

GetUid returns the Uid field if non-nil, zero value otherwise.

### GetUidOk

`func (o *OperationalWebhookEndpointUpdateDto) GetUidOk() (*string, bool)`

GetUidOk returns a tuple with the Uid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUid

`func (o *OperationalWebhookEndpointUpdateDto) SetUid(v string)`

SetUid sets Uid field to given value.

### HasUid

`func (o *OperationalWebhookEndpointUpdateDto) HasUid() bool`

HasUid returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


