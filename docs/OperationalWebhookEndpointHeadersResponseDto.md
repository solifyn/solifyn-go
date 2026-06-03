# OperationalWebhookEndpointHeadersResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Headers** | **map[string]interface{}** | Key-value headers sent with the webhook. | 
**Sensitive** | **[]string** | List of sensitive header keys (e.g. Authorization) that are masked. | 

## Methods

### NewOperationalWebhookEndpointHeadersResponseDto

`func NewOperationalWebhookEndpointHeadersResponseDto(headers map[string]interface{}, sensitive []string, ) *OperationalWebhookEndpointHeadersResponseDto`

NewOperationalWebhookEndpointHeadersResponseDto instantiates a new OperationalWebhookEndpointHeadersResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationalWebhookEndpointHeadersResponseDtoWithDefaults

`func NewOperationalWebhookEndpointHeadersResponseDtoWithDefaults() *OperationalWebhookEndpointHeadersResponseDto`

NewOperationalWebhookEndpointHeadersResponseDtoWithDefaults instantiates a new OperationalWebhookEndpointHeadersResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHeaders

`func (o *OperationalWebhookEndpointHeadersResponseDto) GetHeaders() map[string]interface{}`

GetHeaders returns the Headers field if non-nil, zero value otherwise.

### GetHeadersOk

`func (o *OperationalWebhookEndpointHeadersResponseDto) GetHeadersOk() (*map[string]interface{}, bool)`

GetHeadersOk returns a tuple with the Headers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeaders

`func (o *OperationalWebhookEndpointHeadersResponseDto) SetHeaders(v map[string]interface{})`

SetHeaders sets Headers field to given value.


### GetSensitive

`func (o *OperationalWebhookEndpointHeadersResponseDto) GetSensitive() []string`

GetSensitive returns the Sensitive field if non-nil, zero value otherwise.

### GetSensitiveOk

`func (o *OperationalWebhookEndpointHeadersResponseDto) GetSensitiveOk() (*[]string, bool)`

GetSensitiveOk returns a tuple with the Sensitive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSensitive

`func (o *OperationalWebhookEndpointHeadersResponseDto) SetSensitive(v []string)`

SetSensitive sets Sensitive field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


