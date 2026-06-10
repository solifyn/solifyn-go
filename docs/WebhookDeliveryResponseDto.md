# WebhookDeliveryResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**EndpointId** | **string** |  | 
**Event** | **string** |  | 
**Payload** | **map[string]interface{}** |  | 
**ResponseStatus** | Pointer to **map[string]interface{}** |  | [optional] 
**ResponseBody** | Pointer to **map[string]interface{}** |  | [optional] 
**DurationMs** | Pointer to **map[string]interface{}** |  | [optional] 
**Status** | **string** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewWebhookDeliveryResponseDto

`func NewWebhookDeliveryResponseDto(id string, endpointId string, event string, payload map[string]interface{}, status string, createdAt time.Time, ) *WebhookDeliveryResponseDto`

NewWebhookDeliveryResponseDto instantiates a new WebhookDeliveryResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookDeliveryResponseDtoWithDefaults

`func NewWebhookDeliveryResponseDtoWithDefaults() *WebhookDeliveryResponseDto`

NewWebhookDeliveryResponseDtoWithDefaults instantiates a new WebhookDeliveryResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WebhookDeliveryResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WebhookDeliveryResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WebhookDeliveryResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetEndpointId

`func (o *WebhookDeliveryResponseDto) GetEndpointId() string`

GetEndpointId returns the EndpointId field if non-nil, zero value otherwise.

### GetEndpointIdOk

`func (o *WebhookDeliveryResponseDto) GetEndpointIdOk() (*string, bool)`

GetEndpointIdOk returns a tuple with the EndpointId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointId

`func (o *WebhookDeliveryResponseDto) SetEndpointId(v string)`

SetEndpointId sets EndpointId field to given value.


### GetEvent

`func (o *WebhookDeliveryResponseDto) GetEvent() string`

GetEvent returns the Event field if non-nil, zero value otherwise.

### GetEventOk

`func (o *WebhookDeliveryResponseDto) GetEventOk() (*string, bool)`

GetEventOk returns a tuple with the Event field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvent

`func (o *WebhookDeliveryResponseDto) SetEvent(v string)`

SetEvent sets Event field to given value.


### GetPayload

`func (o *WebhookDeliveryResponseDto) GetPayload() map[string]interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *WebhookDeliveryResponseDto) GetPayloadOk() (*map[string]interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *WebhookDeliveryResponseDto) SetPayload(v map[string]interface{})`

SetPayload sets Payload field to given value.


### GetResponseStatus

`func (o *WebhookDeliveryResponseDto) GetResponseStatus() map[string]interface{}`

GetResponseStatus returns the ResponseStatus field if non-nil, zero value otherwise.

### GetResponseStatusOk

`func (o *WebhookDeliveryResponseDto) GetResponseStatusOk() (*map[string]interface{}, bool)`

GetResponseStatusOk returns a tuple with the ResponseStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseStatus

`func (o *WebhookDeliveryResponseDto) SetResponseStatus(v map[string]interface{})`

SetResponseStatus sets ResponseStatus field to given value.

### HasResponseStatus

`func (o *WebhookDeliveryResponseDto) HasResponseStatus() bool`

HasResponseStatus returns a boolean if a field has been set.

### GetResponseBody

`func (o *WebhookDeliveryResponseDto) GetResponseBody() map[string]interface{}`

GetResponseBody returns the ResponseBody field if non-nil, zero value otherwise.

### GetResponseBodyOk

`func (o *WebhookDeliveryResponseDto) GetResponseBodyOk() (*map[string]interface{}, bool)`

GetResponseBodyOk returns a tuple with the ResponseBody field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseBody

`func (o *WebhookDeliveryResponseDto) SetResponseBody(v map[string]interface{})`

SetResponseBody sets ResponseBody field to given value.

### HasResponseBody

`func (o *WebhookDeliveryResponseDto) HasResponseBody() bool`

HasResponseBody returns a boolean if a field has been set.

### GetDurationMs

`func (o *WebhookDeliveryResponseDto) GetDurationMs() map[string]interface{}`

GetDurationMs returns the DurationMs field if non-nil, zero value otherwise.

### GetDurationMsOk

`func (o *WebhookDeliveryResponseDto) GetDurationMsOk() (*map[string]interface{}, bool)`

GetDurationMsOk returns a tuple with the DurationMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationMs

`func (o *WebhookDeliveryResponseDto) SetDurationMs(v map[string]interface{})`

SetDurationMs sets DurationMs field to given value.

### HasDurationMs

`func (o *WebhookDeliveryResponseDto) HasDurationMs() bool`

HasDurationMs returns a boolean if a field has been set.

### GetStatus

`func (o *WebhookDeliveryResponseDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WebhookDeliveryResponseDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WebhookDeliveryResponseDto) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *WebhookDeliveryResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WebhookDeliveryResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WebhookDeliveryResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


