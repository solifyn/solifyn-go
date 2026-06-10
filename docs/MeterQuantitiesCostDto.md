# MeterQuantitiesCostDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductId** | **string** | The product ID attached to the meter. | 
**TotalUsage** | **float32** | Total usage in the requested date range. | 
**BillableUsage** | **float32** | Billable usage after free threshold is applied. | 
**Cost** | **float32** | Calculated cost for this product. | 
**Currency** | **string** | Currency used for the cost calculation. | 

## Methods

### NewMeterQuantitiesCostDto

`func NewMeterQuantitiesCostDto(productId string, totalUsage float32, billableUsage float32, cost float32, currency string, ) *MeterQuantitiesCostDto`

NewMeterQuantitiesCostDto instantiates a new MeterQuantitiesCostDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMeterQuantitiesCostDtoWithDefaults

`func NewMeterQuantitiesCostDtoWithDefaults() *MeterQuantitiesCostDto`

NewMeterQuantitiesCostDtoWithDefaults instantiates a new MeterQuantitiesCostDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductId

`func (o *MeterQuantitiesCostDto) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *MeterQuantitiesCostDto) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *MeterQuantitiesCostDto) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetTotalUsage

`func (o *MeterQuantitiesCostDto) GetTotalUsage() float32`

GetTotalUsage returns the TotalUsage field if non-nil, zero value otherwise.

### GetTotalUsageOk

`func (o *MeterQuantitiesCostDto) GetTotalUsageOk() (*float32, bool)`

GetTotalUsageOk returns a tuple with the TotalUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalUsage

`func (o *MeterQuantitiesCostDto) SetTotalUsage(v float32)`

SetTotalUsage sets TotalUsage field to given value.


### GetBillableUsage

`func (o *MeterQuantitiesCostDto) GetBillableUsage() float32`

GetBillableUsage returns the BillableUsage field if non-nil, zero value otherwise.

### GetBillableUsageOk

`func (o *MeterQuantitiesCostDto) GetBillableUsageOk() (*float32, bool)`

GetBillableUsageOk returns a tuple with the BillableUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillableUsage

`func (o *MeterQuantitiesCostDto) SetBillableUsage(v float32)`

SetBillableUsage sets BillableUsage field to given value.


### GetCost

`func (o *MeterQuantitiesCostDto) GetCost() float32`

GetCost returns the Cost field if non-nil, zero value otherwise.

### GetCostOk

`func (o *MeterQuantitiesCostDto) GetCostOk() (*float32, bool)`

GetCostOk returns a tuple with the Cost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCost

`func (o *MeterQuantitiesCostDto) SetCost(v float32)`

SetCost sets Cost field to given value.


### GetCurrency

`func (o *MeterQuantitiesCostDto) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *MeterQuantitiesCostDto) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *MeterQuantitiesCostDto) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


