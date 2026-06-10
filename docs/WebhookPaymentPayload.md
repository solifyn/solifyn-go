# WebhookPaymentPayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Internal payment ID. | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Substatus** | Pointer to **NullableString** |  | [optional] 
**CustomerId** | Pointer to **NullableString** |  | [optional] 
**CustomerEmail** | Pointer to **NullableString** |  | [optional] 
**CustomerName** | Pointer to **NullableString** |  | [optional] 
**CustomerUsername** | Pointer to **NullableString** |  | [optional] 
**ProductTitle** | Pointer to **NullableString** |  | [optional] 
**ProductRoute** | Pointer to **NullableString** |  | [optional] 
**PlanId** | Pointer to **NullableString** |  | [optional] 
**MembershipId** | Pointer to **NullableString** |  | [optional] 
**MembershipStatus** | Pointer to **NullableString** |  | [optional] 
**BillingReason** | Pointer to **NullableString** |  | [optional] 
**Amount** | Pointer to **NullableString** | Dollar value, 2 d.p. | [optional] 
**Subtotal** | Pointer to **NullableString** |  | [optional] 
**UsdTotal** | Pointer to **NullableString** |  | [optional] 
**FeeAmount** | Pointer to **NullableString** |  | [optional] 
**AmountAfterFees** | Pointer to **NullableString** |  | [optional] 
**TaxAmount** | Pointer to **NullableString** |  | [optional] 
**TaxBehavior** | Pointer to **NullableString** |  | [optional] 
**TaxRefundedAmount** | Pointer to **NullableString** |  | [optional] 
**RefundedAmount** | Pointer to **string** |  | [optional] 
**SettlementAmount** | Pointer to **NullableString** |  | [optional] 
**SettlementCurrency** | Pointer to **NullableString** |  | [optional] 
**SettlementExchangeRate** | Pointer to **NullableString** |  | [optional] 
**Currency** | Pointer to **string** |  | [optional] 
**Refundable** | Pointer to **bool** |  | [optional] 
**Retryable** | Pointer to **bool** |  | [optional] 
**AutoRefunded** | Pointer to **bool** |  | [optional] 
**PaymentMethod** | Pointer to **NullableString** |  | [optional] 
**CardBrand** | Pointer to **NullableString** |  | [optional] 
**CardLast4** | Pointer to **NullableString** |  | [optional] 
**CardExpMonth** | Pointer to **NullableInt32** |  | [optional] 
**CardExpYear** | Pointer to **NullableInt32** |  | [optional] 
**BillingAddress** | Pointer to [**NullableWebhookPaymentPayloadBillingAddress**](WebhookPaymentPayloadBillingAddress.md) |  | [optional] 
**LicenseKey** | Pointer to **NullableString** |  | [optional] 
**FilesSnapshot** | Pointer to **[]map[string]interface{}** |  | [optional] 
**CheckoutId** | Pointer to **NullableString** |  | [optional] 
**DiscountCode** | Pointer to **NullableString** |  | [optional] 
**FailureMessage** | Pointer to **NullableString** |  | [optional] 
**PaidAt** | Pointer to **NullableTime** |  | [optional] 
**RefundedAt** | Pointer to **NullableTime** |  | [optional] 
**DisputeAlertedAt** | Pointer to **NullableTime** |  | [optional] 
**LastPaymentAttempt** | Pointer to **NullableTime** |  | [optional] 
**NextPaymentAttempt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**PaymentEventType** | Pointer to **NullableString** |  | [optional] 
**LastEventType** | Pointer to **NullableString** |  | [optional] 
**BusinessId** | Pointer to **string** |  | [optional] 

## Methods

### NewWebhookPaymentPayload

`func NewWebhookPaymentPayload() *WebhookPaymentPayload`

NewWebhookPaymentPayload instantiates a new WebhookPaymentPayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookPaymentPayloadWithDefaults

`func NewWebhookPaymentPayloadWithDefaults() *WebhookPaymentPayload`

NewWebhookPaymentPayloadWithDefaults instantiates a new WebhookPaymentPayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WebhookPaymentPayload) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WebhookPaymentPayload) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WebhookPaymentPayload) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *WebhookPaymentPayload) HasId() bool`

HasId returns a boolean if a field has been set.

### GetStatus

`func (o *WebhookPaymentPayload) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WebhookPaymentPayload) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WebhookPaymentPayload) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *WebhookPaymentPayload) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSubstatus

`func (o *WebhookPaymentPayload) GetSubstatus() string`

GetSubstatus returns the Substatus field if non-nil, zero value otherwise.

### GetSubstatusOk

`func (o *WebhookPaymentPayload) GetSubstatusOk() (*string, bool)`

GetSubstatusOk returns a tuple with the Substatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubstatus

`func (o *WebhookPaymentPayload) SetSubstatus(v string)`

SetSubstatus sets Substatus field to given value.

### HasSubstatus

`func (o *WebhookPaymentPayload) HasSubstatus() bool`

HasSubstatus returns a boolean if a field has been set.

### SetSubstatusNil

`func (o *WebhookPaymentPayload) SetSubstatusNil(b bool)`

 SetSubstatusNil sets the value for Substatus to be an explicit nil

### UnsetSubstatus
`func (o *WebhookPaymentPayload) UnsetSubstatus()`

UnsetSubstatus ensures that no value is present for Substatus, not even an explicit nil
### GetCustomerId

`func (o *WebhookPaymentPayload) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *WebhookPaymentPayload) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *WebhookPaymentPayload) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *WebhookPaymentPayload) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *WebhookPaymentPayload) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *WebhookPaymentPayload) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetCustomerEmail

`func (o *WebhookPaymentPayload) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *WebhookPaymentPayload) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *WebhookPaymentPayload) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *WebhookPaymentPayload) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### SetCustomerEmailNil

`func (o *WebhookPaymentPayload) SetCustomerEmailNil(b bool)`

 SetCustomerEmailNil sets the value for CustomerEmail to be an explicit nil

### UnsetCustomerEmail
`func (o *WebhookPaymentPayload) UnsetCustomerEmail()`

UnsetCustomerEmail ensures that no value is present for CustomerEmail, not even an explicit nil
### GetCustomerName

`func (o *WebhookPaymentPayload) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *WebhookPaymentPayload) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *WebhookPaymentPayload) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *WebhookPaymentPayload) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### SetCustomerNameNil

`func (o *WebhookPaymentPayload) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *WebhookPaymentPayload) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetCustomerUsername

`func (o *WebhookPaymentPayload) GetCustomerUsername() string`

GetCustomerUsername returns the CustomerUsername field if non-nil, zero value otherwise.

### GetCustomerUsernameOk

`func (o *WebhookPaymentPayload) GetCustomerUsernameOk() (*string, bool)`

GetCustomerUsernameOk returns a tuple with the CustomerUsername field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerUsername

`func (o *WebhookPaymentPayload) SetCustomerUsername(v string)`

SetCustomerUsername sets CustomerUsername field to given value.

### HasCustomerUsername

`func (o *WebhookPaymentPayload) HasCustomerUsername() bool`

HasCustomerUsername returns a boolean if a field has been set.

### SetCustomerUsernameNil

`func (o *WebhookPaymentPayload) SetCustomerUsernameNil(b bool)`

 SetCustomerUsernameNil sets the value for CustomerUsername to be an explicit nil

### UnsetCustomerUsername
`func (o *WebhookPaymentPayload) UnsetCustomerUsername()`

UnsetCustomerUsername ensures that no value is present for CustomerUsername, not even an explicit nil
### GetProductTitle

`func (o *WebhookPaymentPayload) GetProductTitle() string`

GetProductTitle returns the ProductTitle field if non-nil, zero value otherwise.

### GetProductTitleOk

`func (o *WebhookPaymentPayload) GetProductTitleOk() (*string, bool)`

GetProductTitleOk returns a tuple with the ProductTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductTitle

`func (o *WebhookPaymentPayload) SetProductTitle(v string)`

SetProductTitle sets ProductTitle field to given value.

### HasProductTitle

`func (o *WebhookPaymentPayload) HasProductTitle() bool`

HasProductTitle returns a boolean if a field has been set.

### SetProductTitleNil

`func (o *WebhookPaymentPayload) SetProductTitleNil(b bool)`

 SetProductTitleNil sets the value for ProductTitle to be an explicit nil

### UnsetProductTitle
`func (o *WebhookPaymentPayload) UnsetProductTitle()`

UnsetProductTitle ensures that no value is present for ProductTitle, not even an explicit nil
### GetProductRoute

`func (o *WebhookPaymentPayload) GetProductRoute() string`

GetProductRoute returns the ProductRoute field if non-nil, zero value otherwise.

### GetProductRouteOk

`func (o *WebhookPaymentPayload) GetProductRouteOk() (*string, bool)`

GetProductRouteOk returns a tuple with the ProductRoute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductRoute

`func (o *WebhookPaymentPayload) SetProductRoute(v string)`

SetProductRoute sets ProductRoute field to given value.

### HasProductRoute

`func (o *WebhookPaymentPayload) HasProductRoute() bool`

HasProductRoute returns a boolean if a field has been set.

### SetProductRouteNil

`func (o *WebhookPaymentPayload) SetProductRouteNil(b bool)`

 SetProductRouteNil sets the value for ProductRoute to be an explicit nil

### UnsetProductRoute
`func (o *WebhookPaymentPayload) UnsetProductRoute()`

UnsetProductRoute ensures that no value is present for ProductRoute, not even an explicit nil
### GetPlanId

`func (o *WebhookPaymentPayload) GetPlanId() string`

GetPlanId returns the PlanId field if non-nil, zero value otherwise.

### GetPlanIdOk

`func (o *WebhookPaymentPayload) GetPlanIdOk() (*string, bool)`

GetPlanIdOk returns a tuple with the PlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanId

`func (o *WebhookPaymentPayload) SetPlanId(v string)`

SetPlanId sets PlanId field to given value.

### HasPlanId

`func (o *WebhookPaymentPayload) HasPlanId() bool`

HasPlanId returns a boolean if a field has been set.

### SetPlanIdNil

`func (o *WebhookPaymentPayload) SetPlanIdNil(b bool)`

 SetPlanIdNil sets the value for PlanId to be an explicit nil

### UnsetPlanId
`func (o *WebhookPaymentPayload) UnsetPlanId()`

UnsetPlanId ensures that no value is present for PlanId, not even an explicit nil
### GetMembershipId

`func (o *WebhookPaymentPayload) GetMembershipId() string`

GetMembershipId returns the MembershipId field if non-nil, zero value otherwise.

### GetMembershipIdOk

`func (o *WebhookPaymentPayload) GetMembershipIdOk() (*string, bool)`

GetMembershipIdOk returns a tuple with the MembershipId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembershipId

`func (o *WebhookPaymentPayload) SetMembershipId(v string)`

SetMembershipId sets MembershipId field to given value.

### HasMembershipId

`func (o *WebhookPaymentPayload) HasMembershipId() bool`

HasMembershipId returns a boolean if a field has been set.

### SetMembershipIdNil

`func (o *WebhookPaymentPayload) SetMembershipIdNil(b bool)`

 SetMembershipIdNil sets the value for MembershipId to be an explicit nil

### UnsetMembershipId
`func (o *WebhookPaymentPayload) UnsetMembershipId()`

UnsetMembershipId ensures that no value is present for MembershipId, not even an explicit nil
### GetMembershipStatus

`func (o *WebhookPaymentPayload) GetMembershipStatus() string`

GetMembershipStatus returns the MembershipStatus field if non-nil, zero value otherwise.

### GetMembershipStatusOk

`func (o *WebhookPaymentPayload) GetMembershipStatusOk() (*string, bool)`

GetMembershipStatusOk returns a tuple with the MembershipStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembershipStatus

`func (o *WebhookPaymentPayload) SetMembershipStatus(v string)`

SetMembershipStatus sets MembershipStatus field to given value.

### HasMembershipStatus

`func (o *WebhookPaymentPayload) HasMembershipStatus() bool`

HasMembershipStatus returns a boolean if a field has been set.

### SetMembershipStatusNil

`func (o *WebhookPaymentPayload) SetMembershipStatusNil(b bool)`

 SetMembershipStatusNil sets the value for MembershipStatus to be an explicit nil

### UnsetMembershipStatus
`func (o *WebhookPaymentPayload) UnsetMembershipStatus()`

UnsetMembershipStatus ensures that no value is present for MembershipStatus, not even an explicit nil
### GetBillingReason

`func (o *WebhookPaymentPayload) GetBillingReason() string`

GetBillingReason returns the BillingReason field if non-nil, zero value otherwise.

### GetBillingReasonOk

`func (o *WebhookPaymentPayload) GetBillingReasonOk() (*string, bool)`

GetBillingReasonOk returns a tuple with the BillingReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingReason

`func (o *WebhookPaymentPayload) SetBillingReason(v string)`

SetBillingReason sets BillingReason field to given value.

### HasBillingReason

`func (o *WebhookPaymentPayload) HasBillingReason() bool`

HasBillingReason returns a boolean if a field has been set.

### SetBillingReasonNil

`func (o *WebhookPaymentPayload) SetBillingReasonNil(b bool)`

 SetBillingReasonNil sets the value for BillingReason to be an explicit nil

### UnsetBillingReason
`func (o *WebhookPaymentPayload) UnsetBillingReason()`

UnsetBillingReason ensures that no value is present for BillingReason, not even an explicit nil
### GetAmount

`func (o *WebhookPaymentPayload) GetAmount() string`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *WebhookPaymentPayload) GetAmountOk() (*string, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *WebhookPaymentPayload) SetAmount(v string)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *WebhookPaymentPayload) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### SetAmountNil

`func (o *WebhookPaymentPayload) SetAmountNil(b bool)`

 SetAmountNil sets the value for Amount to be an explicit nil

### UnsetAmount
`func (o *WebhookPaymentPayload) UnsetAmount()`

UnsetAmount ensures that no value is present for Amount, not even an explicit nil
### GetSubtotal

`func (o *WebhookPaymentPayload) GetSubtotal() string`

GetSubtotal returns the Subtotal field if non-nil, zero value otherwise.

### GetSubtotalOk

`func (o *WebhookPaymentPayload) GetSubtotalOk() (*string, bool)`

GetSubtotalOk returns a tuple with the Subtotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotal

`func (o *WebhookPaymentPayload) SetSubtotal(v string)`

SetSubtotal sets Subtotal field to given value.

### HasSubtotal

`func (o *WebhookPaymentPayload) HasSubtotal() bool`

HasSubtotal returns a boolean if a field has been set.

### SetSubtotalNil

`func (o *WebhookPaymentPayload) SetSubtotalNil(b bool)`

 SetSubtotalNil sets the value for Subtotal to be an explicit nil

### UnsetSubtotal
`func (o *WebhookPaymentPayload) UnsetSubtotal()`

UnsetSubtotal ensures that no value is present for Subtotal, not even an explicit nil
### GetUsdTotal

`func (o *WebhookPaymentPayload) GetUsdTotal() string`

GetUsdTotal returns the UsdTotal field if non-nil, zero value otherwise.

### GetUsdTotalOk

`func (o *WebhookPaymentPayload) GetUsdTotalOk() (*string, bool)`

GetUsdTotalOk returns a tuple with the UsdTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsdTotal

`func (o *WebhookPaymentPayload) SetUsdTotal(v string)`

SetUsdTotal sets UsdTotal field to given value.

### HasUsdTotal

`func (o *WebhookPaymentPayload) HasUsdTotal() bool`

HasUsdTotal returns a boolean if a field has been set.

### SetUsdTotalNil

`func (o *WebhookPaymentPayload) SetUsdTotalNil(b bool)`

 SetUsdTotalNil sets the value for UsdTotal to be an explicit nil

### UnsetUsdTotal
`func (o *WebhookPaymentPayload) UnsetUsdTotal()`

UnsetUsdTotal ensures that no value is present for UsdTotal, not even an explicit nil
### GetFeeAmount

`func (o *WebhookPaymentPayload) GetFeeAmount() string`

GetFeeAmount returns the FeeAmount field if non-nil, zero value otherwise.

### GetFeeAmountOk

`func (o *WebhookPaymentPayload) GetFeeAmountOk() (*string, bool)`

GetFeeAmountOk returns a tuple with the FeeAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeeAmount

`func (o *WebhookPaymentPayload) SetFeeAmount(v string)`

SetFeeAmount sets FeeAmount field to given value.

### HasFeeAmount

`func (o *WebhookPaymentPayload) HasFeeAmount() bool`

HasFeeAmount returns a boolean if a field has been set.

### SetFeeAmountNil

`func (o *WebhookPaymentPayload) SetFeeAmountNil(b bool)`

 SetFeeAmountNil sets the value for FeeAmount to be an explicit nil

### UnsetFeeAmount
`func (o *WebhookPaymentPayload) UnsetFeeAmount()`

UnsetFeeAmount ensures that no value is present for FeeAmount, not even an explicit nil
### GetAmountAfterFees

`func (o *WebhookPaymentPayload) GetAmountAfterFees() string`

GetAmountAfterFees returns the AmountAfterFees field if non-nil, zero value otherwise.

### GetAmountAfterFeesOk

`func (o *WebhookPaymentPayload) GetAmountAfterFeesOk() (*string, bool)`

GetAmountAfterFeesOk returns a tuple with the AmountAfterFees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountAfterFees

`func (o *WebhookPaymentPayload) SetAmountAfterFees(v string)`

SetAmountAfterFees sets AmountAfterFees field to given value.

### HasAmountAfterFees

`func (o *WebhookPaymentPayload) HasAmountAfterFees() bool`

HasAmountAfterFees returns a boolean if a field has been set.

### SetAmountAfterFeesNil

`func (o *WebhookPaymentPayload) SetAmountAfterFeesNil(b bool)`

 SetAmountAfterFeesNil sets the value for AmountAfterFees to be an explicit nil

### UnsetAmountAfterFees
`func (o *WebhookPaymentPayload) UnsetAmountAfterFees()`

UnsetAmountAfterFees ensures that no value is present for AmountAfterFees, not even an explicit nil
### GetTaxAmount

`func (o *WebhookPaymentPayload) GetTaxAmount() string`

GetTaxAmount returns the TaxAmount field if non-nil, zero value otherwise.

### GetTaxAmountOk

`func (o *WebhookPaymentPayload) GetTaxAmountOk() (*string, bool)`

GetTaxAmountOk returns a tuple with the TaxAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxAmount

`func (o *WebhookPaymentPayload) SetTaxAmount(v string)`

SetTaxAmount sets TaxAmount field to given value.

### HasTaxAmount

`func (o *WebhookPaymentPayload) HasTaxAmount() bool`

HasTaxAmount returns a boolean if a field has been set.

### SetTaxAmountNil

`func (o *WebhookPaymentPayload) SetTaxAmountNil(b bool)`

 SetTaxAmountNil sets the value for TaxAmount to be an explicit nil

### UnsetTaxAmount
`func (o *WebhookPaymentPayload) UnsetTaxAmount()`

UnsetTaxAmount ensures that no value is present for TaxAmount, not even an explicit nil
### GetTaxBehavior

`func (o *WebhookPaymentPayload) GetTaxBehavior() string`

GetTaxBehavior returns the TaxBehavior field if non-nil, zero value otherwise.

### GetTaxBehaviorOk

`func (o *WebhookPaymentPayload) GetTaxBehaviorOk() (*string, bool)`

GetTaxBehaviorOk returns a tuple with the TaxBehavior field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxBehavior

`func (o *WebhookPaymentPayload) SetTaxBehavior(v string)`

SetTaxBehavior sets TaxBehavior field to given value.

### HasTaxBehavior

`func (o *WebhookPaymentPayload) HasTaxBehavior() bool`

HasTaxBehavior returns a boolean if a field has been set.

### SetTaxBehaviorNil

`func (o *WebhookPaymentPayload) SetTaxBehaviorNil(b bool)`

 SetTaxBehaviorNil sets the value for TaxBehavior to be an explicit nil

### UnsetTaxBehavior
`func (o *WebhookPaymentPayload) UnsetTaxBehavior()`

UnsetTaxBehavior ensures that no value is present for TaxBehavior, not even an explicit nil
### GetTaxRefundedAmount

`func (o *WebhookPaymentPayload) GetTaxRefundedAmount() string`

GetTaxRefundedAmount returns the TaxRefundedAmount field if non-nil, zero value otherwise.

### GetTaxRefundedAmountOk

`func (o *WebhookPaymentPayload) GetTaxRefundedAmountOk() (*string, bool)`

GetTaxRefundedAmountOk returns a tuple with the TaxRefundedAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxRefundedAmount

`func (o *WebhookPaymentPayload) SetTaxRefundedAmount(v string)`

SetTaxRefundedAmount sets TaxRefundedAmount field to given value.

### HasTaxRefundedAmount

`func (o *WebhookPaymentPayload) HasTaxRefundedAmount() bool`

HasTaxRefundedAmount returns a boolean if a field has been set.

### SetTaxRefundedAmountNil

`func (o *WebhookPaymentPayload) SetTaxRefundedAmountNil(b bool)`

 SetTaxRefundedAmountNil sets the value for TaxRefundedAmount to be an explicit nil

### UnsetTaxRefundedAmount
`func (o *WebhookPaymentPayload) UnsetTaxRefundedAmount()`

UnsetTaxRefundedAmount ensures that no value is present for TaxRefundedAmount, not even an explicit nil
### GetRefundedAmount

`func (o *WebhookPaymentPayload) GetRefundedAmount() string`

GetRefundedAmount returns the RefundedAmount field if non-nil, zero value otherwise.

### GetRefundedAmountOk

`func (o *WebhookPaymentPayload) GetRefundedAmountOk() (*string, bool)`

GetRefundedAmountOk returns a tuple with the RefundedAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefundedAmount

`func (o *WebhookPaymentPayload) SetRefundedAmount(v string)`

SetRefundedAmount sets RefundedAmount field to given value.

### HasRefundedAmount

`func (o *WebhookPaymentPayload) HasRefundedAmount() bool`

HasRefundedAmount returns a boolean if a field has been set.

### GetSettlementAmount

`func (o *WebhookPaymentPayload) GetSettlementAmount() string`

GetSettlementAmount returns the SettlementAmount field if non-nil, zero value otherwise.

### GetSettlementAmountOk

`func (o *WebhookPaymentPayload) GetSettlementAmountOk() (*string, bool)`

GetSettlementAmountOk returns a tuple with the SettlementAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettlementAmount

`func (o *WebhookPaymentPayload) SetSettlementAmount(v string)`

SetSettlementAmount sets SettlementAmount field to given value.

### HasSettlementAmount

`func (o *WebhookPaymentPayload) HasSettlementAmount() bool`

HasSettlementAmount returns a boolean if a field has been set.

### SetSettlementAmountNil

`func (o *WebhookPaymentPayload) SetSettlementAmountNil(b bool)`

 SetSettlementAmountNil sets the value for SettlementAmount to be an explicit nil

### UnsetSettlementAmount
`func (o *WebhookPaymentPayload) UnsetSettlementAmount()`

UnsetSettlementAmount ensures that no value is present for SettlementAmount, not even an explicit nil
### GetSettlementCurrency

`func (o *WebhookPaymentPayload) GetSettlementCurrency() string`

GetSettlementCurrency returns the SettlementCurrency field if non-nil, zero value otherwise.

### GetSettlementCurrencyOk

`func (o *WebhookPaymentPayload) GetSettlementCurrencyOk() (*string, bool)`

GetSettlementCurrencyOk returns a tuple with the SettlementCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettlementCurrency

`func (o *WebhookPaymentPayload) SetSettlementCurrency(v string)`

SetSettlementCurrency sets SettlementCurrency field to given value.

### HasSettlementCurrency

`func (o *WebhookPaymentPayload) HasSettlementCurrency() bool`

HasSettlementCurrency returns a boolean if a field has been set.

### SetSettlementCurrencyNil

`func (o *WebhookPaymentPayload) SetSettlementCurrencyNil(b bool)`

 SetSettlementCurrencyNil sets the value for SettlementCurrency to be an explicit nil

### UnsetSettlementCurrency
`func (o *WebhookPaymentPayload) UnsetSettlementCurrency()`

UnsetSettlementCurrency ensures that no value is present for SettlementCurrency, not even an explicit nil
### GetSettlementExchangeRate

`func (o *WebhookPaymentPayload) GetSettlementExchangeRate() string`

GetSettlementExchangeRate returns the SettlementExchangeRate field if non-nil, zero value otherwise.

### GetSettlementExchangeRateOk

`func (o *WebhookPaymentPayload) GetSettlementExchangeRateOk() (*string, bool)`

GetSettlementExchangeRateOk returns a tuple with the SettlementExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettlementExchangeRate

`func (o *WebhookPaymentPayload) SetSettlementExchangeRate(v string)`

SetSettlementExchangeRate sets SettlementExchangeRate field to given value.

### HasSettlementExchangeRate

`func (o *WebhookPaymentPayload) HasSettlementExchangeRate() bool`

HasSettlementExchangeRate returns a boolean if a field has been set.

### SetSettlementExchangeRateNil

`func (o *WebhookPaymentPayload) SetSettlementExchangeRateNil(b bool)`

 SetSettlementExchangeRateNil sets the value for SettlementExchangeRate to be an explicit nil

### UnsetSettlementExchangeRate
`func (o *WebhookPaymentPayload) UnsetSettlementExchangeRate()`

UnsetSettlementExchangeRate ensures that no value is present for SettlementExchangeRate, not even an explicit nil
### GetCurrency

`func (o *WebhookPaymentPayload) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *WebhookPaymentPayload) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *WebhookPaymentPayload) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *WebhookPaymentPayload) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetRefundable

`func (o *WebhookPaymentPayload) GetRefundable() bool`

GetRefundable returns the Refundable field if non-nil, zero value otherwise.

### GetRefundableOk

`func (o *WebhookPaymentPayload) GetRefundableOk() (*bool, bool)`

GetRefundableOk returns a tuple with the Refundable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefundable

`func (o *WebhookPaymentPayload) SetRefundable(v bool)`

SetRefundable sets Refundable field to given value.

### HasRefundable

`func (o *WebhookPaymentPayload) HasRefundable() bool`

HasRefundable returns a boolean if a field has been set.

### GetRetryable

`func (o *WebhookPaymentPayload) GetRetryable() bool`

GetRetryable returns the Retryable field if non-nil, zero value otherwise.

### GetRetryableOk

`func (o *WebhookPaymentPayload) GetRetryableOk() (*bool, bool)`

GetRetryableOk returns a tuple with the Retryable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryable

`func (o *WebhookPaymentPayload) SetRetryable(v bool)`

SetRetryable sets Retryable field to given value.

### HasRetryable

`func (o *WebhookPaymentPayload) HasRetryable() bool`

HasRetryable returns a boolean if a field has been set.

### GetAutoRefunded

`func (o *WebhookPaymentPayload) GetAutoRefunded() bool`

GetAutoRefunded returns the AutoRefunded field if non-nil, zero value otherwise.

### GetAutoRefundedOk

`func (o *WebhookPaymentPayload) GetAutoRefundedOk() (*bool, bool)`

GetAutoRefundedOk returns a tuple with the AutoRefunded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoRefunded

`func (o *WebhookPaymentPayload) SetAutoRefunded(v bool)`

SetAutoRefunded sets AutoRefunded field to given value.

### HasAutoRefunded

`func (o *WebhookPaymentPayload) HasAutoRefunded() bool`

HasAutoRefunded returns a boolean if a field has been set.

### GetPaymentMethod

`func (o *WebhookPaymentPayload) GetPaymentMethod() string`

GetPaymentMethod returns the PaymentMethod field if non-nil, zero value otherwise.

### GetPaymentMethodOk

`func (o *WebhookPaymentPayload) GetPaymentMethodOk() (*string, bool)`

GetPaymentMethodOk returns a tuple with the PaymentMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentMethod

`func (o *WebhookPaymentPayload) SetPaymentMethod(v string)`

SetPaymentMethod sets PaymentMethod field to given value.

### HasPaymentMethod

`func (o *WebhookPaymentPayload) HasPaymentMethod() bool`

HasPaymentMethod returns a boolean if a field has been set.

### SetPaymentMethodNil

`func (o *WebhookPaymentPayload) SetPaymentMethodNil(b bool)`

 SetPaymentMethodNil sets the value for PaymentMethod to be an explicit nil

### UnsetPaymentMethod
`func (o *WebhookPaymentPayload) UnsetPaymentMethod()`

UnsetPaymentMethod ensures that no value is present for PaymentMethod, not even an explicit nil
### GetCardBrand

`func (o *WebhookPaymentPayload) GetCardBrand() string`

GetCardBrand returns the CardBrand field if non-nil, zero value otherwise.

### GetCardBrandOk

`func (o *WebhookPaymentPayload) GetCardBrandOk() (*string, bool)`

GetCardBrandOk returns a tuple with the CardBrand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCardBrand

`func (o *WebhookPaymentPayload) SetCardBrand(v string)`

SetCardBrand sets CardBrand field to given value.

### HasCardBrand

`func (o *WebhookPaymentPayload) HasCardBrand() bool`

HasCardBrand returns a boolean if a field has been set.

### SetCardBrandNil

`func (o *WebhookPaymentPayload) SetCardBrandNil(b bool)`

 SetCardBrandNil sets the value for CardBrand to be an explicit nil

### UnsetCardBrand
`func (o *WebhookPaymentPayload) UnsetCardBrand()`

UnsetCardBrand ensures that no value is present for CardBrand, not even an explicit nil
### GetCardLast4

`func (o *WebhookPaymentPayload) GetCardLast4() string`

GetCardLast4 returns the CardLast4 field if non-nil, zero value otherwise.

### GetCardLast4Ok

`func (o *WebhookPaymentPayload) GetCardLast4Ok() (*string, bool)`

GetCardLast4Ok returns a tuple with the CardLast4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCardLast4

`func (o *WebhookPaymentPayload) SetCardLast4(v string)`

SetCardLast4 sets CardLast4 field to given value.

### HasCardLast4

`func (o *WebhookPaymentPayload) HasCardLast4() bool`

HasCardLast4 returns a boolean if a field has been set.

### SetCardLast4Nil

`func (o *WebhookPaymentPayload) SetCardLast4Nil(b bool)`

 SetCardLast4Nil sets the value for CardLast4 to be an explicit nil

### UnsetCardLast4
`func (o *WebhookPaymentPayload) UnsetCardLast4()`

UnsetCardLast4 ensures that no value is present for CardLast4, not even an explicit nil
### GetCardExpMonth

`func (o *WebhookPaymentPayload) GetCardExpMonth() int32`

GetCardExpMonth returns the CardExpMonth field if non-nil, zero value otherwise.

### GetCardExpMonthOk

`func (o *WebhookPaymentPayload) GetCardExpMonthOk() (*int32, bool)`

GetCardExpMonthOk returns a tuple with the CardExpMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCardExpMonth

`func (o *WebhookPaymentPayload) SetCardExpMonth(v int32)`

SetCardExpMonth sets CardExpMonth field to given value.

### HasCardExpMonth

`func (o *WebhookPaymentPayload) HasCardExpMonth() bool`

HasCardExpMonth returns a boolean if a field has been set.

### SetCardExpMonthNil

`func (o *WebhookPaymentPayload) SetCardExpMonthNil(b bool)`

 SetCardExpMonthNil sets the value for CardExpMonth to be an explicit nil

### UnsetCardExpMonth
`func (o *WebhookPaymentPayload) UnsetCardExpMonth()`

UnsetCardExpMonth ensures that no value is present for CardExpMonth, not even an explicit nil
### GetCardExpYear

`func (o *WebhookPaymentPayload) GetCardExpYear() int32`

GetCardExpYear returns the CardExpYear field if non-nil, zero value otherwise.

### GetCardExpYearOk

`func (o *WebhookPaymentPayload) GetCardExpYearOk() (*int32, bool)`

GetCardExpYearOk returns a tuple with the CardExpYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCardExpYear

`func (o *WebhookPaymentPayload) SetCardExpYear(v int32)`

SetCardExpYear sets CardExpYear field to given value.

### HasCardExpYear

`func (o *WebhookPaymentPayload) HasCardExpYear() bool`

HasCardExpYear returns a boolean if a field has been set.

### SetCardExpYearNil

`func (o *WebhookPaymentPayload) SetCardExpYearNil(b bool)`

 SetCardExpYearNil sets the value for CardExpYear to be an explicit nil

### UnsetCardExpYear
`func (o *WebhookPaymentPayload) UnsetCardExpYear()`

UnsetCardExpYear ensures that no value is present for CardExpYear, not even an explicit nil
### GetBillingAddress

`func (o *WebhookPaymentPayload) GetBillingAddress() WebhookPaymentPayloadBillingAddress`

GetBillingAddress returns the BillingAddress field if non-nil, zero value otherwise.

### GetBillingAddressOk

`func (o *WebhookPaymentPayload) GetBillingAddressOk() (*WebhookPaymentPayloadBillingAddress, bool)`

GetBillingAddressOk returns a tuple with the BillingAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingAddress

`func (o *WebhookPaymentPayload) SetBillingAddress(v WebhookPaymentPayloadBillingAddress)`

SetBillingAddress sets BillingAddress field to given value.

### HasBillingAddress

`func (o *WebhookPaymentPayload) HasBillingAddress() bool`

HasBillingAddress returns a boolean if a field has been set.

### SetBillingAddressNil

`func (o *WebhookPaymentPayload) SetBillingAddressNil(b bool)`

 SetBillingAddressNil sets the value for BillingAddress to be an explicit nil

### UnsetBillingAddress
`func (o *WebhookPaymentPayload) UnsetBillingAddress()`

UnsetBillingAddress ensures that no value is present for BillingAddress, not even an explicit nil
### GetLicenseKey

`func (o *WebhookPaymentPayload) GetLicenseKey() string`

GetLicenseKey returns the LicenseKey field if non-nil, zero value otherwise.

### GetLicenseKeyOk

`func (o *WebhookPaymentPayload) GetLicenseKeyOk() (*string, bool)`

GetLicenseKeyOk returns a tuple with the LicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseKey

`func (o *WebhookPaymentPayload) SetLicenseKey(v string)`

SetLicenseKey sets LicenseKey field to given value.

### HasLicenseKey

`func (o *WebhookPaymentPayload) HasLicenseKey() bool`

HasLicenseKey returns a boolean if a field has been set.

### SetLicenseKeyNil

`func (o *WebhookPaymentPayload) SetLicenseKeyNil(b bool)`

 SetLicenseKeyNil sets the value for LicenseKey to be an explicit nil

### UnsetLicenseKey
`func (o *WebhookPaymentPayload) UnsetLicenseKey()`

UnsetLicenseKey ensures that no value is present for LicenseKey, not even an explicit nil
### GetFilesSnapshot

`func (o *WebhookPaymentPayload) GetFilesSnapshot() []map[string]interface{}`

GetFilesSnapshot returns the FilesSnapshot field if non-nil, zero value otherwise.

### GetFilesSnapshotOk

`func (o *WebhookPaymentPayload) GetFilesSnapshotOk() (*[]map[string]interface{}, bool)`

GetFilesSnapshotOk returns a tuple with the FilesSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesSnapshot

`func (o *WebhookPaymentPayload) SetFilesSnapshot(v []map[string]interface{})`

SetFilesSnapshot sets FilesSnapshot field to given value.

### HasFilesSnapshot

`func (o *WebhookPaymentPayload) HasFilesSnapshot() bool`

HasFilesSnapshot returns a boolean if a field has been set.

### SetFilesSnapshotNil

`func (o *WebhookPaymentPayload) SetFilesSnapshotNil(b bool)`

 SetFilesSnapshotNil sets the value for FilesSnapshot to be an explicit nil

### UnsetFilesSnapshot
`func (o *WebhookPaymentPayload) UnsetFilesSnapshot()`

UnsetFilesSnapshot ensures that no value is present for FilesSnapshot, not even an explicit nil
### GetCheckoutId

`func (o *WebhookPaymentPayload) GetCheckoutId() string`

GetCheckoutId returns the CheckoutId field if non-nil, zero value otherwise.

### GetCheckoutIdOk

`func (o *WebhookPaymentPayload) GetCheckoutIdOk() (*string, bool)`

GetCheckoutIdOk returns a tuple with the CheckoutId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutId

`func (o *WebhookPaymentPayload) SetCheckoutId(v string)`

SetCheckoutId sets CheckoutId field to given value.

### HasCheckoutId

`func (o *WebhookPaymentPayload) HasCheckoutId() bool`

HasCheckoutId returns a boolean if a field has been set.

### SetCheckoutIdNil

`func (o *WebhookPaymentPayload) SetCheckoutIdNil(b bool)`

 SetCheckoutIdNil sets the value for CheckoutId to be an explicit nil

### UnsetCheckoutId
`func (o *WebhookPaymentPayload) UnsetCheckoutId()`

UnsetCheckoutId ensures that no value is present for CheckoutId, not even an explicit nil
### GetDiscountCode

`func (o *WebhookPaymentPayload) GetDiscountCode() string`

GetDiscountCode returns the DiscountCode field if non-nil, zero value otherwise.

### GetDiscountCodeOk

`func (o *WebhookPaymentPayload) GetDiscountCodeOk() (*string, bool)`

GetDiscountCodeOk returns a tuple with the DiscountCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountCode

`func (o *WebhookPaymentPayload) SetDiscountCode(v string)`

SetDiscountCode sets DiscountCode field to given value.

### HasDiscountCode

`func (o *WebhookPaymentPayload) HasDiscountCode() bool`

HasDiscountCode returns a boolean if a field has been set.

### SetDiscountCodeNil

`func (o *WebhookPaymentPayload) SetDiscountCodeNil(b bool)`

 SetDiscountCodeNil sets the value for DiscountCode to be an explicit nil

### UnsetDiscountCode
`func (o *WebhookPaymentPayload) UnsetDiscountCode()`

UnsetDiscountCode ensures that no value is present for DiscountCode, not even an explicit nil
### GetFailureMessage

`func (o *WebhookPaymentPayload) GetFailureMessage() string`

GetFailureMessage returns the FailureMessage field if non-nil, zero value otherwise.

### GetFailureMessageOk

`func (o *WebhookPaymentPayload) GetFailureMessageOk() (*string, bool)`

GetFailureMessageOk returns a tuple with the FailureMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureMessage

`func (o *WebhookPaymentPayload) SetFailureMessage(v string)`

SetFailureMessage sets FailureMessage field to given value.

### HasFailureMessage

`func (o *WebhookPaymentPayload) HasFailureMessage() bool`

HasFailureMessage returns a boolean if a field has been set.

### SetFailureMessageNil

`func (o *WebhookPaymentPayload) SetFailureMessageNil(b bool)`

 SetFailureMessageNil sets the value for FailureMessage to be an explicit nil

### UnsetFailureMessage
`func (o *WebhookPaymentPayload) UnsetFailureMessage()`

UnsetFailureMessage ensures that no value is present for FailureMessage, not even an explicit nil
### GetPaidAt

`func (o *WebhookPaymentPayload) GetPaidAt() time.Time`

GetPaidAt returns the PaidAt field if non-nil, zero value otherwise.

### GetPaidAtOk

`func (o *WebhookPaymentPayload) GetPaidAtOk() (*time.Time, bool)`

GetPaidAtOk returns a tuple with the PaidAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidAt

`func (o *WebhookPaymentPayload) SetPaidAt(v time.Time)`

SetPaidAt sets PaidAt field to given value.

### HasPaidAt

`func (o *WebhookPaymentPayload) HasPaidAt() bool`

HasPaidAt returns a boolean if a field has been set.

### SetPaidAtNil

`func (o *WebhookPaymentPayload) SetPaidAtNil(b bool)`

 SetPaidAtNil sets the value for PaidAt to be an explicit nil

### UnsetPaidAt
`func (o *WebhookPaymentPayload) UnsetPaidAt()`

UnsetPaidAt ensures that no value is present for PaidAt, not even an explicit nil
### GetRefundedAt

`func (o *WebhookPaymentPayload) GetRefundedAt() time.Time`

GetRefundedAt returns the RefundedAt field if non-nil, zero value otherwise.

### GetRefundedAtOk

`func (o *WebhookPaymentPayload) GetRefundedAtOk() (*time.Time, bool)`

GetRefundedAtOk returns a tuple with the RefundedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefundedAt

`func (o *WebhookPaymentPayload) SetRefundedAt(v time.Time)`

SetRefundedAt sets RefundedAt field to given value.

### HasRefundedAt

`func (o *WebhookPaymentPayload) HasRefundedAt() bool`

HasRefundedAt returns a boolean if a field has been set.

### SetRefundedAtNil

`func (o *WebhookPaymentPayload) SetRefundedAtNil(b bool)`

 SetRefundedAtNil sets the value for RefundedAt to be an explicit nil

### UnsetRefundedAt
`func (o *WebhookPaymentPayload) UnsetRefundedAt()`

UnsetRefundedAt ensures that no value is present for RefundedAt, not even an explicit nil
### GetDisputeAlertedAt

`func (o *WebhookPaymentPayload) GetDisputeAlertedAt() time.Time`

GetDisputeAlertedAt returns the DisputeAlertedAt field if non-nil, zero value otherwise.

### GetDisputeAlertedAtOk

`func (o *WebhookPaymentPayload) GetDisputeAlertedAtOk() (*time.Time, bool)`

GetDisputeAlertedAtOk returns a tuple with the DisputeAlertedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisputeAlertedAt

`func (o *WebhookPaymentPayload) SetDisputeAlertedAt(v time.Time)`

SetDisputeAlertedAt sets DisputeAlertedAt field to given value.

### HasDisputeAlertedAt

`func (o *WebhookPaymentPayload) HasDisputeAlertedAt() bool`

HasDisputeAlertedAt returns a boolean if a field has been set.

### SetDisputeAlertedAtNil

`func (o *WebhookPaymentPayload) SetDisputeAlertedAtNil(b bool)`

 SetDisputeAlertedAtNil sets the value for DisputeAlertedAt to be an explicit nil

### UnsetDisputeAlertedAt
`func (o *WebhookPaymentPayload) UnsetDisputeAlertedAt()`

UnsetDisputeAlertedAt ensures that no value is present for DisputeAlertedAt, not even an explicit nil
### GetLastPaymentAttempt

`func (o *WebhookPaymentPayload) GetLastPaymentAttempt() time.Time`

GetLastPaymentAttempt returns the LastPaymentAttempt field if non-nil, zero value otherwise.

### GetLastPaymentAttemptOk

`func (o *WebhookPaymentPayload) GetLastPaymentAttemptOk() (*time.Time, bool)`

GetLastPaymentAttemptOk returns a tuple with the LastPaymentAttempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPaymentAttempt

`func (o *WebhookPaymentPayload) SetLastPaymentAttempt(v time.Time)`

SetLastPaymentAttempt sets LastPaymentAttempt field to given value.

### HasLastPaymentAttempt

`func (o *WebhookPaymentPayload) HasLastPaymentAttempt() bool`

HasLastPaymentAttempt returns a boolean if a field has been set.

### SetLastPaymentAttemptNil

`func (o *WebhookPaymentPayload) SetLastPaymentAttemptNil(b bool)`

 SetLastPaymentAttemptNil sets the value for LastPaymentAttempt to be an explicit nil

### UnsetLastPaymentAttempt
`func (o *WebhookPaymentPayload) UnsetLastPaymentAttempt()`

UnsetLastPaymentAttempt ensures that no value is present for LastPaymentAttempt, not even an explicit nil
### GetNextPaymentAttempt

`func (o *WebhookPaymentPayload) GetNextPaymentAttempt() time.Time`

GetNextPaymentAttempt returns the NextPaymentAttempt field if non-nil, zero value otherwise.

### GetNextPaymentAttemptOk

`func (o *WebhookPaymentPayload) GetNextPaymentAttemptOk() (*time.Time, bool)`

GetNextPaymentAttemptOk returns a tuple with the NextPaymentAttempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPaymentAttempt

`func (o *WebhookPaymentPayload) SetNextPaymentAttempt(v time.Time)`

SetNextPaymentAttempt sets NextPaymentAttempt field to given value.

### HasNextPaymentAttempt

`func (o *WebhookPaymentPayload) HasNextPaymentAttempt() bool`

HasNextPaymentAttempt returns a boolean if a field has been set.

### SetNextPaymentAttemptNil

`func (o *WebhookPaymentPayload) SetNextPaymentAttemptNil(b bool)`

 SetNextPaymentAttemptNil sets the value for NextPaymentAttempt to be an explicit nil

### UnsetNextPaymentAttempt
`func (o *WebhookPaymentPayload) UnsetNextPaymentAttempt()`

UnsetNextPaymentAttempt ensures that no value is present for NextPaymentAttempt, not even an explicit nil
### GetCreatedAt

`func (o *WebhookPaymentPayload) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WebhookPaymentPayload) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WebhookPaymentPayload) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *WebhookPaymentPayload) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *WebhookPaymentPayload) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *WebhookPaymentPayload) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *WebhookPaymentPayload) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *WebhookPaymentPayload) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetPaymentEventType

`func (o *WebhookPaymentPayload) GetPaymentEventType() string`

GetPaymentEventType returns the PaymentEventType field if non-nil, zero value otherwise.

### GetPaymentEventTypeOk

`func (o *WebhookPaymentPayload) GetPaymentEventTypeOk() (*string, bool)`

GetPaymentEventTypeOk returns a tuple with the PaymentEventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentEventType

`func (o *WebhookPaymentPayload) SetPaymentEventType(v string)`

SetPaymentEventType sets PaymentEventType field to given value.

### HasPaymentEventType

`func (o *WebhookPaymentPayload) HasPaymentEventType() bool`

HasPaymentEventType returns a boolean if a field has been set.

### SetPaymentEventTypeNil

`func (o *WebhookPaymentPayload) SetPaymentEventTypeNil(b bool)`

 SetPaymentEventTypeNil sets the value for PaymentEventType to be an explicit nil

### UnsetPaymentEventType
`func (o *WebhookPaymentPayload) UnsetPaymentEventType()`

UnsetPaymentEventType ensures that no value is present for PaymentEventType, not even an explicit nil
### GetLastEventType

`func (o *WebhookPaymentPayload) GetLastEventType() string`

GetLastEventType returns the LastEventType field if non-nil, zero value otherwise.

### GetLastEventTypeOk

`func (o *WebhookPaymentPayload) GetLastEventTypeOk() (*string, bool)`

GetLastEventTypeOk returns a tuple with the LastEventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastEventType

`func (o *WebhookPaymentPayload) SetLastEventType(v string)`

SetLastEventType sets LastEventType field to given value.

### HasLastEventType

`func (o *WebhookPaymentPayload) HasLastEventType() bool`

HasLastEventType returns a boolean if a field has been set.

### SetLastEventTypeNil

`func (o *WebhookPaymentPayload) SetLastEventTypeNil(b bool)`

 SetLastEventTypeNil sets the value for LastEventType to be an explicit nil

### UnsetLastEventType
`func (o *WebhookPaymentPayload) UnsetLastEventType()`

UnsetLastEventType ensures that no value is present for LastEventType, not even an explicit nil
### GetBusinessId

`func (o *WebhookPaymentPayload) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *WebhookPaymentPayload) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *WebhookPaymentPayload) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.

### HasBusinessId

`func (o *WebhookPaymentPayload) HasBusinessId() bool`

HasBusinessId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


