# MeterUsageEventDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique usage event ID. | 
**MeterId** | **string** | The meter ID this event belongs to. | 
**CustomerId** | **string** | The customer ID associated with the usage event. | 
**Value** | **float32** | Numeric usage value recorded for the event. | 
**Metadata** | Pointer to **map[string]interface{}** | Optional event metadata. | [optional] 
**Timestamp** | **time.Time** | Timestamp when the usage event occurred. | 
**ProcessedAt** | **time.Time** | Timestamp when the usage event was processed. | 

## Methods

### NewMeterUsageEventDto

`func NewMeterUsageEventDto(id string, meterId string, customerId string, value float32, timestamp time.Time, processedAt time.Time, ) *MeterUsageEventDto`

NewMeterUsageEventDto instantiates a new MeterUsageEventDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMeterUsageEventDtoWithDefaults

`func NewMeterUsageEventDtoWithDefaults() *MeterUsageEventDto`

NewMeterUsageEventDtoWithDefaults instantiates a new MeterUsageEventDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MeterUsageEventDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MeterUsageEventDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MeterUsageEventDto) SetId(v string)`

SetId sets Id field to given value.


### GetMeterId

`func (o *MeterUsageEventDto) GetMeterId() string`

GetMeterId returns the MeterId field if non-nil, zero value otherwise.

### GetMeterIdOk

`func (o *MeterUsageEventDto) GetMeterIdOk() (*string, bool)`

GetMeterIdOk returns a tuple with the MeterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeterId

`func (o *MeterUsageEventDto) SetMeterId(v string)`

SetMeterId sets MeterId field to given value.


### GetCustomerId

`func (o *MeterUsageEventDto) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *MeterUsageEventDto) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *MeterUsageEventDto) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.


### GetValue

`func (o *MeterUsageEventDto) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *MeterUsageEventDto) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *MeterUsageEventDto) SetValue(v float32)`

SetValue sets Value field to given value.


### GetMetadata

`func (o *MeterUsageEventDto) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *MeterUsageEventDto) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *MeterUsageEventDto) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *MeterUsageEventDto) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *MeterUsageEventDto) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *MeterUsageEventDto) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetTimestamp

`func (o *MeterUsageEventDto) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *MeterUsageEventDto) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *MeterUsageEventDto) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetProcessedAt

`func (o *MeterUsageEventDto) GetProcessedAt() time.Time`

GetProcessedAt returns the ProcessedAt field if non-nil, zero value otherwise.

### GetProcessedAtOk

`func (o *MeterUsageEventDto) GetProcessedAtOk() (*time.Time, bool)`

GetProcessedAtOk returns a tuple with the ProcessedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedAt

`func (o *MeterUsageEventDto) SetProcessedAt(v time.Time)`

SetProcessedAt sets ProcessedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


