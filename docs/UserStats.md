# UserStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Summary** | [**DashboardStatsDto**](DashboardStatsDto.md) | Core metric summaries | 
**ChartData** | **[]map[string]interface{}** | Graph data plotting daily analytics over past month | 

## Methods

### NewUserStats

`func NewUserStats(summary DashboardStatsDto, chartData []map[string]interface{}, ) *UserStats`

NewUserStats instantiates a new UserStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserStatsWithDefaults

`func NewUserStatsWithDefaults() *UserStats`

NewUserStatsWithDefaults instantiates a new UserStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSummary

`func (o *UserStats) GetSummary() DashboardStatsDto`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *UserStats) GetSummaryOk() (*DashboardStatsDto, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *UserStats) SetSummary(v DashboardStatsDto)`

SetSummary sets Summary field to given value.


### GetChartData

`func (o *UserStats) GetChartData() []map[string]interface{}`

GetChartData returns the ChartData field if non-nil, zero value otherwise.

### GetChartDataOk

`func (o *UserStats) GetChartDataOk() (*[]map[string]interface{}, bool)`

GetChartDataOk returns a tuple with the ChartData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChartData

`func (o *UserStats) SetChartData(v []map[string]interface{})`

SetChartData sets ChartData field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


