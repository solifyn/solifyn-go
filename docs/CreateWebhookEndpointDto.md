# CreateWebhookEndpointDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | The URL to send webhook events to. | 
**Description** | Pointer to **string** | Optional description for the webhook endpoint. | [optional] 
**Events** | **[]string** | The list of subscribed event types. | 

## Methods

### NewCreateWebhookEndpointDto

`func NewCreateWebhookEndpointDto(url string, events []string, ) *CreateWebhookEndpointDto`

NewCreateWebhookEndpointDto instantiates a new CreateWebhookEndpointDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWebhookEndpointDtoWithDefaults

`func NewCreateWebhookEndpointDtoWithDefaults() *CreateWebhookEndpointDto`

NewCreateWebhookEndpointDtoWithDefaults instantiates a new CreateWebhookEndpointDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *CreateWebhookEndpointDto) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CreateWebhookEndpointDto) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CreateWebhookEndpointDto) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetDescription

`func (o *CreateWebhookEndpointDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateWebhookEndpointDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateWebhookEndpointDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateWebhookEndpointDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEvents

`func (o *CreateWebhookEndpointDto) GetEvents() []string`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *CreateWebhookEndpointDto) GetEventsOk() (*[]string, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *CreateWebhookEndpointDto) SetEvents(v []string)`

SetEvents sets Events field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


