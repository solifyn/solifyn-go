# MeterIngestEventDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventId** | **string** | Unique usage event ID for idempotency. | 
**CustomerId** | **string** | Unique customer ID associated with the event. | 
**EventName** | **string** | Event name that should match a meter eventName. | 
**Value** | Pointer to **float32** | Event quantity value. | [optional] [default to 1]
**Metadata** | Pointer to **map[string]interface{}** | Metadata attached to the usage event. | [optional] 
**Timestamp** | Pointer to **string** | Timestamp of the event in ISO 8601 format. | [optional] 

## Methods

### NewMeterIngestEventDto

`func NewMeterIngestEventDto(eventId string, customerId string, eventName string, ) *MeterIngestEventDto`

NewMeterIngestEventDto instantiates a new MeterIngestEventDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMeterIngestEventDtoWithDefaults

`func NewMeterIngestEventDtoWithDefaults() *MeterIngestEventDto`

NewMeterIngestEventDtoWithDefaults instantiates a new MeterIngestEventDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventId

`func (o *MeterIngestEventDto) GetEventId() string`

GetEventId returns the EventId field if non-nil, zero value otherwise.

### GetEventIdOk

`func (o *MeterIngestEventDto) GetEventIdOk() (*string, bool)`

GetEventIdOk returns a tuple with the EventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventId

`func (o *MeterIngestEventDto) SetEventId(v string)`

SetEventId sets EventId field to given value.


### GetCustomerId

`func (o *MeterIngestEventDto) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *MeterIngestEventDto) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *MeterIngestEventDto) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.


### GetEventName

`func (o *MeterIngestEventDto) GetEventName() string`

GetEventName returns the EventName field if non-nil, zero value otherwise.

### GetEventNameOk

`func (o *MeterIngestEventDto) GetEventNameOk() (*string, bool)`

GetEventNameOk returns a tuple with the EventName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventName

`func (o *MeterIngestEventDto) SetEventName(v string)`

SetEventName sets EventName field to given value.


### GetValue

`func (o *MeterIngestEventDto) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *MeterIngestEventDto) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *MeterIngestEventDto) SetValue(v float32)`

SetValue sets Value field to given value.

### HasValue

`func (o *MeterIngestEventDto) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetMetadata

`func (o *MeterIngestEventDto) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *MeterIngestEventDto) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *MeterIngestEventDto) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *MeterIngestEventDto) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetTimestamp

`func (o *MeterIngestEventDto) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *MeterIngestEventDto) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *MeterIngestEventDto) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *MeterIngestEventDto) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


