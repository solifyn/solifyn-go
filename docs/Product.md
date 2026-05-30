# Product

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique identifier (ID) of the product. | 
**Name** | **string** | The display name of the product. | 
**Price** | **float32** | The price amount of the product (e.g. 29.00). | 
**Currency** | **string** | The three-letter ISO currency code (e.g. USD, VND, EUR). | 
**Description** | Pointer to **string** | A comprehensive rich text description of the product. | [optional] 
**Status** | **string** | The lifecycle status of the product (e.g. ACTIVE, ARCHIVED). | 
**ImageUrl** | **string** | URL of the product cover image. | 
**TaxCategory** | **string** | The tax classification for the product. | 
**PricingType** | **string** | Pricing model of the product. | 
**Discount** | **float32** | Discount value as a percentage or fixed amount. | 
**HasLicenseKey** | **bool** | Indicates if the product issues a cryptographically secure software license key upon checkout completion. | 
**HasDigitalDelivery** | **bool** | Whether the product includes digital file downloads upon purchase. | 
**IsTaxInclusive** | **bool** | Whether the product price already includes applicable sales taxes. | 
**BillingPeriod** | **int32** | The subscription billing cycle interval in days (for subscription products). | 
**TrialPeriodDays** | **int32** | Trial duration in days for subscription products. | 
**ExpirationDays** | **int32** | Automatic expiration period in days for the subscription entitlement. | 
**StatementDescriptor** | **string** | Custom text displayed on customer credit card statements for purchases of this product. | 
**PayWhatYouWant** | **bool** | Indicates if customers are allowed to enter a custom pricing amount at checkout. | 
**Metadata** | **map[string]string** | Custom developer metadata key-value pairs associated with the product. | 
**CustomFields** | **[]map[string]interface{}** | Custom form field questions to ask the customer during checkout. | 
**Stock** | **int32** | Available stock quantity, or null for unlimited inventory. | 
**ActivationLimit** | **int32** | Maximum number of simultaneous active instances/devices allowed per issued license key (applicable if hasLicenseKey is true). | 
**IsListed** | **bool** | Defines if the product is listed publicly on the merchant&#39;s storefront template. | 
**CreatedAt** | **time.Time** | Timestamp indicating exactly when the product was created. | 
**UpdatedAt** | **time.Time** | Timestamp indicating when the product was last modified. | 
**IsPermanentlyDeleted** | **bool** | Indicates if the product has been permanently deleted. | 
**BrandId** | **string** | Optional brand identifier. | 
**DigitalLink** | **string** | Secure link for digital delivery. | 
**Instructions** | **string** | Special instructions provided upon purchase. | 
**ActivationMessage** | **string** | Custom message displayed when a license key is activated. | 
**ExpiryHours** | **int32** | Number of hours until the license key expires. | 
**BusinessId** | **string** | The unique identifier of the business owning this product. | 

## Methods

### NewProduct

`func NewProduct(id string, name string, price float32, currency string, status string, imageUrl string, taxCategory string, pricingType string, discount float32, hasLicenseKey bool, hasDigitalDelivery bool, isTaxInclusive bool, billingPeriod int32, trialPeriodDays int32, expirationDays int32, statementDescriptor string, payWhatYouWant bool, metadata map[string]string, customFields []map[string]interface{}, stock int32, activationLimit int32, isListed bool, createdAt time.Time, updatedAt time.Time, isPermanentlyDeleted bool, brandId string, digitalLink string, instructions string, activationMessage string, expiryHours int32, businessId string, ) *Product`

NewProduct instantiates a new Product object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductWithDefaults

`func NewProductWithDefaults() *Product`

NewProductWithDefaults instantiates a new Product object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Product) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Product) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Product) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *Product) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Product) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Product) SetName(v string)`

SetName sets Name field to given value.


### GetPrice

`func (o *Product) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *Product) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *Product) SetPrice(v float32)`

SetPrice sets Price field to given value.


### GetCurrency

`func (o *Product) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Product) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Product) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDescription

`func (o *Product) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Product) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Product) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Product) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetStatus

`func (o *Product) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Product) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Product) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetImageUrl

`func (o *Product) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *Product) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *Product) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.


### GetTaxCategory

`func (o *Product) GetTaxCategory() string`

GetTaxCategory returns the TaxCategory field if non-nil, zero value otherwise.

### GetTaxCategoryOk

`func (o *Product) GetTaxCategoryOk() (*string, bool)`

GetTaxCategoryOk returns a tuple with the TaxCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCategory

`func (o *Product) SetTaxCategory(v string)`

SetTaxCategory sets TaxCategory field to given value.


### GetPricingType

`func (o *Product) GetPricingType() string`

GetPricingType returns the PricingType field if non-nil, zero value otherwise.

### GetPricingTypeOk

`func (o *Product) GetPricingTypeOk() (*string, bool)`

GetPricingTypeOk returns a tuple with the PricingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingType

`func (o *Product) SetPricingType(v string)`

SetPricingType sets PricingType field to given value.


### GetDiscount

`func (o *Product) GetDiscount() float32`

GetDiscount returns the Discount field if non-nil, zero value otherwise.

### GetDiscountOk

`func (o *Product) GetDiscountOk() (*float32, bool)`

GetDiscountOk returns a tuple with the Discount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscount

`func (o *Product) SetDiscount(v float32)`

SetDiscount sets Discount field to given value.


### GetHasLicenseKey

`func (o *Product) GetHasLicenseKey() bool`

GetHasLicenseKey returns the HasLicenseKey field if non-nil, zero value otherwise.

### GetHasLicenseKeyOk

`func (o *Product) GetHasLicenseKeyOk() (*bool, bool)`

GetHasLicenseKeyOk returns a tuple with the HasLicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasLicenseKey

`func (o *Product) SetHasLicenseKey(v bool)`

SetHasLicenseKey sets HasLicenseKey field to given value.


### GetHasDigitalDelivery

`func (o *Product) GetHasDigitalDelivery() bool`

GetHasDigitalDelivery returns the HasDigitalDelivery field if non-nil, zero value otherwise.

### GetHasDigitalDeliveryOk

`func (o *Product) GetHasDigitalDeliveryOk() (*bool, bool)`

GetHasDigitalDeliveryOk returns a tuple with the HasDigitalDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasDigitalDelivery

`func (o *Product) SetHasDigitalDelivery(v bool)`

SetHasDigitalDelivery sets HasDigitalDelivery field to given value.


### GetIsTaxInclusive

`func (o *Product) GetIsTaxInclusive() bool`

GetIsTaxInclusive returns the IsTaxInclusive field if non-nil, zero value otherwise.

### GetIsTaxInclusiveOk

`func (o *Product) GetIsTaxInclusiveOk() (*bool, bool)`

GetIsTaxInclusiveOk returns a tuple with the IsTaxInclusive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTaxInclusive

`func (o *Product) SetIsTaxInclusive(v bool)`

SetIsTaxInclusive sets IsTaxInclusive field to given value.


### GetBillingPeriod

`func (o *Product) GetBillingPeriod() int32`

GetBillingPeriod returns the BillingPeriod field if non-nil, zero value otherwise.

### GetBillingPeriodOk

`func (o *Product) GetBillingPeriodOk() (*int32, bool)`

GetBillingPeriodOk returns a tuple with the BillingPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingPeriod

`func (o *Product) SetBillingPeriod(v int32)`

SetBillingPeriod sets BillingPeriod field to given value.


### GetTrialPeriodDays

`func (o *Product) GetTrialPeriodDays() int32`

GetTrialPeriodDays returns the TrialPeriodDays field if non-nil, zero value otherwise.

### GetTrialPeriodDaysOk

`func (o *Product) GetTrialPeriodDaysOk() (*int32, bool)`

GetTrialPeriodDaysOk returns a tuple with the TrialPeriodDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialPeriodDays

`func (o *Product) SetTrialPeriodDays(v int32)`

SetTrialPeriodDays sets TrialPeriodDays field to given value.


### GetExpirationDays

`func (o *Product) GetExpirationDays() int32`

GetExpirationDays returns the ExpirationDays field if non-nil, zero value otherwise.

### GetExpirationDaysOk

`func (o *Product) GetExpirationDaysOk() (*int32, bool)`

GetExpirationDaysOk returns a tuple with the ExpirationDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDays

`func (o *Product) SetExpirationDays(v int32)`

SetExpirationDays sets ExpirationDays field to given value.


### GetStatementDescriptor

`func (o *Product) GetStatementDescriptor() string`

GetStatementDescriptor returns the StatementDescriptor field if non-nil, zero value otherwise.

### GetStatementDescriptorOk

`func (o *Product) GetStatementDescriptorOk() (*string, bool)`

GetStatementDescriptorOk returns a tuple with the StatementDescriptor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatementDescriptor

`func (o *Product) SetStatementDescriptor(v string)`

SetStatementDescriptor sets StatementDescriptor field to given value.


### GetPayWhatYouWant

`func (o *Product) GetPayWhatYouWant() bool`

GetPayWhatYouWant returns the PayWhatYouWant field if non-nil, zero value otherwise.

### GetPayWhatYouWantOk

`func (o *Product) GetPayWhatYouWantOk() (*bool, bool)`

GetPayWhatYouWantOk returns a tuple with the PayWhatYouWant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayWhatYouWant

`func (o *Product) SetPayWhatYouWant(v bool)`

SetPayWhatYouWant sets PayWhatYouWant field to given value.


### GetMetadata

`func (o *Product) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Product) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Product) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.


### GetCustomFields

`func (o *Product) GetCustomFields() []map[string]interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *Product) GetCustomFieldsOk() (*[]map[string]interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *Product) SetCustomFields(v []map[string]interface{})`

SetCustomFields sets CustomFields field to given value.


### GetStock

`func (o *Product) GetStock() int32`

GetStock returns the Stock field if non-nil, zero value otherwise.

### GetStockOk

`func (o *Product) GetStockOk() (*int32, bool)`

GetStockOk returns a tuple with the Stock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStock

`func (o *Product) SetStock(v int32)`

SetStock sets Stock field to given value.


### GetActivationLimit

`func (o *Product) GetActivationLimit() int32`

GetActivationLimit returns the ActivationLimit field if non-nil, zero value otherwise.

### GetActivationLimitOk

`func (o *Product) GetActivationLimitOk() (*int32, bool)`

GetActivationLimitOk returns a tuple with the ActivationLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationLimit

`func (o *Product) SetActivationLimit(v int32)`

SetActivationLimit sets ActivationLimit field to given value.


### GetIsListed

`func (o *Product) GetIsListed() bool`

GetIsListed returns the IsListed field if non-nil, zero value otherwise.

### GetIsListedOk

`func (o *Product) GetIsListedOk() (*bool, bool)`

GetIsListedOk returns a tuple with the IsListed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsListed

`func (o *Product) SetIsListed(v bool)`

SetIsListed sets IsListed field to given value.


### GetCreatedAt

`func (o *Product) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Product) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Product) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Product) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Product) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Product) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetIsPermanentlyDeleted

`func (o *Product) GetIsPermanentlyDeleted() bool`

GetIsPermanentlyDeleted returns the IsPermanentlyDeleted field if non-nil, zero value otherwise.

### GetIsPermanentlyDeletedOk

`func (o *Product) GetIsPermanentlyDeletedOk() (*bool, bool)`

GetIsPermanentlyDeletedOk returns a tuple with the IsPermanentlyDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPermanentlyDeleted

`func (o *Product) SetIsPermanentlyDeleted(v bool)`

SetIsPermanentlyDeleted sets IsPermanentlyDeleted field to given value.


### GetBrandId

`func (o *Product) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *Product) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *Product) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.


### GetDigitalLink

`func (o *Product) GetDigitalLink() string`

GetDigitalLink returns the DigitalLink field if non-nil, zero value otherwise.

### GetDigitalLinkOk

`func (o *Product) GetDigitalLinkOk() (*string, bool)`

GetDigitalLinkOk returns a tuple with the DigitalLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDigitalLink

`func (o *Product) SetDigitalLink(v string)`

SetDigitalLink sets DigitalLink field to given value.


### GetInstructions

`func (o *Product) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *Product) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *Product) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.


### GetActivationMessage

`func (o *Product) GetActivationMessage() string`

GetActivationMessage returns the ActivationMessage field if non-nil, zero value otherwise.

### GetActivationMessageOk

`func (o *Product) GetActivationMessageOk() (*string, bool)`

GetActivationMessageOk returns a tuple with the ActivationMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationMessage

`func (o *Product) SetActivationMessage(v string)`

SetActivationMessage sets ActivationMessage field to given value.


### GetExpiryHours

`func (o *Product) GetExpiryHours() int32`

GetExpiryHours returns the ExpiryHours field if non-nil, zero value otherwise.

### GetExpiryHoursOk

`func (o *Product) GetExpiryHoursOk() (*int32, bool)`

GetExpiryHoursOk returns a tuple with the ExpiryHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryHours

`func (o *Product) SetExpiryHours(v int32)`

SetExpiryHours sets ExpiryHours field to given value.


### GetBusinessId

`func (o *Product) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *Product) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *Product) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


