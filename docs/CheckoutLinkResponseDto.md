# CheckoutLinkResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The checkout link ID | 
**Title** | Pointer to **string** | The title of the checkout link | [optional] 
**ProductId** | Pointer to **string** | The linked Product ID | [optional] 
**CollectionId** | Pointer to **string** | The linked Collection ID | [optional] 
**CustomerName** | Pointer to **string** | Pre-filled customer name | [optional] 
**CustomerEmail** | Pointer to **string** | Pre-filled customer email | [optional] 
**AddressLine1** | Pointer to **string** | Pre-filled address line 1 | [optional] 
**City** | Pointer to **string** | Pre-filled city | [optional] 
**State** | Pointer to **string** | Pre-filled state | [optional] 
**PostalCode** | Pointer to **string** | Pre-filled postal code | [optional] 
**Country** | Pointer to **string** | Pre-filled country | [optional] 
**Quantity** | **float32** | Quantity to purchase | 
**RedirectUrl** | Pointer to **string** | URL to redirect to after successful payment | [optional] 
**CancelUrl** | Pointer to **string** | URL to redirect to if payment is cancelled | [optional] 
**ShowDiscounts** | **bool** | Whether to show discounts on the checkout page | 
**CreatedAt** | **time.Time** | Timestamp when the link was created | 
**UpdatedAt** | **time.Time** | Timestamp when the link was last updated | 

## Methods

### NewCheckoutLinkResponseDto

`func NewCheckoutLinkResponseDto(id string, quantity float32, showDiscounts bool, createdAt time.Time, updatedAt time.Time, ) *CheckoutLinkResponseDto`

NewCheckoutLinkResponseDto instantiates a new CheckoutLinkResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCheckoutLinkResponseDtoWithDefaults

`func NewCheckoutLinkResponseDtoWithDefaults() *CheckoutLinkResponseDto`

NewCheckoutLinkResponseDtoWithDefaults instantiates a new CheckoutLinkResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CheckoutLinkResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CheckoutLinkResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CheckoutLinkResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetTitle

`func (o *CheckoutLinkResponseDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CheckoutLinkResponseDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CheckoutLinkResponseDto) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CheckoutLinkResponseDto) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetProductId

`func (o *CheckoutLinkResponseDto) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CheckoutLinkResponseDto) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CheckoutLinkResponseDto) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *CheckoutLinkResponseDto) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### GetCollectionId

`func (o *CheckoutLinkResponseDto) GetCollectionId() string`

GetCollectionId returns the CollectionId field if non-nil, zero value otherwise.

### GetCollectionIdOk

`func (o *CheckoutLinkResponseDto) GetCollectionIdOk() (*string, bool)`

GetCollectionIdOk returns a tuple with the CollectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionId

`func (o *CheckoutLinkResponseDto) SetCollectionId(v string)`

SetCollectionId sets CollectionId field to given value.

### HasCollectionId

`func (o *CheckoutLinkResponseDto) HasCollectionId() bool`

HasCollectionId returns a boolean if a field has been set.

### GetCustomerName

`func (o *CheckoutLinkResponseDto) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *CheckoutLinkResponseDto) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *CheckoutLinkResponseDto) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *CheckoutLinkResponseDto) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### GetCustomerEmail

`func (o *CheckoutLinkResponseDto) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *CheckoutLinkResponseDto) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *CheckoutLinkResponseDto) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *CheckoutLinkResponseDto) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### GetAddressLine1

`func (o *CheckoutLinkResponseDto) GetAddressLine1() string`

GetAddressLine1 returns the AddressLine1 field if non-nil, zero value otherwise.

### GetAddressLine1Ok

`func (o *CheckoutLinkResponseDto) GetAddressLine1Ok() (*string, bool)`

GetAddressLine1Ok returns a tuple with the AddressLine1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine1

`func (o *CheckoutLinkResponseDto) SetAddressLine1(v string)`

SetAddressLine1 sets AddressLine1 field to given value.

### HasAddressLine1

`func (o *CheckoutLinkResponseDto) HasAddressLine1() bool`

HasAddressLine1 returns a boolean if a field has been set.

### GetCity

`func (o *CheckoutLinkResponseDto) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CheckoutLinkResponseDto) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CheckoutLinkResponseDto) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *CheckoutLinkResponseDto) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetState

`func (o *CheckoutLinkResponseDto) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *CheckoutLinkResponseDto) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *CheckoutLinkResponseDto) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *CheckoutLinkResponseDto) HasState() bool`

HasState returns a boolean if a field has been set.

### GetPostalCode

`func (o *CheckoutLinkResponseDto) GetPostalCode() string`

GetPostalCode returns the PostalCode field if non-nil, zero value otherwise.

### GetPostalCodeOk

`func (o *CheckoutLinkResponseDto) GetPostalCodeOk() (*string, bool)`

GetPostalCodeOk returns a tuple with the PostalCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostalCode

`func (o *CheckoutLinkResponseDto) SetPostalCode(v string)`

SetPostalCode sets PostalCode field to given value.

### HasPostalCode

`func (o *CheckoutLinkResponseDto) HasPostalCode() bool`

HasPostalCode returns a boolean if a field has been set.

### GetCountry

`func (o *CheckoutLinkResponseDto) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *CheckoutLinkResponseDto) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *CheckoutLinkResponseDto) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *CheckoutLinkResponseDto) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetQuantity

`func (o *CheckoutLinkResponseDto) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CheckoutLinkResponseDto) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CheckoutLinkResponseDto) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.


### GetRedirectUrl

`func (o *CheckoutLinkResponseDto) GetRedirectUrl() string`

GetRedirectUrl returns the RedirectUrl field if non-nil, zero value otherwise.

### GetRedirectUrlOk

`func (o *CheckoutLinkResponseDto) GetRedirectUrlOk() (*string, bool)`

GetRedirectUrlOk returns a tuple with the RedirectUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirectUrl

`func (o *CheckoutLinkResponseDto) SetRedirectUrl(v string)`

SetRedirectUrl sets RedirectUrl field to given value.

### HasRedirectUrl

`func (o *CheckoutLinkResponseDto) HasRedirectUrl() bool`

HasRedirectUrl returns a boolean if a field has been set.

### GetCancelUrl

`func (o *CheckoutLinkResponseDto) GetCancelUrl() string`

GetCancelUrl returns the CancelUrl field if non-nil, zero value otherwise.

### GetCancelUrlOk

`func (o *CheckoutLinkResponseDto) GetCancelUrlOk() (*string, bool)`

GetCancelUrlOk returns a tuple with the CancelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelUrl

`func (o *CheckoutLinkResponseDto) SetCancelUrl(v string)`

SetCancelUrl sets CancelUrl field to given value.

### HasCancelUrl

`func (o *CheckoutLinkResponseDto) HasCancelUrl() bool`

HasCancelUrl returns a boolean if a field has been set.

### GetShowDiscounts

`func (o *CheckoutLinkResponseDto) GetShowDiscounts() bool`

GetShowDiscounts returns the ShowDiscounts field if non-nil, zero value otherwise.

### GetShowDiscountsOk

`func (o *CheckoutLinkResponseDto) GetShowDiscountsOk() (*bool, bool)`

GetShowDiscountsOk returns a tuple with the ShowDiscounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowDiscounts

`func (o *CheckoutLinkResponseDto) SetShowDiscounts(v bool)`

SetShowDiscounts sets ShowDiscounts field to given value.


### GetCreatedAt

`func (o *CheckoutLinkResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CheckoutLinkResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CheckoutLinkResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *CheckoutLinkResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CheckoutLinkResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CheckoutLinkResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


