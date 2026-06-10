# MeterResponseDto

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

## Methods

### NewMeterResponseDto

`func NewMeterResponseDto(id string, businessId string, name string, eventName string, aggregationType string, archived bool, createdAt time.Time, updatedAt time.Time, ) *MeterResponseDto`

NewMeterResponseDto instantiates a new MeterResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMeterResponseDtoWithDefaults

`func NewMeterResponseDtoWithDefaults() *MeterResponseDto`

NewMeterResponseDtoWithDefaults instantiates a new MeterResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MeterResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MeterResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MeterResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetBusinessId

`func (o *MeterResponseDto) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *MeterResponseDto) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *MeterResponseDto) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetName

`func (o *MeterResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *MeterResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *MeterResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *MeterResponseDto) GetDescription() map[string]interface{}`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *MeterResponseDto) GetDescriptionOk() (*map[string]interface{}, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *MeterResponseDto) SetDescription(v map[string]interface{})`

SetDescription sets Description field to given value.

### HasDescription

`func (o *MeterResponseDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *MeterResponseDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *MeterResponseDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEventName

`func (o *MeterResponseDto) GetEventName() string`

GetEventName returns the EventName field if non-nil, zero value otherwise.

### GetEventNameOk

`func (o *MeterResponseDto) GetEventNameOk() (*string, bool)`

GetEventNameOk returns a tuple with the EventName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventName

`func (o *MeterResponseDto) SetEventName(v string)`

SetEventName sets EventName field to given value.


### GetAggregationType

`func (o *MeterResponseDto) GetAggregationType() string`

GetAggregationType returns the AggregationType field if non-nil, zero value otherwise.

### GetAggregationTypeOk

`func (o *MeterResponseDto) GetAggregationTypeOk() (*string, bool)`

GetAggregationTypeOk returns a tuple with the AggregationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregationType

`func (o *MeterResponseDto) SetAggregationType(v string)`

SetAggregationType sets AggregationType field to given value.


### GetAggregationKey

`func (o *MeterResponseDto) GetAggregationKey() map[string]interface{}`

GetAggregationKey returns the AggregationKey field if non-nil, zero value otherwise.

### GetAggregationKeyOk

`func (o *MeterResponseDto) GetAggregationKeyOk() (*map[string]interface{}, bool)`

GetAggregationKeyOk returns a tuple with the AggregationKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregationKey

`func (o *MeterResponseDto) SetAggregationKey(v map[string]interface{})`

SetAggregationKey sets AggregationKey field to given value.

### HasAggregationKey

`func (o *MeterResponseDto) HasAggregationKey() bool`

HasAggregationKey returns a boolean if a field has been set.

### SetAggregationKeyNil

`func (o *MeterResponseDto) SetAggregationKeyNil(b bool)`

 SetAggregationKeyNil sets the value for AggregationKey to be an explicit nil

### UnsetAggregationKey
`func (o *MeterResponseDto) UnsetAggregationKey()`

UnsetAggregationKey ensures that no value is present for AggregationKey, not even an explicit nil
### GetUnit

`func (o *MeterResponseDto) GetUnit() map[string]interface{}`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *MeterResponseDto) GetUnitOk() (*map[string]interface{}, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *MeterResponseDto) SetUnit(v map[string]interface{})`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *MeterResponseDto) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### SetUnitNil

`func (o *MeterResponseDto) SetUnitNil(b bool)`

 SetUnitNil sets the value for Unit to be an explicit nil

### UnsetUnit
`func (o *MeterResponseDto) UnsetUnit()`

UnsetUnit ensures that no value is present for Unit, not even an explicit nil
### GetFilters

`func (o *MeterResponseDto) GetFilters() map[string]interface{}`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *MeterResponseDto) GetFiltersOk() (*map[string]interface{}, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *MeterResponseDto) SetFilters(v map[string]interface{})`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *MeterResponseDto) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### SetFiltersNil

`func (o *MeterResponseDto) SetFiltersNil(b bool)`

 SetFiltersNil sets the value for Filters to be an explicit nil

### UnsetFilters
`func (o *MeterResponseDto) UnsetFilters()`

UnsetFilters ensures that no value is present for Filters, not even an explicit nil
### GetArchived

`func (o *MeterResponseDto) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *MeterResponseDto) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *MeterResponseDto) SetArchived(v bool)`

SetArchived sets Archived field to given value.


### GetCreatedAt

`func (o *MeterResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MeterResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MeterResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *MeterResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *MeterResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *MeterResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


