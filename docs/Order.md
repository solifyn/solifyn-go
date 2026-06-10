# Order

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique internal database identifier. | 
**InvoiceUrl** | **string** | The invoice print URL. | 
**Customer** | [**OrderCustomer**](OrderCustomer.md) | Customer details. | 
**TotalAmount** | **int32** | Total paid amount in cents. | 
**Subtotal** | **int32** | Subtotal amount in cents. | 
**UsdTotal** | Pointer to **float32** | Total paid amount converted to USD. | [optional] 
**TaxAmount** | **int32** | Tax amount in cents. | 
**ApplicationFee** | **int32** | Application fee in cents. | 
**AmountAfterFees** | **int32** | Net amount after fees in cents. | 
**Currency** | **string** | Currency code. | 
**Status** | **string** | Current status of the payment. | 
**CreatedAt** | **time.Time** | Payment creation timestamp. | 
**PaidAt** | Pointer to **time.Time** | Payment completion/paid timestamp. | [optional] 
**PaymentMethod** | **string** | Payment method utilized. | 
**CardLastFour** | Pointer to **string** | Last four digits of card used. | [optional] 
**CardNetwork** | Pointer to **string** | Card network/brand. | [optional] 
**CardType** | Pointer to **string** | Card type. | [optional] 
**Billing** | Pointer to [**OrderBilling**](OrderBilling.md) | Billing address details. | [optional] 
**ProductCart** | [**[]OrderProductCart**](OrderProductCart.md) | Products purchased in this order. | 
**Metadata** | Pointer to **map[string]interface{}** | Custom metadata payload associated with this payment. | [optional] 
**Order** | Pointer to [**OrderDetail**](OrderDetail.md) | Order details snapshot. | [optional] 
**Refundable** | **bool** | Indicates whether the order is eligible for refund. | 
**Refunds** | Pointer to [**[]OrderRefund**](OrderRefund.md) | List of refunds associated with this payment. | [optional] 
**BusinessId** | **string** | Business unique ID identifier. | 
**BusinessName** | **string** | Business display title/name. | 
**BillingReason** | Pointer to **string** | Billing reason detail. | [optional] 

## Methods

### NewOrder

`func NewOrder(id string, invoiceUrl string, customer OrderCustomer, totalAmount int32, subtotal int32, taxAmount int32, applicationFee int32, amountAfterFees int32, currency string, status string, createdAt time.Time, paymentMethod string, productCart []OrderProductCart, refundable bool, businessId string, businessName string, ) *Order`

NewOrder instantiates a new Order object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderWithDefaults

`func NewOrderWithDefaults() *Order`

NewOrderWithDefaults instantiates a new Order object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Order) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Order) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Order) SetId(v string)`

SetId sets Id field to given value.


### GetInvoiceUrl

`func (o *Order) GetInvoiceUrl() string`

GetInvoiceUrl returns the InvoiceUrl field if non-nil, zero value otherwise.

### GetInvoiceUrlOk

`func (o *Order) GetInvoiceUrlOk() (*string, bool)`

GetInvoiceUrlOk returns a tuple with the InvoiceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceUrl

`func (o *Order) SetInvoiceUrl(v string)`

SetInvoiceUrl sets InvoiceUrl field to given value.


### GetCustomer

`func (o *Order) GetCustomer() OrderCustomer`

GetCustomer returns the Customer field if non-nil, zero value otherwise.

### GetCustomerOk

`func (o *Order) GetCustomerOk() (*OrderCustomer, bool)`

GetCustomerOk returns a tuple with the Customer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomer

`func (o *Order) SetCustomer(v OrderCustomer)`

SetCustomer sets Customer field to given value.


### GetTotalAmount

`func (o *Order) GetTotalAmount() int32`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *Order) GetTotalAmountOk() (*int32, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *Order) SetTotalAmount(v int32)`

SetTotalAmount sets TotalAmount field to given value.


### GetSubtotal

`func (o *Order) GetSubtotal() int32`

GetSubtotal returns the Subtotal field if non-nil, zero value otherwise.

### GetSubtotalOk

`func (o *Order) GetSubtotalOk() (*int32, bool)`

GetSubtotalOk returns a tuple with the Subtotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotal

`func (o *Order) SetSubtotal(v int32)`

SetSubtotal sets Subtotal field to given value.


### GetUsdTotal

`func (o *Order) GetUsdTotal() float32`

GetUsdTotal returns the UsdTotal field if non-nil, zero value otherwise.

### GetUsdTotalOk

`func (o *Order) GetUsdTotalOk() (*float32, bool)`

GetUsdTotalOk returns a tuple with the UsdTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsdTotal

`func (o *Order) SetUsdTotal(v float32)`

SetUsdTotal sets UsdTotal field to given value.

### HasUsdTotal

`func (o *Order) HasUsdTotal() bool`

HasUsdTotal returns a boolean if a field has been set.

### GetTaxAmount

`func (o *Order) GetTaxAmount() int32`

GetTaxAmount returns the TaxAmount field if non-nil, zero value otherwise.

### GetTaxAmountOk

`func (o *Order) GetTaxAmountOk() (*int32, bool)`

GetTaxAmountOk returns a tuple with the TaxAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxAmount

`func (o *Order) SetTaxAmount(v int32)`

SetTaxAmount sets TaxAmount field to given value.


### GetApplicationFee

`func (o *Order) GetApplicationFee() int32`

GetApplicationFee returns the ApplicationFee field if non-nil, zero value otherwise.

### GetApplicationFeeOk

`func (o *Order) GetApplicationFeeOk() (*int32, bool)`

GetApplicationFeeOk returns a tuple with the ApplicationFee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationFee

`func (o *Order) SetApplicationFee(v int32)`

SetApplicationFee sets ApplicationFee field to given value.


### GetAmountAfterFees

`func (o *Order) GetAmountAfterFees() int32`

GetAmountAfterFees returns the AmountAfterFees field if non-nil, zero value otherwise.

### GetAmountAfterFeesOk

`func (o *Order) GetAmountAfterFeesOk() (*int32, bool)`

GetAmountAfterFeesOk returns a tuple with the AmountAfterFees field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountAfterFees

`func (o *Order) SetAmountAfterFees(v int32)`

SetAmountAfterFees sets AmountAfterFees field to given value.


### GetCurrency

`func (o *Order) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Order) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Order) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetStatus

`func (o *Order) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Order) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Order) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *Order) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Order) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Order) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetPaidAt

`func (o *Order) GetPaidAt() time.Time`

GetPaidAt returns the PaidAt field if non-nil, zero value otherwise.

### GetPaidAtOk

`func (o *Order) GetPaidAtOk() (*time.Time, bool)`

GetPaidAtOk returns a tuple with the PaidAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidAt

`func (o *Order) SetPaidAt(v time.Time)`

SetPaidAt sets PaidAt field to given value.

### HasPaidAt

`func (o *Order) HasPaidAt() bool`

HasPaidAt returns a boolean if a field has been set.

### GetPaymentMethod

`func (o *Order) GetPaymentMethod() string`

GetPaymentMethod returns the PaymentMethod field if non-nil, zero value otherwise.

### GetPaymentMethodOk

`func (o *Order) GetPaymentMethodOk() (*string, bool)`

GetPaymentMethodOk returns a tuple with the PaymentMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentMethod

`func (o *Order) SetPaymentMethod(v string)`

SetPaymentMethod sets PaymentMethod field to given value.


### GetCardLastFour

`func (o *Order) GetCardLastFour() string`

GetCardLastFour returns the CardLastFour field if non-nil, zero value otherwise.

### GetCardLastFourOk

`func (o *Order) GetCardLastFourOk() (*string, bool)`

GetCardLastFourOk returns a tuple with the CardLastFour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCardLastFour

`func (o *Order) SetCardLastFour(v string)`

SetCardLastFour sets CardLastFour field to given value.

### HasCardLastFour

`func (o *Order) HasCardLastFour() bool`

HasCardLastFour returns a boolean if a field has been set.

### GetCardNetwork

`func (o *Order) GetCardNetwork() string`

GetCardNetwork returns the CardNetwork field if non-nil, zero value otherwise.

### GetCardNetworkOk

`func (o *Order) GetCardNetworkOk() (*string, bool)`

GetCardNetworkOk returns a tuple with the CardNetwork field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCardNetwork

`func (o *Order) SetCardNetwork(v string)`

SetCardNetwork sets CardNetwork field to given value.

### HasCardNetwork

`func (o *Order) HasCardNetwork() bool`

HasCardNetwork returns a boolean if a field has been set.

### GetCardType

`func (o *Order) GetCardType() string`

GetCardType returns the CardType field if non-nil, zero value otherwise.

### GetCardTypeOk

`func (o *Order) GetCardTypeOk() (*string, bool)`

GetCardTypeOk returns a tuple with the CardType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCardType

`func (o *Order) SetCardType(v string)`

SetCardType sets CardType field to given value.

### HasCardType

`func (o *Order) HasCardType() bool`

HasCardType returns a boolean if a field has been set.

### GetBilling

`func (o *Order) GetBilling() OrderBilling`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *Order) GetBillingOk() (*OrderBilling, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *Order) SetBilling(v OrderBilling)`

SetBilling sets Billing field to given value.

### HasBilling

`func (o *Order) HasBilling() bool`

HasBilling returns a boolean if a field has been set.

### GetProductCart

`func (o *Order) GetProductCart() []OrderProductCart`

GetProductCart returns the ProductCart field if non-nil, zero value otherwise.

### GetProductCartOk

`func (o *Order) GetProductCartOk() (*[]OrderProductCart, bool)`

GetProductCartOk returns a tuple with the ProductCart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductCart

`func (o *Order) SetProductCart(v []OrderProductCart)`

SetProductCart sets ProductCart field to given value.


### GetMetadata

`func (o *Order) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Order) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Order) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *Order) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetOrder

`func (o *Order) GetOrder() OrderDetail`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *Order) GetOrderOk() (*OrderDetail, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *Order) SetOrder(v OrderDetail)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *Order) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetRefundable

`func (o *Order) GetRefundable() bool`

GetRefundable returns the Refundable field if non-nil, zero value otherwise.

### GetRefundableOk

`func (o *Order) GetRefundableOk() (*bool, bool)`

GetRefundableOk returns a tuple with the Refundable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefundable

`func (o *Order) SetRefundable(v bool)`

SetRefundable sets Refundable field to given value.


### GetRefunds

`func (o *Order) GetRefunds() []OrderRefund`

GetRefunds returns the Refunds field if non-nil, zero value otherwise.

### GetRefundsOk

`func (o *Order) GetRefundsOk() (*[]OrderRefund, bool)`

GetRefundsOk returns a tuple with the Refunds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefunds

`func (o *Order) SetRefunds(v []OrderRefund)`

SetRefunds sets Refunds field to given value.

### HasRefunds

`func (o *Order) HasRefunds() bool`

HasRefunds returns a boolean if a field has been set.

### GetBusinessId

`func (o *Order) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *Order) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *Order) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetBusinessName

`func (o *Order) GetBusinessName() string`

GetBusinessName returns the BusinessName field if non-nil, zero value otherwise.

### GetBusinessNameOk

`func (o *Order) GetBusinessNameOk() (*string, bool)`

GetBusinessNameOk returns a tuple with the BusinessName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessName

`func (o *Order) SetBusinessName(v string)`

SetBusinessName sets BusinessName field to given value.


### GetBillingReason

`func (o *Order) GetBillingReason() string`

GetBillingReason returns the BillingReason field if non-nil, zero value otherwise.

### GetBillingReasonOk

`func (o *Order) GetBillingReasonOk() (*string, bool)`

GetBillingReasonOk returns a tuple with the BillingReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingReason

`func (o *Order) SetBillingReason(v string)`

SetBillingReason sets BillingReason field to given value.

### HasBillingReason

`func (o *Order) HasBillingReason() bool`

HasBillingReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


