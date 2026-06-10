# UpdateWebhookEndpointDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | Pointer to **string** | The URL to send webhook events to. | [optional] 
**Description** | Pointer to **string** | Optional description for the webhook endpoint. | [optional] 
**Events** | Pointer to **[]string** | The list of subscribed event types. | [optional] 
**Status** | Pointer to **string** | The status of the webhook endpoint. | [optional] 

## Methods

### NewUpdateWebhookEndpointDto

`func NewUpdateWebhookEndpointDto() *UpdateWebhookEndpointDto`

NewUpdateWebhookEndpointDto instantiates a new UpdateWebhookEndpointDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateWebhookEndpointDtoWithDefaults

`func NewUpdateWebhookEndpointDtoWithDefaults() *UpdateWebhookEndpointDto`

NewUpdateWebhookEndpointDtoWithDefaults instantiates a new UpdateWebhookEndpointDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *UpdateWebhookEndpointDto) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *UpdateWebhookEndpointDto) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *UpdateWebhookEndpointDto) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *UpdateWebhookEndpointDto) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateWebhookEndpointDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateWebhookEndpointDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateWebhookEndpointDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateWebhookEndpointDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEvents

`func (o *UpdateWebhookEndpointDto) GetEvents() []string`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *UpdateWebhookEndpointDto) GetEventsOk() (*[]string, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *UpdateWebhookEndpointDto) SetEvents(v []string)`

SetEvents sets Events field to given value.

### HasEvents

`func (o *UpdateWebhookEndpointDto) HasEvents() bool`

HasEvents returns a boolean if a field has been set.

### GetStatus

`func (o *UpdateWebhookEndpointDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UpdateWebhookEndpointDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UpdateWebhookEndpointDto) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *UpdateWebhookEndpointDto) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


