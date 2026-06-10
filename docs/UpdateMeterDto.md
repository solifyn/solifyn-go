# UpdateMeterDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Meter display name. | [optional] 
**Description** | Pointer to **string** | Meter description. | [optional] 
**EventName** | Pointer to **string** | The event name tracked by this meter. | [optional] 
**AggregationType** | Pointer to **string** | Aggregation strategy for usage events. | [optional] 
**AggregationKey** | Pointer to **string** | Metadata key used by SUM, MAX, or LAST aggregation modes. | [optional] 
**Unit** | Pointer to **string** | Measurement unit label. | [optional] 
**Filters** | Pointer to **map[string]interface{}** | Optional filter definition for advanced matching. | [optional] 
**EnableFiltering** | Pointer to **bool** | Enable filtering on usage event ingestion. | [optional] 

## Methods

### NewUpdateMeterDto

`func NewUpdateMeterDto() *UpdateMeterDto`

NewUpdateMeterDto instantiates a new UpdateMeterDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateMeterDtoWithDefaults

`func NewUpdateMeterDtoWithDefaults() *UpdateMeterDto`

NewUpdateMeterDtoWithDefaults instantiates a new UpdateMeterDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateMeterDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateMeterDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateMeterDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateMeterDto) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateMeterDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateMeterDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateMeterDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateMeterDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEventName

`func (o *UpdateMeterDto) GetEventName() string`

GetEventName returns the EventName field if non-nil, zero value otherwise.

### GetEventNameOk

`func (o *UpdateMeterDto) GetEventNameOk() (*string, bool)`

GetEventNameOk returns a tuple with the EventName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventName

`func (o *UpdateMeterDto) SetEventName(v string)`

SetEventName sets EventName field to given value.

### HasEventName

`func (o *UpdateMeterDto) HasEventName() bool`

HasEventName returns a boolean if a field has been set.

### GetAggregationType

`func (o *UpdateMeterDto) GetAggregationType() string`

GetAggregationType returns the AggregationType field if non-nil, zero value otherwise.

### GetAggregationTypeOk

`func (o *UpdateMeterDto) GetAggregationTypeOk() (*string, bool)`

GetAggregationTypeOk returns a tuple with the AggregationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregationType

`func (o *UpdateMeterDto) SetAggregationType(v string)`

SetAggregationType sets AggregationType field to given value.

### HasAggregationType

`func (o *UpdateMeterDto) HasAggregationType() bool`

HasAggregationType returns a boolean if a field has been set.

### GetAggregationKey

`func (o *UpdateMeterDto) GetAggregationKey() string`

GetAggregationKey returns the AggregationKey field if non-nil, zero value otherwise.

### GetAggregationKeyOk

`func (o *UpdateMeterDto) GetAggregationKeyOk() (*string, bool)`

GetAggregationKeyOk returns a tuple with the AggregationKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregationKey

`func (o *UpdateMeterDto) SetAggregationKey(v string)`

SetAggregationKey sets AggregationKey field to given value.

### HasAggregationKey

`func (o *UpdateMeterDto) HasAggregationKey() bool`

HasAggregationKey returns a boolean if a field has been set.

### GetUnit

`func (o *UpdateMeterDto) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *UpdateMeterDto) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *UpdateMeterDto) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *UpdateMeterDto) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetFilters

`func (o *UpdateMeterDto) GetFilters() map[string]interface{}`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *UpdateMeterDto) GetFiltersOk() (*map[string]interface{}, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *UpdateMeterDto) SetFilters(v map[string]interface{})`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *UpdateMeterDto) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### GetEnableFiltering

`func (o *UpdateMeterDto) GetEnableFiltering() bool`

GetEnableFiltering returns the EnableFiltering field if non-nil, zero value otherwise.

### GetEnableFilteringOk

`func (o *UpdateMeterDto) GetEnableFilteringOk() (*bool, bool)`

GetEnableFilteringOk returns a tuple with the EnableFiltering field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableFiltering

`func (o *UpdateMeterDto) SetEnableFiltering(v bool)`

SetEnableFiltering sets EnableFiltering field to given value.

### HasEnableFiltering

`func (o *UpdateMeterDto) HasEnableFiltering() bool`

HasEnableFiltering returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


