# WebhookEndpointResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Url** | **string** |  | 
**Description** | **string** |  | 
**Events** | **[]string** |  | 
**Status** | **string** |  | 
**MaskedSecret** | **string** | Masked signing secret for verification. | 
**Secret** | Pointer to **string** | Raw signing secret (only returned once during creation). | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewWebhookEndpointResponseDto

`func NewWebhookEndpointResponseDto(id string, url string, description string, events []string, status string, maskedSecret string, createdAt time.Time, ) *WebhookEndpointResponseDto`

NewWebhookEndpointResponseDto instantiates a new WebhookEndpointResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookEndpointResponseDtoWithDefaults

`func NewWebhookEndpointResponseDtoWithDefaults() *WebhookEndpointResponseDto`

NewWebhookEndpointResponseDtoWithDefaults instantiates a new WebhookEndpointResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WebhookEndpointResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WebhookEndpointResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WebhookEndpointResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetUrl

`func (o *WebhookEndpointResponseDto) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *WebhookEndpointResponseDto) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *WebhookEndpointResponseDto) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetDescription

`func (o *WebhookEndpointResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *WebhookEndpointResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *WebhookEndpointResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetEvents

`func (o *WebhookEndpointResponseDto) GetEvents() []string`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *WebhookEndpointResponseDto) GetEventsOk() (*[]string, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *WebhookEndpointResponseDto) SetEvents(v []string)`

SetEvents sets Events field to given value.


### GetStatus

`func (o *WebhookEndpointResponseDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WebhookEndpointResponseDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WebhookEndpointResponseDto) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetMaskedSecret

`func (o *WebhookEndpointResponseDto) GetMaskedSecret() string`

GetMaskedSecret returns the MaskedSecret field if non-nil, zero value otherwise.

### GetMaskedSecretOk

`func (o *WebhookEndpointResponseDto) GetMaskedSecretOk() (*string, bool)`

GetMaskedSecretOk returns a tuple with the MaskedSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaskedSecret

`func (o *WebhookEndpointResponseDto) SetMaskedSecret(v string)`

SetMaskedSecret sets MaskedSecret field to given value.


### GetSecret

`func (o *WebhookEndpointResponseDto) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *WebhookEndpointResponseDto) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *WebhookEndpointResponseDto) SetSecret(v string)`

SetSecret sets Secret field to given value.

### HasSecret

`func (o *WebhookEndpointResponseDto) HasSecret() bool`

HasSecret returns a boolean if a field has been set.

### GetCreatedAt

`func (o *WebhookEndpointResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WebhookEndpointResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WebhookEndpointResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *WebhookEndpointResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *WebhookEndpointResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *WebhookEndpointResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *WebhookEndpointResponseDto) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


