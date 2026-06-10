# CreateCheckoutDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductId** | **string** | The public product identifier (product ID) | 
**Currency** | Pointer to **string** | Three-letter ISO currency code (lowercase) | [optional] 
**Quantity** | Pointer to **float32** | The quantity of items to buy | [optional] [default to 1]
**DiscountCode** | Pointer to **string** | Discount code to apply | [optional] 
**CustomPrice** | Pointer to **float32** | Custom price paid by customer (for Pay What You Want products) | [optional] 
**CustomerEmail** | Pointer to **string** | Email address of the customer | [optional] 
**CheckoutData** | Pointer to **map[string]interface{}** | JSON metadata or checkout custom information | [optional] 
**CustomFields** | Pointer to **map[string]interface{}** | Custom text fields required for the purchase | [optional] 
**Aff** | Pointer to **string** | Affiliate partner tracking code | [optional] 
**CheckoutId** | Pointer to **string** | The existing checkout database ID to validate / update | [optional] 

## Methods

### NewCreateCheckoutDto

`func NewCreateCheckoutDto(productId string, ) *CreateCheckoutDto`

NewCreateCheckoutDto instantiates a new CreateCheckoutDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCheckoutDtoWithDefaults

`func NewCreateCheckoutDtoWithDefaults() *CreateCheckoutDto`

NewCreateCheckoutDtoWithDefaults instantiates a new CreateCheckoutDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductId

`func (o *CreateCheckoutDto) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CreateCheckoutDto) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CreateCheckoutDto) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetCurrency

`func (o *CreateCheckoutDto) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateCheckoutDto) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateCheckoutDto) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CreateCheckoutDto) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetQuantity

`func (o *CreateCheckoutDto) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateCheckoutDto) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateCheckoutDto) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *CreateCheckoutDto) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetDiscountCode

`func (o *CreateCheckoutDto) GetDiscountCode() string`

GetDiscountCode returns the DiscountCode field if non-nil, zero value otherwise.

### GetDiscountCodeOk

`func (o *CreateCheckoutDto) GetDiscountCodeOk() (*string, bool)`

GetDiscountCodeOk returns a tuple with the DiscountCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountCode

`func (o *CreateCheckoutDto) SetDiscountCode(v string)`

SetDiscountCode sets DiscountCode field to given value.

### HasDiscountCode

`func (o *CreateCheckoutDto) HasDiscountCode() bool`

HasDiscountCode returns a boolean if a field has been set.

### GetCustomPrice

`func (o *CreateCheckoutDto) GetCustomPrice() float32`

GetCustomPrice returns the CustomPrice field if non-nil, zero value otherwise.

### GetCustomPriceOk

`func (o *CreateCheckoutDto) GetCustomPriceOk() (*float32, bool)`

GetCustomPriceOk returns a tuple with the CustomPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomPrice

`func (o *CreateCheckoutDto) SetCustomPrice(v float32)`

SetCustomPrice sets CustomPrice field to given value.

### HasCustomPrice

`func (o *CreateCheckoutDto) HasCustomPrice() bool`

HasCustomPrice returns a boolean if a field has been set.

### GetCustomerEmail

`func (o *CreateCheckoutDto) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *CreateCheckoutDto) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *CreateCheckoutDto) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *CreateCheckoutDto) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### GetCheckoutData

`func (o *CreateCheckoutDto) GetCheckoutData() map[string]interface{}`

GetCheckoutData returns the CheckoutData field if non-nil, zero value otherwise.

### GetCheckoutDataOk

`func (o *CreateCheckoutDto) GetCheckoutDataOk() (*map[string]interface{}, bool)`

GetCheckoutDataOk returns a tuple with the CheckoutData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutData

`func (o *CreateCheckoutDto) SetCheckoutData(v map[string]interface{})`

SetCheckoutData sets CheckoutData field to given value.

### HasCheckoutData

`func (o *CreateCheckoutDto) HasCheckoutData() bool`

HasCheckoutData returns a boolean if a field has been set.

### GetCustomFields

`func (o *CreateCheckoutDto) GetCustomFields() map[string]interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *CreateCheckoutDto) GetCustomFieldsOk() (*map[string]interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *CreateCheckoutDto) SetCustomFields(v map[string]interface{})`

SetCustomFields sets CustomFields field to given value.

### HasCustomFields

`func (o *CreateCheckoutDto) HasCustomFields() bool`

HasCustomFields returns a boolean if a field has been set.

### GetAff

`func (o *CreateCheckoutDto) GetAff() string`

GetAff returns the Aff field if non-nil, zero value otherwise.

### GetAffOk

`func (o *CreateCheckoutDto) GetAffOk() (*string, bool)`

GetAffOk returns a tuple with the Aff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAff

`func (o *CreateCheckoutDto) SetAff(v string)`

SetAff sets Aff field to given value.

### HasAff

`func (o *CreateCheckoutDto) HasAff() bool`

HasAff returns a boolean if a field has been set.

### GetCheckoutId

`func (o *CreateCheckoutDto) GetCheckoutId() string`

GetCheckoutId returns the CheckoutId field if non-nil, zero value otherwise.

### GetCheckoutIdOk

`func (o *CreateCheckoutDto) GetCheckoutIdOk() (*string, bool)`

GetCheckoutIdOk returns a tuple with the CheckoutId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutId

`func (o *CreateCheckoutDto) SetCheckoutId(v string)`

SetCheckoutId sets CheckoutId field to given value.

### HasCheckoutId

`func (o *CreateCheckoutDto) HasCheckoutId() bool`

HasCheckoutId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


