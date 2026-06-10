# CreateSetupCheckoutDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompanyId** | **string** | The Whop/Stripe company ID context | 
**Currency** | Pointer to **string** | Currency for setup mode | [optional] [default to "usd"]
**RetryPaymentId** | Pointer to **string** | Internal or Whop failed payment ID to retry | [optional] 
**MembershipId** | Pointer to **string** | Membership ID to link setup checkout to for card updating | [optional] 
**PlanId** | Pointer to **string** | Plan ID to retry or renew | [optional] 

## Methods

### NewCreateSetupCheckoutDto

`func NewCreateSetupCheckoutDto(companyId string, ) *CreateSetupCheckoutDto`

NewCreateSetupCheckoutDto instantiates a new CreateSetupCheckoutDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateSetupCheckoutDtoWithDefaults

`func NewCreateSetupCheckoutDtoWithDefaults() *CreateSetupCheckoutDto`

NewCreateSetupCheckoutDtoWithDefaults instantiates a new CreateSetupCheckoutDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompanyId

`func (o *CreateSetupCheckoutDto) GetCompanyId() string`

GetCompanyId returns the CompanyId field if non-nil, zero value otherwise.

### GetCompanyIdOk

`func (o *CreateSetupCheckoutDto) GetCompanyIdOk() (*string, bool)`

GetCompanyIdOk returns a tuple with the CompanyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyId

`func (o *CreateSetupCheckoutDto) SetCompanyId(v string)`

SetCompanyId sets CompanyId field to given value.


### GetCurrency

`func (o *CreateSetupCheckoutDto) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateSetupCheckoutDto) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateSetupCheckoutDto) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CreateSetupCheckoutDto) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetRetryPaymentId

`func (o *CreateSetupCheckoutDto) GetRetryPaymentId() string`

GetRetryPaymentId returns the RetryPaymentId field if non-nil, zero value otherwise.

### GetRetryPaymentIdOk

`func (o *CreateSetupCheckoutDto) GetRetryPaymentIdOk() (*string, bool)`

GetRetryPaymentIdOk returns a tuple with the RetryPaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryPaymentId

`func (o *CreateSetupCheckoutDto) SetRetryPaymentId(v string)`

SetRetryPaymentId sets RetryPaymentId field to given value.

### HasRetryPaymentId

`func (o *CreateSetupCheckoutDto) HasRetryPaymentId() bool`

HasRetryPaymentId returns a boolean if a field has been set.

### GetMembershipId

`func (o *CreateSetupCheckoutDto) GetMembershipId() string`

GetMembershipId returns the MembershipId field if non-nil, zero value otherwise.

### GetMembershipIdOk

`func (o *CreateSetupCheckoutDto) GetMembershipIdOk() (*string, bool)`

GetMembershipIdOk returns a tuple with the MembershipId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembershipId

`func (o *CreateSetupCheckoutDto) SetMembershipId(v string)`

SetMembershipId sets MembershipId field to given value.

### HasMembershipId

`func (o *CreateSetupCheckoutDto) HasMembershipId() bool`

HasMembershipId returns a boolean if a field has been set.

### GetPlanId

`func (o *CreateSetupCheckoutDto) GetPlanId() string`

GetPlanId returns the PlanId field if non-nil, zero value otherwise.

### GetPlanIdOk

`func (o *CreateSetupCheckoutDto) GetPlanIdOk() (*string, bool)`

GetPlanIdOk returns a tuple with the PlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanId

`func (o *CreateSetupCheckoutDto) SetPlanId(v string)`

SetPlanId sets PlanId field to given value.

### HasPlanId

`func (o *CreateSetupCheckoutDto) HasPlanId() bool`

HasPlanId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


