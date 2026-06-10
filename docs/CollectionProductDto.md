# CollectionProductDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique identifier (ID) of the product. | 
**Name** | **string** | The display name of the product. | 
**Price** | **float32** | The price amount of the product (e.g. 29.00). | 
**Currency** | **string** | The three-letter ISO currency code (e.g. USD, VND, EUR). | 
**Description** | Pointer to **NullableString** | A comprehensive rich text description of the product. | [optional] 
**Status** | **string** | The lifecycle status of the product (e.g. ACTIVE, ARCHIVED). | 
**ImageUrl** | **NullableString** | URL of the product cover image. | 
**TaxCategory** | **string** | The tax classification for the product. | 
**PricingType** | **string** | Pricing model of the product. | 
**Discount** | **NullableFloat32** | Discount value as a percentage or fixed amount. | 
**HasLicenseKey** | **bool** | Indicates if the product issues a cryptographically secure software license key upon checkout completion. | 
**HasDigitalDelivery** | **bool** | Whether the product includes digital file downloads upon purchase. | 
**HasGithubAccess** | **bool** | Whether the product includes GitHub repository access. | 
**GithubRepo** | **NullableString** | GitHub repository to grant access to (format: owner/repo). | 
**GithubPermission** | **NullableString** | GitHub collaborator permission level. | 
**IsTaxInclusive** | **bool** | Whether the product price already includes applicable sales taxes. | 
**BillingPeriod** | **NullableInt32** | The subscription billing cycle interval in days (for subscription products). | 
**TrialPeriodDays** | **NullableInt32** | Trial duration in days for subscription products. | 
**ExpirationDays** | **NullableInt32** | Automatic expiration period in days for the subscription entitlement. | 
**StatementDescriptor** | **NullableString** | Custom text displayed on customer credit card statements for purchases of this product. | 
**PayWhatYouWant** | **bool** | Indicates if customers are allowed to enter a custom pricing amount at checkout. | 
**Metadata** | **map[string]string** | Custom developer metadata key-value pairs associated with the product. | 
**CustomFields** | **[]map[string]interface{}** | Custom form field questions to ask the customer during checkout. | 
**Stock** | **NullableInt32** | Available stock quantity, or null for unlimited inventory. | 
**ActivationLimit** | **int32** | Maximum number of simultaneous active instances/devices allowed per issued license key (applicable if hasLicenseKey is true). | 
**IsListed** | **bool** | Defines if the product is listed publicly on the merchant&#39;s storefront template. | 
**IsFree** | **bool** | Whether the product is free. | 
**CreatedAt** | **time.Time** | Timestamp indicating exactly when the product was created. | 
**UpdatedAt** | **time.Time** | Timestamp indicating when the product was last modified. | 
**IsPermanentlyDeleted** | **bool** | Indicates if the product has been permanently deleted. | 
**BrandId** | **NullableString** | Optional brand identifier. | 
**DigitalLink** | **NullableString** | Secure link for digital delivery. | 
**Instructions** | **NullableString** | Special instructions provided upon purchase. | 
**ActivationMessage** | **NullableString** | Custom message displayed when a license key is activated. | 
**ExpiryHours** | **NullableInt32** | Number of hours until the license key expires. | 
**BusinessId** | **string** | The unique identifier of the business owning this product. | 
**Quantity** | **float32** | Quantity of the product in the collection | 

## Methods

### NewCollectionProductDto

`func NewCollectionProductDto(id string, name string, price float32, currency string, status string, imageUrl NullableString, taxCategory string, pricingType string, discount NullableFloat32, hasLicenseKey bool, hasDigitalDelivery bool, hasGithubAccess bool, githubRepo NullableString, githubPermission NullableString, isTaxInclusive bool, billingPeriod NullableInt32, trialPeriodDays NullableInt32, expirationDays NullableInt32, statementDescriptor NullableString, payWhatYouWant bool, metadata map[string]string, customFields []map[string]interface{}, stock NullableInt32, activationLimit int32, isListed bool, isFree bool, createdAt time.Time, updatedAt time.Time, isPermanentlyDeleted bool, brandId NullableString, digitalLink NullableString, instructions NullableString, activationMessage NullableString, expiryHours NullableInt32, businessId string, quantity float32, ) *CollectionProductDto`

NewCollectionProductDto instantiates a new CollectionProductDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCollectionProductDtoWithDefaults

`func NewCollectionProductDtoWithDefaults() *CollectionProductDto`

NewCollectionProductDtoWithDefaults instantiates a new CollectionProductDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CollectionProductDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CollectionProductDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CollectionProductDto) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *CollectionProductDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CollectionProductDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CollectionProductDto) SetName(v string)`

SetName sets Name field to given value.


### GetPrice

`func (o *CollectionProductDto) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *CollectionProductDto) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *CollectionProductDto) SetPrice(v float32)`

SetPrice sets Price field to given value.


### GetCurrency

`func (o *CollectionProductDto) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CollectionProductDto) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CollectionProductDto) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDescription

`func (o *CollectionProductDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CollectionProductDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CollectionProductDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CollectionProductDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CollectionProductDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CollectionProductDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetStatus

`func (o *CollectionProductDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CollectionProductDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CollectionProductDto) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetImageUrl

`func (o *CollectionProductDto) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *CollectionProductDto) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *CollectionProductDto) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.


### SetImageUrlNil

`func (o *CollectionProductDto) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *CollectionProductDto) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetTaxCategory

`func (o *CollectionProductDto) GetTaxCategory() string`

GetTaxCategory returns the TaxCategory field if non-nil, zero value otherwise.

### GetTaxCategoryOk

`func (o *CollectionProductDto) GetTaxCategoryOk() (*string, bool)`

GetTaxCategoryOk returns a tuple with the TaxCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCategory

`func (o *CollectionProductDto) SetTaxCategory(v string)`

SetTaxCategory sets TaxCategory field to given value.


### GetPricingType

`func (o *CollectionProductDto) GetPricingType() string`

GetPricingType returns the PricingType field if non-nil, zero value otherwise.

### GetPricingTypeOk

`func (o *CollectionProductDto) GetPricingTypeOk() (*string, bool)`

GetPricingTypeOk returns a tuple with the PricingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingType

`func (o *CollectionProductDto) SetPricingType(v string)`

SetPricingType sets PricingType field to given value.


### GetDiscount

`func (o *CollectionProductDto) GetDiscount() float32`

GetDiscount returns the Discount field if non-nil, zero value otherwise.

### GetDiscountOk

`func (o *CollectionProductDto) GetDiscountOk() (*float32, bool)`

GetDiscountOk returns a tuple with the Discount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscount

`func (o *CollectionProductDto) SetDiscount(v float32)`

SetDiscount sets Discount field to given value.


### SetDiscountNil

`func (o *CollectionProductDto) SetDiscountNil(b bool)`

 SetDiscountNil sets the value for Discount to be an explicit nil

### UnsetDiscount
`func (o *CollectionProductDto) UnsetDiscount()`

UnsetDiscount ensures that no value is present for Discount, not even an explicit nil
### GetHasLicenseKey

`func (o *CollectionProductDto) GetHasLicenseKey() bool`

GetHasLicenseKey returns the HasLicenseKey field if non-nil, zero value otherwise.

### GetHasLicenseKeyOk

`func (o *CollectionProductDto) GetHasLicenseKeyOk() (*bool, bool)`

GetHasLicenseKeyOk returns a tuple with the HasLicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasLicenseKey

`func (o *CollectionProductDto) SetHasLicenseKey(v bool)`

SetHasLicenseKey sets HasLicenseKey field to given value.


### GetHasDigitalDelivery

`func (o *CollectionProductDto) GetHasDigitalDelivery() bool`

GetHasDigitalDelivery returns the HasDigitalDelivery field if non-nil, zero value otherwise.

### GetHasDigitalDeliveryOk

`func (o *CollectionProductDto) GetHasDigitalDeliveryOk() (*bool, bool)`

GetHasDigitalDeliveryOk returns a tuple with the HasDigitalDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasDigitalDelivery

`func (o *CollectionProductDto) SetHasDigitalDelivery(v bool)`

SetHasDigitalDelivery sets HasDigitalDelivery field to given value.


### GetHasGithubAccess

`func (o *CollectionProductDto) GetHasGithubAccess() bool`

GetHasGithubAccess returns the HasGithubAccess field if non-nil, zero value otherwise.

### GetHasGithubAccessOk

`func (o *CollectionProductDto) GetHasGithubAccessOk() (*bool, bool)`

GetHasGithubAccessOk returns a tuple with the HasGithubAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasGithubAccess

`func (o *CollectionProductDto) SetHasGithubAccess(v bool)`

SetHasGithubAccess sets HasGithubAccess field to given value.


### GetGithubRepo

`func (o *CollectionProductDto) GetGithubRepo() string`

GetGithubRepo returns the GithubRepo field if non-nil, zero value otherwise.

### GetGithubRepoOk

`func (o *CollectionProductDto) GetGithubRepoOk() (*string, bool)`

GetGithubRepoOk returns a tuple with the GithubRepo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubRepo

`func (o *CollectionProductDto) SetGithubRepo(v string)`

SetGithubRepo sets GithubRepo field to given value.


### SetGithubRepoNil

`func (o *CollectionProductDto) SetGithubRepoNil(b bool)`

 SetGithubRepoNil sets the value for GithubRepo to be an explicit nil

### UnsetGithubRepo
`func (o *CollectionProductDto) UnsetGithubRepo()`

UnsetGithubRepo ensures that no value is present for GithubRepo, not even an explicit nil
### GetGithubPermission

`func (o *CollectionProductDto) GetGithubPermission() string`

GetGithubPermission returns the GithubPermission field if non-nil, zero value otherwise.

### GetGithubPermissionOk

`func (o *CollectionProductDto) GetGithubPermissionOk() (*string, bool)`

GetGithubPermissionOk returns a tuple with the GithubPermission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubPermission

`func (o *CollectionProductDto) SetGithubPermission(v string)`

SetGithubPermission sets GithubPermission field to given value.


### SetGithubPermissionNil

`func (o *CollectionProductDto) SetGithubPermissionNil(b bool)`

 SetGithubPermissionNil sets the value for GithubPermission to be an explicit nil

### UnsetGithubPermission
`func (o *CollectionProductDto) UnsetGithubPermission()`

UnsetGithubPermission ensures that no value is present for GithubPermission, not even an explicit nil
### GetIsTaxInclusive

`func (o *CollectionProductDto) GetIsTaxInclusive() bool`

GetIsTaxInclusive returns the IsTaxInclusive field if non-nil, zero value otherwise.

### GetIsTaxInclusiveOk

`func (o *CollectionProductDto) GetIsTaxInclusiveOk() (*bool, bool)`

GetIsTaxInclusiveOk returns a tuple with the IsTaxInclusive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTaxInclusive

`func (o *CollectionProductDto) SetIsTaxInclusive(v bool)`

SetIsTaxInclusive sets IsTaxInclusive field to given value.


### GetBillingPeriod

`func (o *CollectionProductDto) GetBillingPeriod() int32`

GetBillingPeriod returns the BillingPeriod field if non-nil, zero value otherwise.

### GetBillingPeriodOk

`func (o *CollectionProductDto) GetBillingPeriodOk() (*int32, bool)`

GetBillingPeriodOk returns a tuple with the BillingPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingPeriod

`func (o *CollectionProductDto) SetBillingPeriod(v int32)`

SetBillingPeriod sets BillingPeriod field to given value.


### SetBillingPeriodNil

`func (o *CollectionProductDto) SetBillingPeriodNil(b bool)`

 SetBillingPeriodNil sets the value for BillingPeriod to be an explicit nil

### UnsetBillingPeriod
`func (o *CollectionProductDto) UnsetBillingPeriod()`

UnsetBillingPeriod ensures that no value is present for BillingPeriod, not even an explicit nil
### GetTrialPeriodDays

`func (o *CollectionProductDto) GetTrialPeriodDays() int32`

GetTrialPeriodDays returns the TrialPeriodDays field if non-nil, zero value otherwise.

### GetTrialPeriodDaysOk

`func (o *CollectionProductDto) GetTrialPeriodDaysOk() (*int32, bool)`

GetTrialPeriodDaysOk returns a tuple with the TrialPeriodDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialPeriodDays

`func (o *CollectionProductDto) SetTrialPeriodDays(v int32)`

SetTrialPeriodDays sets TrialPeriodDays field to given value.


### SetTrialPeriodDaysNil

`func (o *CollectionProductDto) SetTrialPeriodDaysNil(b bool)`

 SetTrialPeriodDaysNil sets the value for TrialPeriodDays to be an explicit nil

### UnsetTrialPeriodDays
`func (o *CollectionProductDto) UnsetTrialPeriodDays()`

UnsetTrialPeriodDays ensures that no value is present for TrialPeriodDays, not even an explicit nil
### GetExpirationDays

`func (o *CollectionProductDto) GetExpirationDays() int32`

GetExpirationDays returns the ExpirationDays field if non-nil, zero value otherwise.

### GetExpirationDaysOk

`func (o *CollectionProductDto) GetExpirationDaysOk() (*int32, bool)`

GetExpirationDaysOk returns a tuple with the ExpirationDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDays

`func (o *CollectionProductDto) SetExpirationDays(v int32)`

SetExpirationDays sets ExpirationDays field to given value.


### SetExpirationDaysNil

`func (o *CollectionProductDto) SetExpirationDaysNil(b bool)`

 SetExpirationDaysNil sets the value for ExpirationDays to be an explicit nil

### UnsetExpirationDays
`func (o *CollectionProductDto) UnsetExpirationDays()`

UnsetExpirationDays ensures that no value is present for ExpirationDays, not even an explicit nil
### GetStatementDescriptor

`func (o *CollectionProductDto) GetStatementDescriptor() string`

GetStatementDescriptor returns the StatementDescriptor field if non-nil, zero value otherwise.

### GetStatementDescriptorOk

`func (o *CollectionProductDto) GetStatementDescriptorOk() (*string, bool)`

GetStatementDescriptorOk returns a tuple with the StatementDescriptor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatementDescriptor

`func (o *CollectionProductDto) SetStatementDescriptor(v string)`

SetStatementDescriptor sets StatementDescriptor field to given value.


### SetStatementDescriptorNil

`func (o *CollectionProductDto) SetStatementDescriptorNil(b bool)`

 SetStatementDescriptorNil sets the value for StatementDescriptor to be an explicit nil

### UnsetStatementDescriptor
`func (o *CollectionProductDto) UnsetStatementDescriptor()`

UnsetStatementDescriptor ensures that no value is present for StatementDescriptor, not even an explicit nil
### GetPayWhatYouWant

`func (o *CollectionProductDto) GetPayWhatYouWant() bool`

GetPayWhatYouWant returns the PayWhatYouWant field if non-nil, zero value otherwise.

### GetPayWhatYouWantOk

`func (o *CollectionProductDto) GetPayWhatYouWantOk() (*bool, bool)`

GetPayWhatYouWantOk returns a tuple with the PayWhatYouWant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayWhatYouWant

`func (o *CollectionProductDto) SetPayWhatYouWant(v bool)`

SetPayWhatYouWant sets PayWhatYouWant field to given value.


### GetMetadata

`func (o *CollectionProductDto) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CollectionProductDto) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CollectionProductDto) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *CollectionProductDto) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *CollectionProductDto) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCustomFields

`func (o *CollectionProductDto) GetCustomFields() []map[string]interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *CollectionProductDto) GetCustomFieldsOk() (*[]map[string]interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *CollectionProductDto) SetCustomFields(v []map[string]interface{})`

SetCustomFields sets CustomFields field to given value.


### SetCustomFieldsNil

`func (o *CollectionProductDto) SetCustomFieldsNil(b bool)`

 SetCustomFieldsNil sets the value for CustomFields to be an explicit nil

### UnsetCustomFields
`func (o *CollectionProductDto) UnsetCustomFields()`

UnsetCustomFields ensures that no value is present for CustomFields, not even an explicit nil
### GetStock

`func (o *CollectionProductDto) GetStock() int32`

GetStock returns the Stock field if non-nil, zero value otherwise.

### GetStockOk

`func (o *CollectionProductDto) GetStockOk() (*int32, bool)`

GetStockOk returns a tuple with the Stock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStock

`func (o *CollectionProductDto) SetStock(v int32)`

SetStock sets Stock field to given value.


### SetStockNil

`func (o *CollectionProductDto) SetStockNil(b bool)`

 SetStockNil sets the value for Stock to be an explicit nil

### UnsetStock
`func (o *CollectionProductDto) UnsetStock()`

UnsetStock ensures that no value is present for Stock, not even an explicit nil
### GetActivationLimit

`func (o *CollectionProductDto) GetActivationLimit() int32`

GetActivationLimit returns the ActivationLimit field if non-nil, zero value otherwise.

### GetActivationLimitOk

`func (o *CollectionProductDto) GetActivationLimitOk() (*int32, bool)`

GetActivationLimitOk returns a tuple with the ActivationLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationLimit

`func (o *CollectionProductDto) SetActivationLimit(v int32)`

SetActivationLimit sets ActivationLimit field to given value.


### GetIsListed

`func (o *CollectionProductDto) GetIsListed() bool`

GetIsListed returns the IsListed field if non-nil, zero value otherwise.

### GetIsListedOk

`func (o *CollectionProductDto) GetIsListedOk() (*bool, bool)`

GetIsListedOk returns a tuple with the IsListed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsListed

`func (o *CollectionProductDto) SetIsListed(v bool)`

SetIsListed sets IsListed field to given value.


### GetIsFree

`func (o *CollectionProductDto) GetIsFree() bool`

GetIsFree returns the IsFree field if non-nil, zero value otherwise.

### GetIsFreeOk

`func (o *CollectionProductDto) GetIsFreeOk() (*bool, bool)`

GetIsFreeOk returns a tuple with the IsFree field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFree

`func (o *CollectionProductDto) SetIsFree(v bool)`

SetIsFree sets IsFree field to given value.


### GetCreatedAt

`func (o *CollectionProductDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CollectionProductDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CollectionProductDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *CollectionProductDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CollectionProductDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CollectionProductDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetIsPermanentlyDeleted

`func (o *CollectionProductDto) GetIsPermanentlyDeleted() bool`

GetIsPermanentlyDeleted returns the IsPermanentlyDeleted field if non-nil, zero value otherwise.

### GetIsPermanentlyDeletedOk

`func (o *CollectionProductDto) GetIsPermanentlyDeletedOk() (*bool, bool)`

GetIsPermanentlyDeletedOk returns a tuple with the IsPermanentlyDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPermanentlyDeleted

`func (o *CollectionProductDto) SetIsPermanentlyDeleted(v bool)`

SetIsPermanentlyDeleted sets IsPermanentlyDeleted field to given value.


### GetBrandId

`func (o *CollectionProductDto) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *CollectionProductDto) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *CollectionProductDto) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.


### SetBrandIdNil

`func (o *CollectionProductDto) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *CollectionProductDto) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetDigitalLink

`func (o *CollectionProductDto) GetDigitalLink() string`

GetDigitalLink returns the DigitalLink field if non-nil, zero value otherwise.

### GetDigitalLinkOk

`func (o *CollectionProductDto) GetDigitalLinkOk() (*string, bool)`

GetDigitalLinkOk returns a tuple with the DigitalLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDigitalLink

`func (o *CollectionProductDto) SetDigitalLink(v string)`

SetDigitalLink sets DigitalLink field to given value.


### SetDigitalLinkNil

`func (o *CollectionProductDto) SetDigitalLinkNil(b bool)`

 SetDigitalLinkNil sets the value for DigitalLink to be an explicit nil

### UnsetDigitalLink
`func (o *CollectionProductDto) UnsetDigitalLink()`

UnsetDigitalLink ensures that no value is present for DigitalLink, not even an explicit nil
### GetInstructions

`func (o *CollectionProductDto) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *CollectionProductDto) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *CollectionProductDto) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.


### SetInstructionsNil

`func (o *CollectionProductDto) SetInstructionsNil(b bool)`

 SetInstructionsNil sets the value for Instructions to be an explicit nil

### UnsetInstructions
`func (o *CollectionProductDto) UnsetInstructions()`

UnsetInstructions ensures that no value is present for Instructions, not even an explicit nil
### GetActivationMessage

`func (o *CollectionProductDto) GetActivationMessage() string`

GetActivationMessage returns the ActivationMessage field if non-nil, zero value otherwise.

### GetActivationMessageOk

`func (o *CollectionProductDto) GetActivationMessageOk() (*string, bool)`

GetActivationMessageOk returns a tuple with the ActivationMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationMessage

`func (o *CollectionProductDto) SetActivationMessage(v string)`

SetActivationMessage sets ActivationMessage field to given value.


### SetActivationMessageNil

`func (o *CollectionProductDto) SetActivationMessageNil(b bool)`

 SetActivationMessageNil sets the value for ActivationMessage to be an explicit nil

### UnsetActivationMessage
`func (o *CollectionProductDto) UnsetActivationMessage()`

UnsetActivationMessage ensures that no value is present for ActivationMessage, not even an explicit nil
### GetExpiryHours

`func (o *CollectionProductDto) GetExpiryHours() int32`

GetExpiryHours returns the ExpiryHours field if non-nil, zero value otherwise.

### GetExpiryHoursOk

`func (o *CollectionProductDto) GetExpiryHoursOk() (*int32, bool)`

GetExpiryHoursOk returns a tuple with the ExpiryHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryHours

`func (o *CollectionProductDto) SetExpiryHours(v int32)`

SetExpiryHours sets ExpiryHours field to given value.


### SetExpiryHoursNil

`func (o *CollectionProductDto) SetExpiryHoursNil(b bool)`

 SetExpiryHoursNil sets the value for ExpiryHours to be an explicit nil

### UnsetExpiryHours
`func (o *CollectionProductDto) UnsetExpiryHours()`

UnsetExpiryHours ensures that no value is present for ExpiryHours, not even an explicit nil
### GetBusinessId

`func (o *CollectionProductDto) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *CollectionProductDto) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *CollectionProductDto) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetQuantity

`func (o *CollectionProductDto) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CollectionProductDto) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CollectionProductDto) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


