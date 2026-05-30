# CheckoutSessionDetailsDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Checkout session identifier | 
**Price** | **float32** | Total purchase amount | 
**Currency** | **string** | ISO currency code of the purchase | 
**StoreName** | **string** | Title or name of the merchant/store selling the item | 
**Status** | **string** | Current status of the checkout session | 
**BillingAddress** | Pointer to **map[string]interface{}** | Customer billing address details | [optional] 
**CustomFields** | Pointer to **map[string]interface{}** | Custom fields collected during purchase | [optional] 
**SessionId** | Pointer to **string** | The payment partner session ID | [optional] 
**PaymentId** | Pointer to **string** | Database payment transaction ID | [optional] 
**CheckoutUrl** | Pointer to **string** | Checkout session redirect URL if loaded in link mode | [optional] 
**Product** | Pointer to [**Product**](Product.md) | The details of the product being purchased | [optional] 

## Methods

### NewCheckoutSessionDetailsDto

`func NewCheckoutSessionDetailsDto(id string, price float32, currency string, storeName string, status string, ) *CheckoutSessionDetailsDto`

NewCheckoutSessionDetailsDto instantiates a new CheckoutSessionDetailsDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCheckoutSessionDetailsDtoWithDefaults

`func NewCheckoutSessionDetailsDtoWithDefaults() *CheckoutSessionDetailsDto`

NewCheckoutSessionDetailsDtoWithDefaults instantiates a new CheckoutSessionDetailsDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CheckoutSessionDetailsDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CheckoutSessionDetailsDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CheckoutSessionDetailsDto) SetId(v string)`

SetId sets Id field to given value.


### GetPrice

`func (o *CheckoutSessionDetailsDto) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *CheckoutSessionDetailsDto) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *CheckoutSessionDetailsDto) SetPrice(v float32)`

SetPrice sets Price field to given value.


### GetCurrency

`func (o *CheckoutSessionDetailsDto) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CheckoutSessionDetailsDto) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CheckoutSessionDetailsDto) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetStoreName

`func (o *CheckoutSessionDetailsDto) GetStoreName() string`

GetStoreName returns the StoreName field if non-nil, zero value otherwise.

### GetStoreNameOk

`func (o *CheckoutSessionDetailsDto) GetStoreNameOk() (*string, bool)`

GetStoreNameOk returns a tuple with the StoreName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreName

`func (o *CheckoutSessionDetailsDto) SetStoreName(v string)`

SetStoreName sets StoreName field to given value.


### GetStatus

`func (o *CheckoutSessionDetailsDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CheckoutSessionDetailsDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CheckoutSessionDetailsDto) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetBillingAddress

`func (o *CheckoutSessionDetailsDto) GetBillingAddress() map[string]interface{}`

GetBillingAddress returns the BillingAddress field if non-nil, zero value otherwise.

### GetBillingAddressOk

`func (o *CheckoutSessionDetailsDto) GetBillingAddressOk() (*map[string]interface{}, bool)`

GetBillingAddressOk returns a tuple with the BillingAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingAddress

`func (o *CheckoutSessionDetailsDto) SetBillingAddress(v map[string]interface{})`

SetBillingAddress sets BillingAddress field to given value.

### HasBillingAddress

`func (o *CheckoutSessionDetailsDto) HasBillingAddress() bool`

HasBillingAddress returns a boolean if a field has been set.

### GetCustomFields

`func (o *CheckoutSessionDetailsDto) GetCustomFields() map[string]interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *CheckoutSessionDetailsDto) GetCustomFieldsOk() (*map[string]interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *CheckoutSessionDetailsDto) SetCustomFields(v map[string]interface{})`

SetCustomFields sets CustomFields field to given value.

### HasCustomFields

`func (o *CheckoutSessionDetailsDto) HasCustomFields() bool`

HasCustomFields returns a boolean if a field has been set.

### GetSessionId

`func (o *CheckoutSessionDetailsDto) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *CheckoutSessionDetailsDto) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *CheckoutSessionDetailsDto) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.

### HasSessionId

`func (o *CheckoutSessionDetailsDto) HasSessionId() bool`

HasSessionId returns a boolean if a field has been set.

### GetPaymentId

`func (o *CheckoutSessionDetailsDto) GetPaymentId() string`

GetPaymentId returns the PaymentId field if non-nil, zero value otherwise.

### GetPaymentIdOk

`func (o *CheckoutSessionDetailsDto) GetPaymentIdOk() (*string, bool)`

GetPaymentIdOk returns a tuple with the PaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentId

`func (o *CheckoutSessionDetailsDto) SetPaymentId(v string)`

SetPaymentId sets PaymentId field to given value.

### HasPaymentId

`func (o *CheckoutSessionDetailsDto) HasPaymentId() bool`

HasPaymentId returns a boolean if a field has been set.

### GetCheckoutUrl

`func (o *CheckoutSessionDetailsDto) GetCheckoutUrl() string`

GetCheckoutUrl returns the CheckoutUrl field if non-nil, zero value otherwise.

### GetCheckoutUrlOk

`func (o *CheckoutSessionDetailsDto) GetCheckoutUrlOk() (*string, bool)`

GetCheckoutUrlOk returns a tuple with the CheckoutUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutUrl

`func (o *CheckoutSessionDetailsDto) SetCheckoutUrl(v string)`

SetCheckoutUrl sets CheckoutUrl field to given value.

### HasCheckoutUrl

`func (o *CheckoutSessionDetailsDto) HasCheckoutUrl() bool`

HasCheckoutUrl returns a boolean if a field has been set.

### GetProduct

`func (o *CheckoutSessionDetailsDto) GetProduct() Product`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *CheckoutSessionDetailsDto) GetProductOk() (*Product, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *CheckoutSessionDetailsDto) SetProduct(v Product)`

SetProduct sets Product field to given value.

### HasProduct

`func (o *CheckoutSessionDetailsDto) HasProduct() bool`

HasProduct returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


