# OperationalWebhookEndpointListResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]OperationalWebhookEndpointResponseDto**](OperationalWebhookEndpointResponseDto.md) |  | 
**Done** | **bool** |  | 
**Iterator** | Pointer to **map[string]interface{}** |  | [optional] 
**PrevIterator** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewOperationalWebhookEndpointListResponseDto

`func NewOperationalWebhookEndpointListResponseDto(data []OperationalWebhookEndpointResponseDto, done bool, ) *OperationalWebhookEndpointListResponseDto`

NewOperationalWebhookEndpointListResponseDto instantiates a new OperationalWebhookEndpointListResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationalWebhookEndpointListResponseDtoWithDefaults

`func NewOperationalWebhookEndpointListResponseDtoWithDefaults() *OperationalWebhookEndpointListResponseDto`

NewOperationalWebhookEndpointListResponseDtoWithDefaults instantiates a new OperationalWebhookEndpointListResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *OperationalWebhookEndpointListResponseDto) GetData() []OperationalWebhookEndpointResponseDto`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *OperationalWebhookEndpointListResponseDto) GetDataOk() (*[]OperationalWebhookEndpointResponseDto, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *OperationalWebhookEndpointListResponseDto) SetData(v []OperationalWebhookEndpointResponseDto)`

SetData sets Data field to given value.


### GetDone

`func (o *OperationalWebhookEndpointListResponseDto) GetDone() bool`

GetDone returns the Done field if non-nil, zero value otherwise.

### GetDoneOk

`func (o *OperationalWebhookEndpointListResponseDto) GetDoneOk() (*bool, bool)`

GetDoneOk returns a tuple with the Done field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDone

`func (o *OperationalWebhookEndpointListResponseDto) SetDone(v bool)`

SetDone sets Done field to given value.


### GetIterator

`func (o *OperationalWebhookEndpointListResponseDto) GetIterator() map[string]interface{}`

GetIterator returns the Iterator field if non-nil, zero value otherwise.

### GetIteratorOk

`func (o *OperationalWebhookEndpointListResponseDto) GetIteratorOk() (*map[string]interface{}, bool)`

GetIteratorOk returns a tuple with the Iterator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIterator

`func (o *OperationalWebhookEndpointListResponseDto) SetIterator(v map[string]interface{})`

SetIterator sets Iterator field to given value.

### HasIterator

`func (o *OperationalWebhookEndpointListResponseDto) HasIterator() bool`

HasIterator returns a boolean if a field has been set.

### GetPrevIterator

`func (o *OperationalWebhookEndpointListResponseDto) GetPrevIterator() map[string]interface{}`

GetPrevIterator returns the PrevIterator field if non-nil, zero value otherwise.

### GetPrevIteratorOk

`func (o *OperationalWebhookEndpointListResponseDto) GetPrevIteratorOk() (*map[string]interface{}, bool)`

GetPrevIteratorOk returns a tuple with the PrevIterator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevIterator

`func (o *OperationalWebhookEndpointListResponseDto) SetPrevIterator(v map[string]interface{})`

SetPrevIterator sets PrevIterator field to given value.

### HasPrevIterator

`func (o *OperationalWebhookEndpointListResponseDto) HasPrevIterator() bool`

HasPrevIterator returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


