# MeterQuantitiesResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MeterId** | **string** | The unique meter ID. | 
**Name** | **string** | Meter display name. | 
**TotalUsage** | **float32** | Total usage within the selected time range. | 
**Costs** | [**[]MeterQuantitiesCostDto**](MeterQuantitiesCostDto.md) | Cost breakdown for products attached to the meter. | 

## Methods

### NewMeterQuantitiesResponseDto

`func NewMeterQuantitiesResponseDto(meterId string, name string, totalUsage float32, costs []MeterQuantitiesCostDto, ) *MeterQuantitiesResponseDto`

NewMeterQuantitiesResponseDto instantiates a new MeterQuantitiesResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMeterQuantitiesResponseDtoWithDefaults

`func NewMeterQuantitiesResponseDtoWithDefaults() *MeterQuantitiesResponseDto`

NewMeterQuantitiesResponseDtoWithDefaults instantiates a new MeterQuantitiesResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMeterId

`func (o *MeterQuantitiesResponseDto) GetMeterId() string`

GetMeterId returns the MeterId field if non-nil, zero value otherwise.

### GetMeterIdOk

`func (o *MeterQuantitiesResponseDto) GetMeterIdOk() (*string, bool)`

GetMeterIdOk returns a tuple with the MeterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeterId

`func (o *MeterQuantitiesResponseDto) SetMeterId(v string)`

SetMeterId sets MeterId field to given value.


### GetName

`func (o *MeterQuantitiesResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *MeterQuantitiesResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *MeterQuantitiesResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetTotalUsage

`func (o *MeterQuantitiesResponseDto) GetTotalUsage() float32`

GetTotalUsage returns the TotalUsage field if non-nil, zero value otherwise.

### GetTotalUsageOk

`func (o *MeterQuantitiesResponseDto) GetTotalUsageOk() (*float32, bool)`

GetTotalUsageOk returns a tuple with the TotalUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalUsage

`func (o *MeterQuantitiesResponseDto) SetTotalUsage(v float32)`

SetTotalUsage sets TotalUsage field to given value.


### GetCosts

`func (o *MeterQuantitiesResponseDto) GetCosts() []MeterQuantitiesCostDto`

GetCosts returns the Costs field if non-nil, zero value otherwise.

### GetCostsOk

`func (o *MeterQuantitiesResponseDto) GetCostsOk() (*[]MeterQuantitiesCostDto, bool)`

GetCostsOk returns a tuple with the Costs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCosts

`func (o *MeterQuantitiesResponseDto) SetCosts(v []MeterQuantitiesCostDto)`

SetCosts sets Costs field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


