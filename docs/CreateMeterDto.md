# CreateMeterDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Meter display name. | 
**Description** | Pointer to **string** | Meter description. | [optional] 
**EventName** | **string** | The event name tracked by this meter. | 
**AggregationType** | **string** | Aggregation strategy for usage events. | 
**AggregationKey** | Pointer to **string** | Metadata key used by SUM, MAX, or LAST aggregation modes. | [optional] 
**Unit** | Pointer to **string** | Measurement unit label. | [optional] 
**Filters** | Pointer to **map[string]interface{}** | Optional filter definition for advanced matching. | [optional] 
**EnableFiltering** | Pointer to **bool** | Enable filtering on usage event ingestion. | [optional] [default to false]

## Methods

### NewCreateMeterDto

`func NewCreateMeterDto(name string, eventName string, aggregationType string, ) *CreateMeterDto`

NewCreateMeterDto instantiates a new CreateMeterDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateMeterDtoWithDefaults

`func NewCreateMeterDtoWithDefaults() *CreateMeterDto`

NewCreateMeterDtoWithDefaults instantiates a new CreateMeterDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateMeterDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateMeterDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateMeterDto) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *CreateMeterDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateMeterDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateMeterDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateMeterDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEventName

`func (o *CreateMeterDto) GetEventName() string`

GetEventName returns the EventName field if non-nil, zero value otherwise.

### GetEventNameOk

`func (o *CreateMeterDto) GetEventNameOk() (*string, bool)`

GetEventNameOk returns a tuple with the EventName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventName

`func (o *CreateMeterDto) SetEventName(v string)`

SetEventName sets EventName field to given value.


### GetAggregationType

`func (o *CreateMeterDto) GetAggregationType() string`

GetAggregationType returns the AggregationType field if non-nil, zero value otherwise.

### GetAggregationTypeOk

`func (o *CreateMeterDto) GetAggregationTypeOk() (*string, bool)`

GetAggregationTypeOk returns a tuple with the AggregationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregationType

`func (o *CreateMeterDto) SetAggregationType(v string)`

SetAggregationType sets AggregationType field to given value.


### GetAggregationKey

`func (o *CreateMeterDto) GetAggregationKey() string`

GetAggregationKey returns the AggregationKey field if non-nil, zero value otherwise.

### GetAggregationKeyOk

`func (o *CreateMeterDto) GetAggregationKeyOk() (*string, bool)`

GetAggregationKeyOk returns a tuple with the AggregationKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregationKey

`func (o *CreateMeterDto) SetAggregationKey(v string)`

SetAggregationKey sets AggregationKey field to given value.

### HasAggregationKey

`func (o *CreateMeterDto) HasAggregationKey() bool`

HasAggregationKey returns a boolean if a field has been set.

### GetUnit

`func (o *CreateMeterDto) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *CreateMeterDto) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *CreateMeterDto) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *CreateMeterDto) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetFilters

`func (o *CreateMeterDto) GetFilters() map[string]interface{}`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *CreateMeterDto) GetFiltersOk() (*map[string]interface{}, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *CreateMeterDto) SetFilters(v map[string]interface{})`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *CreateMeterDto) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### GetEnableFiltering

`func (o *CreateMeterDto) GetEnableFiltering() bool`

GetEnableFiltering returns the EnableFiltering field if non-nil, zero value otherwise.

### GetEnableFilteringOk

`func (o *CreateMeterDto) GetEnableFilteringOk() (*bool, bool)`

GetEnableFilteringOk returns a tuple with the EnableFiltering field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableFiltering

`func (o *CreateMeterDto) SetEnableFiltering(v bool)`

SetEnableFiltering sets EnableFiltering field to given value.

### HasEnableFiltering

`func (o *CreateMeterDto) HasEnableFiltering() bool`

HasEnableFiltering returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


