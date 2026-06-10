# SubscriptionDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Subscription** | [**Subscription**](Subscription.md) | The main subscription details | 
**Payments** | [**[]Order**](Order.md) | The subscription payments / invoice billing history | 
**PurchasedAddons** | [**[]ResolvedAddon**](ResolvedAddon.md) | List of purchased addons associated with this subscription | 
**Product** | [**SubscriptionDetailProduct**](SubscriptionDetailProduct.md) | The core product information associated with this subscription | 

## Methods

### NewSubscriptionDetail

`func NewSubscriptionDetail(subscription Subscription, payments []Order, purchasedAddons []ResolvedAddon, product SubscriptionDetailProduct, ) *SubscriptionDetail`

NewSubscriptionDetail instantiates a new SubscriptionDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionDetailWithDefaults

`func NewSubscriptionDetailWithDefaults() *SubscriptionDetail`

NewSubscriptionDetailWithDefaults instantiates a new SubscriptionDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSubscription

`func (o *SubscriptionDetail) GetSubscription() Subscription`

GetSubscription returns the Subscription field if non-nil, zero value otherwise.

### GetSubscriptionOk

`func (o *SubscriptionDetail) GetSubscriptionOk() (*Subscription, bool)`

GetSubscriptionOk returns a tuple with the Subscription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscription

`func (o *SubscriptionDetail) SetSubscription(v Subscription)`

SetSubscription sets Subscription field to given value.


### GetPayments

`func (o *SubscriptionDetail) GetPayments() []Order`

GetPayments returns the Payments field if non-nil, zero value otherwise.

### GetPaymentsOk

`func (o *SubscriptionDetail) GetPaymentsOk() (*[]Order, bool)`

GetPaymentsOk returns a tuple with the Payments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayments

`func (o *SubscriptionDetail) SetPayments(v []Order)`

SetPayments sets Payments field to given value.


### GetPurchasedAddons

`func (o *SubscriptionDetail) GetPurchasedAddons() []ResolvedAddon`

GetPurchasedAddons returns the PurchasedAddons field if non-nil, zero value otherwise.

### GetPurchasedAddonsOk

`func (o *SubscriptionDetail) GetPurchasedAddonsOk() (*[]ResolvedAddon, bool)`

GetPurchasedAddonsOk returns a tuple with the PurchasedAddons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchasedAddons

`func (o *SubscriptionDetail) SetPurchasedAddons(v []ResolvedAddon)`

SetPurchasedAddons sets PurchasedAddons field to given value.


### GetProduct

`func (o *SubscriptionDetail) GetProduct() SubscriptionDetailProduct`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *SubscriptionDetail) GetProductOk() (*SubscriptionDetailProduct, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *SubscriptionDetail) SetProduct(v SubscriptionDetailProduct)`

SetProduct sets Product field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


