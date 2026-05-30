# DashboardStatsDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Revenue** | **float32** | Gross revenue in cents | 
**OrdersCount** | **float32** | Total payments processed count | 
**RefundsCount** | **float32** | Gross amount refunded in cents | 
**ActiveMemberships** | **float32** | Number of active paying customers/memberships | 

## Methods

### NewDashboardStatsDto

`func NewDashboardStatsDto(revenue float32, ordersCount float32, refundsCount float32, activeMemberships float32, ) *DashboardStatsDto`

NewDashboardStatsDto instantiates a new DashboardStatsDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDashboardStatsDtoWithDefaults

`func NewDashboardStatsDtoWithDefaults() *DashboardStatsDto`

NewDashboardStatsDtoWithDefaults instantiates a new DashboardStatsDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRevenue

`func (o *DashboardStatsDto) GetRevenue() float32`

GetRevenue returns the Revenue field if non-nil, zero value otherwise.

### GetRevenueOk

`func (o *DashboardStatsDto) GetRevenueOk() (*float32, bool)`

GetRevenueOk returns a tuple with the Revenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevenue

`func (o *DashboardStatsDto) SetRevenue(v float32)`

SetRevenue sets Revenue field to given value.


### GetOrdersCount

`func (o *DashboardStatsDto) GetOrdersCount() float32`

GetOrdersCount returns the OrdersCount field if non-nil, zero value otherwise.

### GetOrdersCountOk

`func (o *DashboardStatsDto) GetOrdersCountOk() (*float32, bool)`

GetOrdersCountOk returns a tuple with the OrdersCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrdersCount

`func (o *DashboardStatsDto) SetOrdersCount(v float32)`

SetOrdersCount sets OrdersCount field to given value.


### GetRefundsCount

`func (o *DashboardStatsDto) GetRefundsCount() float32`

GetRefundsCount returns the RefundsCount field if non-nil, zero value otherwise.

### GetRefundsCountOk

`func (o *DashboardStatsDto) GetRefundsCountOk() (*float32, bool)`

GetRefundsCountOk returns a tuple with the RefundsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefundsCount

`func (o *DashboardStatsDto) SetRefundsCount(v float32)`

SetRefundsCount sets RefundsCount field to given value.


### GetActiveMemberships

`func (o *DashboardStatsDto) GetActiveMemberships() float32`

GetActiveMemberships returns the ActiveMemberships field if non-nil, zero value otherwise.

### GetActiveMembershipsOk

`func (o *DashboardStatsDto) GetActiveMembershipsOk() (*float32, bool)`

GetActiveMembershipsOk returns a tuple with the ActiveMemberships field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveMemberships

`func (o *DashboardStatsDto) SetActiveMemberships(v float32)`

SetActiveMemberships sets ActiveMemberships field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


