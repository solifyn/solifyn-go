# MeterEventsResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MeterId** | **string** | The unique meter ID. | 
**Items** | [**[]MeterUsageEventDto**](MeterUsageEventDto.md) | List of recent usage events. | 
**Count** | **float32** | Number of returned usage events. | 

## Methods

### NewMeterEventsResponseDto

`func NewMeterEventsResponseDto(meterId string, items []MeterUsageEventDto, count float32, ) *MeterEventsResponseDto`

NewMeterEventsResponseDto instantiates a new MeterEventsResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMeterEventsResponseDtoWithDefaults

`func NewMeterEventsResponseDtoWithDefaults() *MeterEventsResponseDto`

NewMeterEventsResponseDtoWithDefaults instantiates a new MeterEventsResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMeterId

`func (o *MeterEventsResponseDto) GetMeterId() string`

GetMeterId returns the MeterId field if non-nil, zero value otherwise.

### GetMeterIdOk

`func (o *MeterEventsResponseDto) GetMeterIdOk() (*string, bool)`

GetMeterIdOk returns a tuple with the MeterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeterId

`func (o *MeterEventsResponseDto) SetMeterId(v string)`

SetMeterId sets MeterId field to given value.


### GetItems

`func (o *MeterEventsResponseDto) GetItems() []MeterUsageEventDto`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *MeterEventsResponseDto) GetItemsOk() (*[]MeterUsageEventDto, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *MeterEventsResponseDto) SetItems(v []MeterUsageEventDto)`

SetItems sets Items field to given value.


### GetCount

`func (o *MeterEventsResponseDto) GetCount() float32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *MeterEventsResponseDto) GetCountOk() (*float32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *MeterEventsResponseDto) SetCount(v float32)`

SetCount sets Count field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


