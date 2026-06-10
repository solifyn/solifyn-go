# UpdateCheckoutLinkDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | Pointer to **string** | The friendly display title of this checkout link | [optional] 
**ProductId** | Pointer to **string** | Product database/Whop ID to sell | [optional] 
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

### NewUpdateCheckoutLinkDto

`func NewUpdateCheckoutLinkDto() *UpdateCheckoutLinkDto`

NewUpdateCheckoutLinkDto instantiates a new UpdateCheckoutLinkDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateCheckoutLinkDtoWithDefaults

`func NewUpdateCheckoutLinkDtoWithDefaults() *UpdateCheckoutLinkDto`

NewUpdateCheckoutLinkDtoWithDefaults instantiates a new UpdateCheckoutLinkDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *UpdateCheckoutLinkDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *UpdateCheckoutLinkDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *UpdateCheckoutLinkDto) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *UpdateCheckoutLinkDto) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetProductId

`func (o *UpdateCheckoutLinkDto) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *UpdateCheckoutLinkDto) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *UpdateCheckoutLinkDto) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *UpdateCheckoutLinkDto) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### GetCollectionId

`func (o *UpdateCheckoutLinkDto) GetCollectionId() string`

GetCollectionId returns the CollectionId field if non-nil, zero value otherwise.

### GetCollectionIdOk

`func (o *UpdateCheckoutLinkDto) GetCollectionIdOk() (*string, bool)`

GetCollectionIdOk returns a tuple with the CollectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionId

`func (o *UpdateCheckoutLinkDto) SetCollectionId(v string)`

SetCollectionId sets CollectionId field to given value.

### HasCollectionId

`func (o *UpdateCheckoutLinkDto) HasCollectionId() bool`

HasCollectionId returns a boolean if a field has been set.

### GetCustomerName

`func (o *UpdateCheckoutLinkDto) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *UpdateCheckoutLinkDto) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *UpdateCheckoutLinkDto) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *UpdateCheckoutLinkDto) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### GetCustomerEmail

`func (o *UpdateCheckoutLinkDto) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *UpdateCheckoutLinkDto) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *UpdateCheckoutLinkDto) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *UpdateCheckoutLinkDto) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### GetAddressLine1

`func (o *UpdateCheckoutLinkDto) GetAddressLine1() string`

GetAddressLine1 returns the AddressLine1 field if non-nil, zero value otherwise.

### GetAddressLine1Ok

`func (o *UpdateCheckoutLinkDto) GetAddressLine1Ok() (*string, bool)`

GetAddressLine1Ok returns a tuple with the AddressLine1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine1

`func (o *UpdateCheckoutLinkDto) SetAddressLine1(v string)`

SetAddressLine1 sets AddressLine1 field to given value.

### HasAddressLine1

`func (o *UpdateCheckoutLinkDto) HasAddressLine1() bool`

HasAddressLine1 returns a boolean if a field has been set.

### GetCity

`func (o *UpdateCheckoutLinkDto) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *UpdateCheckoutLinkDto) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *UpdateCheckoutLinkDto) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *UpdateCheckoutLinkDto) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetState

`func (o *UpdateCheckoutLinkDto) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *UpdateCheckoutLinkDto) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *UpdateCheckoutLinkDto) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *UpdateCheckoutLinkDto) HasState() bool`

HasState returns a boolean if a field has been set.

### GetPostalCode

`func (o *UpdateCheckoutLinkDto) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *UpdateCheckoutLinkDto) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *UpdateCheckoutLinkDto) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.

### HasPostalCode

`func (o *UpdateCheckoutLinkDto) HasPostalCode() bool`

HasPostalCode returns a boolean if a field has been set.

### GetCountry

`func (o *UpdateCheckoutLinkDto) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *UpdateCheckoutLinkDto) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *UpdateCheckoutLinkDto) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *UpdateCheckoutLinkDto) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetQuantity

`func (o *UpdateCheckoutLinkDto) GetQuantity() map[string]interface{}`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *UpdateCheckoutLinkDto) GetQuantityOk() (*map[string]interface{}, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *UpdateCheckoutLinkDto) SetQuantity(v map[string]interface{})`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *UpdateCheckoutLinkDto) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetRedirectUrl

`func (o *UpdateCheckoutLinkDto) GetRedirectUrl() string`

GetRedirectUrl returns the RedirectUrl field if non-nil, zero value otherwise.

### GetRedirectUrlOk

`func (o *UpdateCheckoutLinkDto) GetRedirectUrlOk() (*string, bool)`

GetRedirectUrlOk returns a tuple with the RedirectUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirectUrl

`func (o *UpdateCheckoutLinkDto) SetRedirectUrl(v string)`

SetRedirectUrl sets RedirectUrl field to given value.

### HasRedirectUrl

`func (o *UpdateCheckoutLinkDto) HasRedirectUrl() bool`

HasRedirectUrl returns a boolean if a field has been set.

### GetCancelUrl

`func (o *UpdateCheckoutLinkDto) GetCancelUrl() string`

GetCancelUrl returns the CancelUrl field if non-nil, zero value otherwise.

### GetCancelUrlOk

`func (o *UpdateCheckoutLinkDto) GetCancelUrlOk() (*string, bool)`

GetCancelUrlOk returns a tuple with the CancelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelUrl

`func (o *UpdateCheckoutLinkDto) SetCancelUrl(v string)`

SetCancelUrl sets CancelUrl field to given value.

### HasCancelUrl

`func (o *UpdateCheckoutLinkDto) HasCancelUrl() bool`

HasCancelUrl returns a boolean if a field has been set.

### GetShowDiscounts

`func (o *UpdateCheckoutLinkDto) GetShowDiscounts() bool`

GetShowDiscounts returns the ShowDiscounts field if non-nil, zero value otherwise.

### GetShowDiscountsOk

`func (o *UpdateCheckoutLinkDto) GetShowDiscountsOk() (*bool, bool)`

GetShowDiscountsOk returns a tuple with the ShowDiscounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowDiscounts

`func (o *UpdateCheckoutLinkDto) SetShowDiscounts(v bool)`

SetShowDiscounts sets ShowDiscounts field to given value.

### HasShowDiscounts

`func (o *UpdateCheckoutLinkDto) HasShowDiscounts() bool`

HasShowDiscounts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


