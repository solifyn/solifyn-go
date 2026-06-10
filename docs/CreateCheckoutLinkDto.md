# CreateCheckoutLinkDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | Pointer to **string** | The friendly display title of this checkout link | [optional] 
**ProductId** | **string** | Product database/Whop ID to sell | 
**CollectionId** | Pointer to **string** | Optional collection database ID to sell | [optional] 
**CustomerName** | Pointer to **string** | Prefilled customer name for checkout inputs | [optional] 
**CustomerEmail** | Pointer to **string** | Prefilled customer email for checkout inputs | [optional] 
**AddressLine1** | Pointer to **string** | Prefilled customer billing address line 1 | [optional] 
**City** | Pointer to **string** | Prefilled customer billing city | [optional] 
**State** | Pointer to **string** | Prefilled customer billing state | [optional] 
**PostalCode** | Pointer to **string** | Prefilled customer billing zip/postal code | [optional] 
**Country** | Pointer to **string** | Prefilled customer billing country (2-letter ISO) | [optional] 
**Quantity** | Pointer to **map[string]interface{}** | Override quantity for checkout session | [optional] 
**RedirectUrl** | Pointer to **string** | The absolute URL to redirect to upon successful payment completion | [optional] 
**CancelUrl** | Pointer to **string** | The absolute URL to redirect to if a customer cancels the payment | [optional] 
**ShowDiscounts** | Pointer to **bool** | Whether to display discount input form fields on checkout screen | [optional] [default to true]

## Methods

### NewCreateCheckoutLinkDto

`func NewCreateCheckoutLinkDto(productId string, ) *CreateCheckoutLinkDto`

NewCreateCheckoutLinkDto instantiates a new CreateCheckoutLinkDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCheckoutLinkDtoWithDefaults

`func NewCreateCheckoutLinkDtoWithDefaults() *CreateCheckoutLinkDto`

NewCreateCheckoutLinkDtoWithDefaults instantiates a new CreateCheckoutLinkDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *CreateCheckoutLinkDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateCheckoutLinkDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateCheckoutLinkDto) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CreateCheckoutLinkDto) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetProductId

`func (o *CreateCheckoutLinkDto) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CreateCheckoutLinkDto) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CreateCheckoutLinkDto) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetCollectionId

`func (o *CreateCheckoutLinkDto) GetCollectionId() string`

GetCollectionId returns the CollectionId field if non-nil, zero value otherwise.

### GetCollectionIdOk

`func (o *CreateCheckoutLinkDto) GetCollectionIdOk() (*string, bool)`

GetCollectionIdOk returns a tuple with the CollectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionId

`func (o *CreateCheckoutLinkDto) SetCollectionId(v string)`

SetCollectionId sets CollectionId field to given value.

### HasCollectionId

`func (o *CreateCheckoutLinkDto) HasCollectionId() bool`

HasCollectionId returns a boolean if a field has been set.

### GetCustomerName

`func (o *CreateCheckoutLinkDto) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *CreateCheckoutLinkDto) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *CreateCheckoutLinkDto) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *CreateCheckoutLinkDto) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### GetCustomerEmail

`func (o *CreateCheckoutLinkDto) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *CreateCheckoutLinkDto) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *CreateCheckoutLinkDto) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *CreateCheckoutLinkDto) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### GetAddressLine1

`func (o *CreateCheckoutLinkDto) GetAddressLine1() string`

GetAddressLine1 returns the AddressLine1 field if non-nil, zero value otherwise.

### GetAddressLine1Ok

`func (o *CreateCheckoutLinkDto) GetAddressLine1Ok() (*string, bool)`

GetAddressLine1Ok returns a tuple with the AddressLine1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine1

`func (o *CreateCheckoutLinkDto) SetAddressLine1(v string)`

SetAddressLine1 sets AddressLine1 field to given value.

### HasAddressLine1

`func (o *CreateCheckoutLinkDto) HasAddressLine1() bool`

HasAddressLine1 returns a boolean if a field has been set.

### GetCity

`func (o *CreateCheckoutLinkDto) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CreateCheckoutLinkDto) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CreateCheckoutLinkDto) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *CreateCheckoutLinkDto) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetState

`func (o *CreateCheckoutLinkDto) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *CreateCheckoutLinkDto) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *CreateCheckoutLinkDto) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *CreateCheckoutLinkDto) HasState() bool`

HasState returns a boolean if a field has been set.

### GetPostalCode

`func (o *CreateCheckoutLinkDto) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *CreateCheckoutLinkDto) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *CreateCheckoutLinkDto) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.

### HasPostalCode

`func (o *CreateCheckoutLinkDto) HasPostalCode() bool`

HasPostalCode returns a boolean if a field has been set.

### GetCountry

`func (o *CreateCheckoutLinkDto) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *CreateCheckoutLinkDto) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *CreateCheckoutLinkDto) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *CreateCheckoutLinkDto) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetQuantity

`func (o *CreateCheckoutLinkDto) GetQuantity() map[string]interface{}`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateCheckoutLinkDto) GetQuantityOk() (*map[string]interface{}, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateCheckoutLinkDto) SetQuantity(v map[string]interface{})`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *CreateCheckoutLinkDto) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetRedirectUrl

`func (o *CreateCheckoutLinkDto) GetRedirectUrl() string`

GetRedirectUrl returns the RedirectUrl field if non-nil, zero value otherwise.

### GetRedirectUrlOk

`func (o *CreateCheckoutLinkDto) GetRedirectUrlOk() (*string, bool)`

GetRedirectUrlOk returns a tuple with the RedirectUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirectUrl

`func (o *CreateCheckoutLinkDto) SetRedirectUrl(v string)`

SetRedirectUrl sets RedirectUrl field to given value.

### HasRedirectUrl

`func (o *CreateCheckoutLinkDto) HasRedirectUrl() bool`

HasRedirectUrl returns a boolean if a field has been set.

### GetCancelUrl

`func (o *CreateCheckoutLinkDto) GetCancelUrl() string`

GetCancelUrl returns the CancelUrl field if non-nil, zero value otherwise.

### GetCancelUrlOk

`func (o *CreateCheckoutLinkDto) GetCancelUrlOk() (*string, bool)`

GetCancelUrlOk returns a tuple with the CancelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelUrl

`func (o *CreateCheckoutLinkDto) SetCancelUrl(v string)`

SetCancelUrl sets CancelUrl field to given value.

### HasCancelUrl

`func (o *CreateCheckoutLinkDto) HasCancelUrl() bool`

HasCancelUrl returns a boolean if a field has been set.

### GetShowDiscounts

`func (o *CreateCheckoutLinkDto) GetShowDiscounts() bool`

GetShowDiscounts returns the ShowDiscounts field if non-nil, zero value otherwise.

### GetShowDiscountsOk

`func (o *CreateCheckoutLinkDto) GetShowDiscountsOk() (*bool, bool)`

GetShowDiscountsOk returns a tuple with the ShowDiscounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowDiscounts

`func (o *CreateCheckoutLinkDto) SetShowDiscounts(v bool)`

SetShowDiscounts sets ShowDiscounts field to given value.

### HasShowDiscounts

`func (o *CreateCheckoutLinkDto) HasShowDiscounts() bool`

HasShowDiscounts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


