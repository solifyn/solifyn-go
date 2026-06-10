# MeterDetailResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique meter ID. | 
**BusinessId** | **string** | The business ID that owns this meter. | 
**Name** | **string** | Meter display name. | 
**Description** | Pointer to **map[string]interface{}** | Meter description. | [optional] 
**EventName** | **string** | The event name tracked by this meter. | 
**AggregationType** | **string** | Aggregation strategy for usage events. | 
**AggregationKey** | Pointer to **map[string]interface{}** | Metadata key used for aggregation. | [optional] 
**Unit** | Pointer to **map[string]interface{}** | Measurement unit label. | [optional] 
**Filters** | Pointer to **map[string]interface{}** | Optional filter definition for advanced matching. | [optional] 
**Archived** | **bool** | Whether the meter is archived. | 
**CreatedAt** | **time.Time** | Creation timestamp. | 
**UpdatedAt** | **time.Time** | Last update timestamp. | 
**UsageEvents** | [**[]MeterUsageEventDto**](MeterUsageEventDto.md) | Most recent usage events recorded for the meter. | 
**TotalUsageEvents** | **float32** | Total usage event count for the meter. | 

## Methods

### NewMeterDetailResponseDto

`func NewMeterDetailResponseDto(id string, businessId string, name string, eventName string, aggregationType string, archived bool, createdAt time.Time, updatedAt time.Time, usageEvents []MeterUsageEventDto, totalUsageEvents float32, ) *MeterDetailResponseDto`

NewMeterDetailResponseDto instantiates a new MeterDetailResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMeterDetailResponseDtoWithDefaults

`func NewMeterDetailResponseDtoWithDefaults() *MeterDetailResponseDto`

NewMeterDetailResponseDtoWithDefaults instantiates a new MeterDetailResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MeterDetailResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MeterDetailResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MeterDetailResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetBusinessId

`func (o *MeterDetailResponseDto) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *MeterDetailResponseDto) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *MeterDetailResponseDto) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetName

`func (o *MeterDetailResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *MeterDetailResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *MeterDetailResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *MeterDetailResponseDto) GetDescription() map[string]interface{}`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *MeterDetailResponseDto) GetDescriptionOk() (*map[string]interface{}, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *MeterDetailResponseDto) SetDescription(v map[string]interface{})`

SetDescription sets Description field to given value.

### HasDescription

`func (o *MeterDetailResponseDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *MeterDetailResponseDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *MeterDetailResponseDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEventName

`func (o *MeterDetailResponseDto) GetEventName() string`

GetEventName returns the EventName field if non-nil, zero value otherwise.

### GetEventNameOk

`func (o *MeterDetailResponseDto) GetEventNameOk() (*string, bool)`

GetEventNameOk returns a tuple with the EventName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventName

`func (o *MeterDetailResponseDto) SetEventName(v string)`

SetEventName sets EventName field to given value.


### GetAggregationType

`func (o *MeterDetailResponseDto) GetAggregationType() string`

GetAggregationType returns the AggregationType field if non-nil, zero value otherwise.

### GetAggregationTypeOk

`func (o *MeterDetailResponseDto) GetAggregationTypeOk() (*string, bool)`

GetAggregationTypeOk returns a tuple with the AggregationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregationType

`func (o *MeterDetailResponseDto) SetAggregationType(v string)`

SetAggregationType sets AggregationType field to given value.


### GetAggregationKey

`func (o *MeterDetailResponseDto) GetAggregationKey() map[string]interface{}`

GetAggregationKey returns the AggregationKey field if non-nil, zero value otherwise.

### GetAggregationKeyOk

`func (o *MeterDetailResponseDto) GetAggregationKeyOk() (*map[string]interface{}, bool)`

GetAggregationKeyOk returns a tuple with the AggregationKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregationKey

`func (o *MeterDetailResponseDto) SetAggregationKey(v map[string]interface{})`

SetAggregationKey sets AggregationKey field to given value.

### HasAggregationKey

`func (o *MeterDetailResponseDto) HasAggregationKey() bool`

HasAggregationKey returns a boolean if a field has been set.

### SetAggregationKeyNil

`func (o *MeterDetailResponseDto) SetAggregationKeyNil(b bool)`

 SetAggregationKeyNil sets the value for AggregationKey to be an explicit nil

### UnsetAggregationKey
`func (o *MeterDetailResponseDto) UnsetAggregationKey()`

UnsetAggregationKey ensures that no value is present for AggregationKey, not even an explicit nil
### GetUnit

`func (o *MeterDetailResponseDto) GetUnit() map[string]interface{}`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *MeterDetailResponseDto) GetUnitOk() (*map[string]interface{}, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *MeterDetailResponseDto) SetUnit(v map[string]interface{})`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *MeterDetailResponseDto) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### SetUnitNil

`func (o *MeterDetailResponseDto) SetUnitNil(b bool)`

 SetUnitNil sets the value for Unit to be an explicit nil

### UnsetUnit
`func (o *MeterDetailResponseDto) UnsetUnit()`

UnsetUnit ensures that no value is present for Unit, not even an explicit nil
### GetFilters

`func (o *MeterDetailResponseDto) GetFilters() map[string]interface{}`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *MeterDetailResponseDto) GetFiltersOk() (*map[string]interface{}, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *MeterDetailResponseDto) SetFilters(v map[string]interface{})`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *MeterDetailResponseDto) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### SetFiltersNil

`func (o *MeterDetailResponseDto) SetFiltersNil(b bool)`

 SetFiltersNil sets the value for Filters to be an explicit nil

### UnsetFilters
`func (o *MeterDetailResponseDto) UnsetFilters()`

UnsetFilters ensures that no value is present for Filters, not even an explicit nil
### GetArchived

`func (o *MeterDetailResponseDto) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *MeterDetailResponseDto) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *MeterDetailResponseDto) SetArchived(v bool)`

SetArchived sets Archived field to given value.


### GetCreatedAt

`func (o *MeterDetailResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MeterDetailResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MeterDetailResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *MeterDetailResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *MeterDetailResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *MeterDetailResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUsageEvents

`func (o *MeterDetailResponseDto) GetUsageEvents() []MeterUsageEventDto`

GetUsageEvents returns the UsageEvents field if non-nil, zero value otherwise.

### GetUsageEventsOk

`func (o *MeterDetailResponseDto) GetUsageEventsOk() (*[]MeterUsageEventDto, bool)`

GetUsageEventsOk returns a tuple with the UsageEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageEvents

`func (o *MeterDetailResponseDto) SetUsageEvents(v []MeterUsageEventDto)`

SetUsageEvents sets UsageEvents field to given value.


### GetTotalUsageEvents

`func (o *MeterDetailResponseDto) GetTotalUsageEvents() float32`

GetTotalUsageEvents returns the TotalUsageEvents field if non-nil, zero value otherwise.

### GetTotalUsageEventsOk

`func (o *MeterDetailResponseDto) GetTotalUsageEventsOk() (*float32, bool)`

GetTotalUsageEventsOk returns a tuple with the TotalUsageEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalUsageEvents

`func (o *MeterDetailResponseDto) SetTotalUsageEvents(v float32)`

SetTotalUsageEvents sets TotalUsageEvents field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


