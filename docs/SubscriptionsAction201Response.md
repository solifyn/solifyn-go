# SubscriptionsAction201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique ID of the subscription | 
**Status** | **string** | The status of the subscription (e.g. completed, active, trialing, past_due, canceled) | 
**CreatedAt** | **time.Time** | Timestamp when the subscription was created | 
**JoinedAt** | **time.Time** | Timestamp when the member joined | 
**UpdatedAt** | **time.Time** | Timestamp when the subscription was last updated | 
**ManageUrl** | **string** | The management URL for the billing/subscription | 
**Member** | [**SubscriptionMemberDto**](SubscriptionMemberDto.md) | The member details | 
**User** | [**SubscriptionUserDto**](SubscriptionUserDto.md) | The user details | 
**RenewalPeriodStart** | **map[string]interface{}** | Start timestamp of the current renewal period | 
**RenewalPeriodEnd** | **map[string]interface{}** | End timestamp of the current renewal period | 
**CancelAtPeriodEnd** | **bool** | Whether the subscription is set to cancel at the end of the billing period | 
**CancelOption** | **map[string]interface{}** | The cancel option details | 
**CancellationReason** | **map[string]interface{}** | The reason for cancellation | 
**CanceledAt** | **map[string]interface{}** | Timestamp when the subscription was canceled | 
**Currency** | **string** | Billing currency | 
**Company** | [**SubscriptionCompanyDto**](SubscriptionCompanyDto.md) | The company context details | 
**Plan** | [**SubscriptionPlanDto**](SubscriptionPlanDto.md) | The plan associated with this subscription | 
**PromoCode** | **map[string]interface{}** | The promo code applied to the subscription | 
**Product** | [**SubscriptionProductDto**](SubscriptionProductDto.md) | The product associated with the subscription | 
**LicenseKey** | **map[string]interface{}** | The license key associated with this subscription | 
**Metadata** | **map[string]interface{}** | Additional metadata for the subscription | 
**PaymentCollectionPaused** | **bool** | Whether the payment collection is currently paused | 
**CheckoutConfigurationId** | **string** | The checkout configuration ID used | 
**Price** | Pointer to **map[string]interface{}** | The price/amount of the membership | [optional] 
**Type** | Pointer to **map[string]interface{}** | The type of the membership plan | [optional] 
**CustomerId** | Pointer to **map[string]interface{}** | The business customer ID | [optional] 
**Success** | **bool** | Indicates if the seat adjustment was successful | 
**SubscriptionId** | **string** | The customer subscription ID | 
**AddonProductId** | **string** | The unique ID of the addon product | 
**OldQuantity** | **float32** | The previous seat quantity | 
**NewQuantity** | **float32** | The new seat quantity after adjustment | 
**QuantityDelta** | **float32** | The difference in seat quantity | 
**ProrationType** | **string** | The proration strategy type applied | 
**CostImpact** | **float32** | Calculated pro-rata price cost impact in currency unit (charged or credited) | 

## Methods

### NewSubscriptionsAction201Response

`func NewSubscriptionsAction201Response(id string, status string, createdAt time.Time, joinedAt time.Time, updatedAt time.Time, manageUrl string, member SubscriptionMemberDto, user SubscriptionUserDto, renewalPeriodStart map[string]interface{}, renewalPeriodEnd map[string]interface{}, cancelAtPeriodEnd bool, cancelOption map[string]interface{}, cancellationReason map[string]interface{}, canceledAt map[string]interface{}, currency string, company SubscriptionCompanyDto, plan SubscriptionPlanDto, promoCode map[string]interface{}, product SubscriptionProductDto, licenseKey map[string]interface{}, metadata map[string]interface{}, paymentCollectionPaused bool, checkoutConfigurationId string, success bool, subscriptionId string, addonProductId string, oldQuantity float32, newQuantity float32, quantityDelta float32, prorationType string, costImpact float32, ) *SubscriptionsAction201Response`

NewSubscriptionsAction201Response instantiates a new SubscriptionsAction201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionsAction201ResponseWithDefaults

`func NewSubscriptionsAction201ResponseWithDefaults() *SubscriptionsAction201Response`

NewSubscriptionsAction201ResponseWithDefaults instantiates a new SubscriptionsAction201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SubscriptionsAction201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SubscriptionsAction201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SubscriptionsAction201Response) SetId(v string)`

SetId sets Id field to given value.


### GetStatus

`func (o *SubscriptionsAction201Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SubscriptionsAction201Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SubscriptionsAction201Response) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *SubscriptionsAction201Response) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SubscriptionsAction201Response) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SubscriptionsAction201Response) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetJoinedAt

`func (o *SubscriptionsAction201Response) GetJoinedAt() time.Time`

GetJoinedAt returns the JoinedAt field if non-nil, zero value otherwise.

### GetJoinedAtOk

`func (o *SubscriptionsAction201Response) GetJoinedAtOk() (*time.Time, bool)`

GetJoinedAtOk returns a tuple with the JoinedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJoinedAt

`func (o *SubscriptionsAction201Response) SetJoinedAt(v time.Time)`

SetJoinedAt sets JoinedAt field to given value.


### GetUpdatedAt

`func (o *SubscriptionsAction201Response) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SubscriptionsAction201Response) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SubscriptionsAction201Response) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetManageUrl

`func (o *SubscriptionsAction201Response) GetManageUrl() string`

GetManageUrl returns the ManageUrl field if non-nil, zero value otherwise.

### GetManageUrlOk

`func (o *SubscriptionsAction201Response) GetManageUrlOk() (*string, bool)`

GetManageUrlOk returns a tuple with the ManageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManageUrl

`func (o *SubscriptionsAction201Response) SetManageUrl(v string)`

SetManageUrl sets ManageUrl field to given value.


### GetMember

`func (o *SubscriptionsAction201Response) GetMember() SubscriptionMemberDto`

GetMember returns the Member field if non-nil, zero value otherwise.

### GetMemberOk

`func (o *SubscriptionsAction201Response) GetMemberOk() (*SubscriptionMemberDto, bool)`

GetMemberOk returns a tuple with the Member field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMember

`func (o *SubscriptionsAction201Response) SetMember(v SubscriptionMemberDto)`

SetMember sets Member field to given value.


### GetUser

`func (o *SubscriptionsAction201Response) GetUser() SubscriptionUserDto`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *SubscriptionsAction201Response) GetUserOk() (*SubscriptionUserDto, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *SubscriptionsAction201Response) SetUser(v SubscriptionUserDto)`

SetUser sets User field to given value.


### GetRenewalPeriodStart

`func (o *SubscriptionsAction201Response) GetRenewalPeriodStart() map[string]interface{}`

GetRenewalPeriodStart returns the RenewalPeriodStart field if non-nil, zero value otherwise.

### GetRenewalPeriodStartOk

`func (o *SubscriptionsAction201Response) GetRenewalPeriodStartOk() (*map[string]interface{}, bool)`

GetRenewalPeriodStartOk returns a tuple with the RenewalPeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenewalPeriodStart

`func (o *SubscriptionsAction201Response) SetRenewalPeriodStart(v map[string]interface{})`

SetRenewalPeriodStart sets RenewalPeriodStart field to given value.


### GetRenewalPeriodEnd

`func (o *SubscriptionsAction201Response) GetRenewalPeriodEnd() map[string]interface{}`

GetRenewalPeriodEnd returns the RenewalPeriodEnd field if non-nil, zero value otherwise.

### GetRenewalPeriodEndOk

`func (o *SubscriptionsAction201Response) GetRenewalPeriodEndOk() (*map[string]interface{}, bool)`

GetRenewalPeriodEndOk returns a tuple with the RenewalPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenewalPeriodEnd

`func (o *SubscriptionsAction201Response) SetRenewalPeriodEnd(v map[string]interface{})`

SetRenewalPeriodEnd sets RenewalPeriodEnd field to given value.


### GetCancelAtPeriodEnd

`func (o *SubscriptionsAction201Response) GetCancelAtPeriodEnd() bool`

GetCancelAtPeriodEnd returns the CancelAtPeriodEnd field if non-nil, zero value otherwise.

### GetCancelAtPeriodEndOk

`func (o *SubscriptionsAction201Response) GetCancelAtPeriodEndOk() (*bool, bool)`

GetCancelAtPeriodEndOk returns a tuple with the CancelAtPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelAtPeriodEnd

`func (o *SubscriptionsAction201Response) SetCancelAtPeriodEnd(v bool)`

SetCancelAtPeriodEnd sets CancelAtPeriodEnd field to given value.


### GetCancelOption

`func (o *SubscriptionsAction201Response) GetCancelOption() map[string]interface{}`

GetCancelOption returns the CancelOption field if non-nil, zero value otherwise.

### GetCancelOptionOk

`func (o *SubscriptionsAction201Response) GetCancelOptionOk() (*map[string]interface{}, bool)`

GetCancelOptionOk returns a tuple with the CancelOption field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelOption

`func (o *SubscriptionsAction201Response) SetCancelOption(v map[string]interface{})`

SetCancelOption sets CancelOption field to given value.


### GetCancellationReason

`func (o *SubscriptionsAction201Response) GetCancellationReason() map[string]interface{}`

GetCancellationReason returns the CancellationReason field if non-nil, zero value otherwise.

### GetCancellationReasonOk

`func (o *SubscriptionsAction201Response) GetCancellationReasonOk() (*map[string]interface{}, bool)`

GetCancellationReasonOk returns a tuple with the CancellationReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellationReason

`func (o *SubscriptionsAction201Response) SetCancellationReason(v map[string]interface{})`

SetCancellationReason sets CancellationReason field to given value.


### GetCanceledAt

`func (o *SubscriptionsAction201Response) GetCanceledAt() map[string]interface{}`

GetCanceledAt returns the CanceledAt field if non-nil, zero value otherwise.

### GetCanceledAtOk

`func (o *SubscriptionsAction201Response) GetCanceledAtOk() (*map[string]interface{}, bool)`

GetCanceledAtOk returns a tuple with the CanceledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanceledAt

`func (o *SubscriptionsAction201Response) SetCanceledAt(v map[string]interface{})`

SetCanceledAt sets CanceledAt field to given value.


### GetCurrency

`func (o *SubscriptionsAction201Response) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SubscriptionsAction201Response) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SubscriptionsAction201Response) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetCompany

`func (o *SubscriptionsAction201Response) GetCompany() SubscriptionCompanyDto`

GetCompany returns the Company field if non-nil, zero value otherwise.

### GetCompanyOk

`func (o *SubscriptionsAction201Response) GetCompanyOk() (*SubscriptionCompanyDto, bool)`

GetCompanyOk returns a tuple with the Company field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompany

`func (o *SubscriptionsAction201Response) SetCompany(v SubscriptionCompanyDto)`

SetCompany sets Company field to given value.


### GetPlan

`func (o *SubscriptionsAction201Response) GetPlan() SubscriptionPlanDto`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *SubscriptionsAction201Response) GetPlanOk() (*SubscriptionPlanDto, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *SubscriptionsAction201Response) SetPlan(v SubscriptionPlanDto)`

SetPlan sets Plan field to given value.


### GetPromoCode

`func (o *SubscriptionsAction201Response) GetPromoCode() map[string]interface{}`

GetPromoCode returns the PromoCode field if non-nil, zero value otherwise.

### GetPromoCodeOk

`func (o *SubscriptionsAction201Response) GetPromoCodeOk() (*map[string]interface{}, bool)`

GetPromoCodeOk returns a tuple with the PromoCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromoCode

`func (o *SubscriptionsAction201Response) SetPromoCode(v map[string]interface{})`

SetPromoCode sets PromoCode field to given value.


### GetProduct

`func (o *SubscriptionsAction201Response) GetProduct() SubscriptionProductDto`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *SubscriptionsAction201Response) GetProductOk() (*SubscriptionProductDto, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *SubscriptionsAction201Response) SetProduct(v SubscriptionProductDto)`

SetProduct sets Product field to given value.


### GetLicenseKey

`func (o *SubscriptionsAction201Response) GetLicenseKey() map[string]interface{}`

GetLicenseKey returns the LicenseKey field if non-nil, zero value otherwise.

### GetLicenseKeyOk

`func (o *SubscriptionsAction201Response) GetLicenseKeyOk() (*map[string]interface{}, bool)`

GetLicenseKeyOk returns a tuple with the LicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseKey

`func (o *SubscriptionsAction201Response) SetLicenseKey(v map[string]interface{})`

SetLicenseKey sets LicenseKey field to given value.


### GetMetadata

`func (o *SubscriptionsAction201Response) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *SubscriptionsAction201Response) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *SubscriptionsAction201Response) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.


### GetPaymentCollectionPaused

`func (o *SubscriptionsAction201Response) GetPaymentCollectionPaused() bool`

GetPaymentCollectionPaused returns the PaymentCollectionPaused field if non-nil, zero value otherwise.

### GetPaymentCollectionPausedOk

`func (o *SubscriptionsAction201Response) GetPaymentCollectionPausedOk() (*bool, bool)`

GetPaymentCollectionPausedOk returns a tuple with the PaymentCollectionPaused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentCollectionPaused

`func (o *SubscriptionsAction201Response) SetPaymentCollectionPaused(v bool)`

SetPaymentCollectionPaused sets PaymentCollectionPaused field to given value.


### GetCheckoutConfigurationId

`func (o *SubscriptionsAction201Response) GetCheckoutConfigurationId() string`

GetCheckoutConfigurationId returns the CheckoutConfigurationId field if non-nil, zero value otherwise.

### GetCheckoutConfigurationIdOk

`func (o *SubscriptionsAction201Response) GetCheckoutConfigurationIdOk() (*string, bool)`

GetCheckoutConfigurationIdOk returns a tuple with the CheckoutConfigurationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutConfigurationId

`func (o *SubscriptionsAction201Response) SetCheckoutConfigurationId(v string)`

SetCheckoutConfigurationId sets CheckoutConfigurationId field to given value.


### GetPrice

`func (o *SubscriptionsAction201Response) GetPrice() map[string]interface{}`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *SubscriptionsAction201Response) GetPriceOk() (*map[string]interface{}, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *SubscriptionsAction201Response) SetPrice(v map[string]interface{})`

SetPrice sets Price field to given value.

### HasPrice

`func (o *SubscriptionsAction201Response) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetType

`func (o *SubscriptionsAction201Response) GetType() map[string]interface{}`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SubscriptionsAction201Response) GetTypeOk() (*map[string]interface{}, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SubscriptionsAction201Response) SetType(v map[string]interface{})`

SetType sets Type field to given value.

### HasType

`func (o *SubscriptionsAction201Response) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCustomerId

`func (o *SubscriptionsAction201Response) GetCustomerId() map[string]interface{}`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *SubscriptionsAction201Response) GetCustomerIdOk() (*map[string]interface{}, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *SubscriptionsAction201Response) SetCustomerId(v map[string]interface{})`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *SubscriptionsAction201Response) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetSuccess

`func (o *SubscriptionsAction201Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *SubscriptionsAction201Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *SubscriptionsAction201Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetSubscriptionId

`func (o *SubscriptionsAction201Response) GetSubscriptionId() string`

GetSubscriptionId returns the SubscriptionId field if non-nil, zero value otherwise.

### GetSubscriptionIdOk

`func (o *SubscriptionsAction201Response) GetSubscriptionIdOk() (*string, bool)`

GetSubscriptionIdOk returns a tuple with the SubscriptionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionId

`func (o *SubscriptionsAction201Response) SetSubscriptionId(v string)`

SetSubscriptionId sets SubscriptionId field to given value.


### GetAddonProductId

`func (o *SubscriptionsAction201Response) GetAddonProductId() string`

GetAddonProductId returns the AddonProductId field if non-nil, zero value otherwise.

### GetAddonProductIdOk

`func (o *SubscriptionsAction201Response) GetAddonProductIdOk() (*string, bool)`

GetAddonProductIdOk returns a tuple with the AddonProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddonProductId

`func (o *SubscriptionsAction201Response) SetAddonProductId(v string)`

SetAddonProductId sets AddonProductId field to given value.


### GetOldQuantity

`func (o *SubscriptionsAction201Response) GetOldQuantity() float32`

GetOldQuantity returns the OldQuantity field if non-nil, zero value otherwise.

### GetOldQuantityOk

`func (o *SubscriptionsAction201Response) GetOldQuantityOk() (*float32, bool)`

GetOldQuantityOk returns a tuple with the OldQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldQuantity

`func (o *SubscriptionsAction201Response) SetOldQuantity(v float32)`

SetOldQuantity sets OldQuantity field to given value.


### GetNewQuantity

`func (o *SubscriptionsAction201Response) GetNewQuantity() float32`

GetNewQuantity returns the NewQuantity field if non-nil, zero value otherwise.

### GetNewQuantityOk

`func (o *SubscriptionsAction201Response) GetNewQuantityOk() (*float32, bool)`

GetNewQuantityOk returns a tuple with the NewQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewQuantity

`func (o *SubscriptionsAction201Response) SetNewQuantity(v float32)`

SetNewQuantity sets NewQuantity field to given value.


### GetQuantityDelta

`func (o *SubscriptionsAction201Response) GetQuantityDelta() float32`

GetQuantityDelta returns the QuantityDelta field if non-nil, zero value otherwise.

### GetQuantityDeltaOk

`func (o *SubscriptionsAction201Response) GetQuantityDeltaOk() (*float32, bool)`

GetQuantityDeltaOk returns a tuple with the QuantityDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityDelta

`func (o *SubscriptionsAction201Response) SetQuantityDelta(v float32)`

SetQuantityDelta sets QuantityDelta field to given value.


### GetProrationType

`func (o *SubscriptionsAction201Response) GetProrationType() string`

GetProrationType returns the ProrationType field if non-nil, zero value otherwise.

### GetProrationTypeOk

`func (o *SubscriptionsAction201Response) GetProrationTypeOk() (*string, bool)`

GetProrationTypeOk returns a tuple with the ProrationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProrationType

`func (o *SubscriptionsAction201Response) SetProrationType(v string)`

SetProrationType sets ProrationType field to given value.


### GetCostImpact

`func (o *SubscriptionsAction201Response) GetCostImpact() float32`

GetCostImpact returns the CostImpact field if non-nil, zero value otherwise.

### GetCostImpactOk

`func (o *SubscriptionsAction201Response) GetCostImpactOk() (*float32, bool)`

GetCostImpactOk returns a tuple with the CostImpact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostImpact

`func (o *SubscriptionsAction201Response) SetCostImpact(v float32)`

SetCostImpact sets CostImpact field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


