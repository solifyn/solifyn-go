# Subscription

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
**Currency** | **string** | The currency used for payments | 
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

## Methods

### NewSubscription

`func NewSubscription(id string, status string, createdAt time.Time, joinedAt time.Time, updatedAt time.Time, manageUrl string, member SubscriptionMemberDto, user SubscriptionUserDto, renewalPeriodStart map[string]interface{}, renewalPeriodEnd map[string]interface{}, cancelAtPeriodEnd bool, cancelOption map[string]interface{}, cancellationReason map[string]interface{}, canceledAt map[string]interface{}, currency string, company SubscriptionCompanyDto, plan SubscriptionPlanDto, promoCode map[string]interface{}, product SubscriptionProductDto, licenseKey map[string]interface{}, metadata map[string]interface{}, paymentCollectionPaused bool, checkoutConfigurationId string, ) *Subscription`

NewSubscription instantiates a new Subscription object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionWithDefaults

`func NewSubscriptionWithDefaults() *Subscription`

NewSubscriptionWithDefaults instantiates a new Subscription object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Subscription) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Subscription) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Subscription) SetId(v string)`

SetId sets Id field to given value.


### GetStatus

`func (o *Subscription) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Subscription) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Subscription) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *Subscription) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Subscription) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Subscription) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetJoinedAt

`func (o *Subscription) GetJoinedAt() time.Time`

GetJoinedAt returns the JoinedAt field if non-nil, zero value otherwise.

### GetJoinedAtOk

`func (o *Subscription) GetJoinedAtOk() (*time.Time, bool)`

GetJoinedAtOk returns a tuple with the JoinedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJoinedAt

`func (o *Subscription) SetJoinedAt(v time.Time)`

SetJoinedAt sets JoinedAt field to given value.


### GetUpdatedAt

`func (o *Subscription) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Subscription) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Subscription) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetManageUrl

`func (o *Subscription) GetManageUrl() string`

GetManageUrl returns the ManageUrl field if non-nil, zero value otherwise.

### GetManageUrlOk

`func (o *Subscription) GetManageUrlOk() (*string, bool)`

GetManageUrlOk returns a tuple with the ManageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManageUrl

`func (o *Subscription) SetManageUrl(v string)`

SetManageUrl sets ManageUrl field to given value.


### GetMember

`func (o *Subscription) GetMember() SubscriptionMemberDto`

GetMember returns the Member field if non-nil, zero value otherwise.

### GetMemberOk

`func (o *Subscription) GetMemberOk() (*SubscriptionMemberDto, bool)`

GetMemberOk returns a tuple with the Member field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMember

`func (o *Subscription) SetMember(v SubscriptionMemberDto)`

SetMember sets Member field to given value.


### GetUser

`func (o *Subscription) GetUser() SubscriptionUserDto`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *Subscription) GetUserOk() (*SubscriptionUserDto, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *Subscription) SetUser(v SubscriptionUserDto)`

SetUser sets User field to given value.


### GetRenewalPeriodStart

`func (o *Subscription) GetRenewalPeriodStart() map[string]interface{}`

GetRenewalPeriodStart returns the RenewalPeriodStart field if non-nil, zero value otherwise.

### GetRenewalPeriodStartOk

`func (o *Subscription) GetRenewalPeriodStartOk() (*map[string]interface{}, bool)`

GetRenewalPeriodStartOk returns a tuple with the RenewalPeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenewalPeriodStart

`func (o *Subscription) SetRenewalPeriodStart(v map[string]interface{})`

SetRenewalPeriodStart sets RenewalPeriodStart field to given value.


### SetRenewalPeriodStartNil

`func (o *Subscription) SetRenewalPeriodStartNil(b bool)`

 SetRenewalPeriodStartNil sets the value for RenewalPeriodStart to be an explicit nil

### UnsetRenewalPeriodStart
`func (o *Subscription) UnsetRenewalPeriodStart()`

UnsetRenewalPeriodStart ensures that no value is present for RenewalPeriodStart, not even an explicit nil
### GetRenewalPeriodEnd

`func (o *Subscription) GetRenewalPeriodEnd() map[string]interface{}`

GetRenewalPeriodEnd returns the RenewalPeriodEnd field if non-nil, zero value otherwise.

### GetRenewalPeriodEndOk

`func (o *Subscription) GetRenewalPeriodEndOk() (*map[string]interface{}, bool)`

GetRenewalPeriodEndOk returns a tuple with the RenewalPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenewalPeriodEnd

`func (o *Subscription) SetRenewalPeriodEnd(v map[string]interface{})`

SetRenewalPeriodEnd sets RenewalPeriodEnd field to given value.


### SetRenewalPeriodEndNil

`func (o *Subscription) SetRenewalPeriodEndNil(b bool)`

 SetRenewalPeriodEndNil sets the value for RenewalPeriodEnd to be an explicit nil

### UnsetRenewalPeriodEnd
`func (o *Subscription) UnsetRenewalPeriodEnd()`

UnsetRenewalPeriodEnd ensures that no value is present for RenewalPeriodEnd, not even an explicit nil
### GetCancelAtPeriodEnd

`func (o *Subscription) GetCancelAtPeriodEnd() bool`

GetCancelAtPeriodEnd returns the CancelAtPeriodEnd field if non-nil, zero value otherwise.

### GetCancelAtPeriodEndOk

`func (o *Subscription) GetCancelAtPeriodEndOk() (*bool, bool)`

GetCancelAtPeriodEndOk returns a tuple with the CancelAtPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelAtPeriodEnd

`func (o *Subscription) SetCancelAtPeriodEnd(v bool)`

SetCancelAtPeriodEnd sets CancelAtPeriodEnd field to given value.


### GetCancelOption

`func (o *Subscription) GetCancelOption() map[string]interface{}`

GetCancelOption returns the CancelOption field if non-nil, zero value otherwise.

### GetCancelOptionOk

`func (o *Subscription) GetCancelOptionOk() (*map[string]interface{}, bool)`

GetCancelOptionOk returns a tuple with the CancelOption field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelOption

`func (o *Subscription) SetCancelOption(v map[string]interface{})`

SetCancelOption sets CancelOption field to given value.


### SetCancelOptionNil

`func (o *Subscription) SetCancelOptionNil(b bool)`

 SetCancelOptionNil sets the value for CancelOption to be an explicit nil

### UnsetCancelOption
`func (o *Subscription) UnsetCancelOption()`

UnsetCancelOption ensures that no value is present for CancelOption, not even an explicit nil
### GetCancellationReason

`func (o *Subscription) GetCancellationReason() map[string]interface{}`

GetCancellationReason returns the CancellationReason field if non-nil, zero value otherwise.

### GetCancellationReasonOk

`func (o *Subscription) GetCancellationReasonOk() (*map[string]interface{}, bool)`

GetCancellationReasonOk returns a tuple with the CancellationReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellationReason

`func (o *Subscription) SetCancellationReason(v map[string]interface{})`

SetCancellationReason sets CancellationReason field to given value.


### SetCancellationReasonNil

`func (o *Subscription) SetCancellationReasonNil(b bool)`

 SetCancellationReasonNil sets the value for CancellationReason to be an explicit nil

### UnsetCancellationReason
`func (o *Subscription) UnsetCancellationReason()`

UnsetCancellationReason ensures that no value is present for CancellationReason, not even an explicit nil
### GetCanceledAt

`func (o *Subscription) GetCanceledAt() map[string]interface{}`

GetCanceledAt returns the CanceledAt field if non-nil, zero value otherwise.

### GetCanceledAtOk

`func (o *Subscription) GetCanceledAtOk() (*map[string]interface{}, bool)`

GetCanceledAtOk returns a tuple with the CanceledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanceledAt

`func (o *Subscription) SetCanceledAt(v map[string]interface{})`

SetCanceledAt sets CanceledAt field to given value.


### SetCanceledAtNil

`func (o *Subscription) SetCanceledAtNil(b bool)`

 SetCanceledAtNil sets the value for CanceledAt to be an explicit nil

### UnsetCanceledAt
`func (o *Subscription) UnsetCanceledAt()`

UnsetCanceledAt ensures that no value is present for CanceledAt, not even an explicit nil
### GetCurrency

`func (o *Subscription) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Subscription) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Subscription) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetCompany

`func (o *Subscription) GetCompany() SubscriptionCompanyDto`

GetCompany returns the Company field if non-nil, zero value otherwise.

### GetCompanyOk

`func (o *Subscription) GetCompanyOk() (*SubscriptionCompanyDto, bool)`

GetCompanyOk returns a tuple with the Company field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompany

`func (o *Subscription) SetCompany(v SubscriptionCompanyDto)`

SetCompany sets Company field to given value.


### GetPlan

`func (o *Subscription) GetPlan() SubscriptionPlanDto`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *Subscription) GetPlanOk() (*SubscriptionPlanDto, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *Subscription) SetPlan(v SubscriptionPlanDto)`

SetPlan sets Plan field to given value.


### GetPromoCode

`func (o *Subscription) GetPromoCode() map[string]interface{}`

GetPromoCode returns the PromoCode field if non-nil, zero value otherwise.

### GetPromoCodeOk

`func (o *Subscription) GetPromoCodeOk() (*map[string]interface{}, bool)`

GetPromoCodeOk returns a tuple with the PromoCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromoCode

`func (o *Subscription) SetPromoCode(v map[string]interface{})`

SetPromoCode sets PromoCode field to given value.


### SetPromoCodeNil

`func (o *Subscription) SetPromoCodeNil(b bool)`

 SetPromoCodeNil sets the value for PromoCode to be an explicit nil

### UnsetPromoCode
`func (o *Subscription) UnsetPromoCode()`

UnsetPromoCode ensures that no value is present for PromoCode, not even an explicit nil
### GetProduct

`func (o *Subscription) GetProduct() SubscriptionProductDto`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *Subscription) GetProductOk() (*SubscriptionProductDto, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *Subscription) SetProduct(v SubscriptionProductDto)`

SetProduct sets Product field to given value.


### GetLicenseKey

`func (o *Subscription) GetLicenseKey() map[string]interface{}`

GetLicenseKey returns the LicenseKey field if non-nil, zero value otherwise.

### GetLicenseKeyOk

`func (o *Subscription) GetLicenseKeyOk() (*map[string]interface{}, bool)`

GetLicenseKeyOk returns a tuple with the LicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseKey

`func (o *Subscription) SetLicenseKey(v map[string]interface{})`

SetLicenseKey sets LicenseKey field to given value.


### SetLicenseKeyNil

`func (o *Subscription) SetLicenseKeyNil(b bool)`

 SetLicenseKeyNil sets the value for LicenseKey to be an explicit nil

### UnsetLicenseKey
`func (o *Subscription) UnsetLicenseKey()`

UnsetLicenseKey ensures that no value is present for LicenseKey, not even an explicit nil
### GetMetadata

`func (o *Subscription) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Subscription) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Subscription) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.


### GetPaymentCollectionPaused

`func (o *Subscription) GetPaymentCollectionPaused() bool`

GetPaymentCollectionPaused returns the PaymentCollectionPaused field if non-nil, zero value otherwise.

### GetPaymentCollectionPausedOk

`func (o *Subscription) GetPaymentCollectionPausedOk() (*bool, bool)`

GetPaymentCollectionPausedOk returns a tuple with the PaymentCollectionPaused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentCollectionPaused

`func (o *Subscription) SetPaymentCollectionPaused(v bool)`

SetPaymentCollectionPaused sets PaymentCollectionPaused field to given value.


### GetCheckoutConfigurationId

`func (o *Subscription) GetCheckoutConfigurationId() string`

GetCheckoutConfigurationId returns the CheckoutConfigurationId field if non-nil, zero value otherwise.

### GetCheckoutConfigurationIdOk

`func (o *Subscription) GetCheckoutConfigurationIdOk() (*string, bool)`

GetCheckoutConfigurationIdOk returns a tuple with the CheckoutConfigurationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutConfigurationId

`func (o *Subscription) SetCheckoutConfigurationId(v string)`

SetCheckoutConfigurationId sets CheckoutConfigurationId field to given value.


### GetPrice

`func (o *Subscription) GetPrice() map[string]interface{}`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *Subscription) GetPriceOk() (*map[string]interface{}, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *Subscription) SetPrice(v map[string]interface{})`

SetPrice sets Price field to given value.

### HasPrice

`func (o *Subscription) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### SetPriceNil

`func (o *Subscription) SetPriceNil(b bool)`

 SetPriceNil sets the value for Price to be an explicit nil

### UnsetPrice
`func (o *Subscription) UnsetPrice()`

UnsetPrice ensures that no value is present for Price, not even an explicit nil
### GetType

`func (o *Subscription) GetType() map[string]interface{}`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Subscription) GetTypeOk() (*map[string]interface{}, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Subscription) SetType(v map[string]interface{})`

SetType sets Type field to given value.

### HasType

`func (o *Subscription) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *Subscription) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *Subscription) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetCustomerId

`func (o *Subscription) GetCustomerId() map[string]interface{}`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *Subscription) GetCustomerIdOk() (*map[string]interface{}, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *Subscription) SetCustomerId(v map[string]interface{})`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *Subscription) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *Subscription) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *Subscription) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


