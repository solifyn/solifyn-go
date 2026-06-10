# SubscriptionList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]Subscription**](Subscription.md) | List of customer subscriptions | 
**TotalCount** | **float32** | Total count of subscriptions matching the filters | 

## Methods

### NewSubscriptionList

`func NewSubscriptionList(items []Subscription, totalCount float32, ) *SubscriptionList`

NewSubscriptionList instantiates a new SubscriptionList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionListWithDefaults

`func NewSubscriptionListWithDefaults() *SubscriptionList`

NewSubscriptionListWithDefaults instantiates a new SubscriptionList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *SubscriptionList) GetItems() []Subscription`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *SubscriptionList) GetItemsOk() (*[]Subscription, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *SubscriptionList) SetItems(v []Subscription)`

SetItems sets Items field to given value.


### GetTotalCount

`func (o *SubscriptionList) GetTotalCount() float32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *SubscriptionList) GetTotalCountOk() (*float32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *SubscriptionList) SetTotalCount(v float32)`

SetTotalCount sets TotalCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


