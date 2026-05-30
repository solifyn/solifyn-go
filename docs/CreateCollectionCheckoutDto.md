# CreateCollectionCheckoutDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CollectionId** | **string** | The database ID of the collection to checkout | 
**Quantity** | Pointer to **float32** | Quantity of collections to buy | [optional] [default to 1]
**DiscountCode** | Pointer to **string** | Discount code to apply | [optional] 
**Aff** | Pointer to **string** | Affiliate tracking code | [optional] 
**CustomFields** | Pointer to **map[string]interface{}** | Custom text fields / selected addons | [optional] 

## Methods

### NewCreateCollectionCheckoutDto

`func NewCreateCollectionCheckoutDto(collectionId string, ) *CreateCollectionCheckoutDto`

NewCreateCollectionCheckoutDto instantiates a new CreateCollectionCheckoutDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCollectionCheckoutDtoWithDefaults

`func NewCreateCollectionCheckoutDtoWithDefaults() *CreateCollectionCheckoutDto`

NewCreateCollectionCheckoutDtoWithDefaults instantiates a new CreateCollectionCheckoutDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCollectionId

`func (o *CreateCollectionCheckoutDto) GetCollectionId() string`

GetCollectionId returns the CollectionId field if non-nil, zero value otherwise.

### GetCollectionIdOk

`func (o *CreateCollectionCheckoutDto) GetCollectionIdOk() (*string, bool)`

GetCollectionIdOk returns a tuple with the CollectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionId

`func (o *CreateCollectionCheckoutDto) SetCollectionId(v string)`

SetCollectionId sets CollectionId field to given value.


### GetQuantity

`func (o *CreateCollectionCheckoutDto) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateCollectionCheckoutDto) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateCollectionCheckoutDto) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *CreateCollectionCheckoutDto) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetDiscountCode

`func (o *CreateCollectionCheckoutDto) GetDiscountCode() string`

GetDiscountCode returns the DiscountCode field if non-nil, zero value otherwise.

### GetDiscountCodeOk

`func (o *CreateCollectionCheckoutDto) GetDiscountCodeOk() (*string, bool)`

GetDiscountCodeOk returns a tuple with the DiscountCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountCode

`func (o *CreateCollectionCheckoutDto) SetDiscountCode(v string)`

SetDiscountCode sets DiscountCode field to given value.

### HasDiscountCode

`func (o *CreateCollectionCheckoutDto) HasDiscountCode() bool`

HasDiscountCode returns a boolean if a field has been set.

### GetAff

`func (o *CreateCollectionCheckoutDto) GetAff() string`

GetAff returns the Aff field if non-nil, zero value otherwise.

### GetAffOk

`func (o *CreateCollectionCheckoutDto) GetAffOk() (*string, bool)`

GetAffOk returns a tuple with the Aff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAff

`func (o *CreateCollectionCheckoutDto) SetAff(v string)`

SetAff sets Aff field to given value.

### HasAff

`func (o *CreateCollectionCheckoutDto) HasAff() bool`

HasAff returns a boolean if a field has been set.

### GetCustomFields

`func (o *CreateCollectionCheckoutDto) GetCustomFields() map[string]interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *CreateCollectionCheckoutDto) GetCustomFieldsOk() (*map[string]interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *CreateCollectionCheckoutDto) SetCustomFields(v map[string]interface{})`

SetCustomFields sets CustomFields field to given value.

### HasCustomFields

`func (o *CreateCollectionCheckoutDto) HasCustomFields() bool`

HasCustomFields returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


