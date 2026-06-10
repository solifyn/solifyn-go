# CollectionProductDto

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
**HasGithubAccess** | **bool** | Whether the product includes GitHub repository access. | 
**GithubRepo** | **string** | GitHub repository to grant access to (format: owner/repo). | 
**GithubPermission** | **string** | GitHub collaborator permission level. | 
**HasDiscordAccess** | **bool** | Whether the product includes Discord role access. | 
**DiscordGuildId** | **string** | Discord Guild (Server) ID to grant access to. | 
**DiscordRoleId** | **string** | Discord Role ID to assign to the user. | 
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
**IsFree** | **bool** | Whether the product is free. | 
**CreatedAt** | **time.Time** | Timestamp indicating exactly when the product was created. | 
**UpdatedAt** | **time.Time** | Timestamp indicating when the product was last modified. | 
**IsPermanentlyDeleted** | **bool** | Indicates if the product has been permanently deleted. | 
**BrandId** | **string** | Optional brand identifier. | 
**DigitalLink** | **string** | Secure link for digital delivery. | 
**Instructions** | **string** | Special instructions provided upon purchase. | 
**ActivationMessage** | **string** | Custom message displayed when a license key is activated. | 
**ExpiryHours** | **int32** | Number of hours until the license key expires. | 
**BusinessId** | **string** | The unique identifier of the business owning this product. | 
**Quantity** | **float32** | Quantity of the product in the collection | 

## Methods

### NewCollectionProductDto

`func NewCollectionProductDto(id string, name string, price float32, currency string, status string, imageUrl string, taxCategory string, pricingType string, discount float32, hasLicenseKey bool, hasDigitalDelivery bool, hasGithubAccess bool, githubRepo string, githubPermission string, hasDiscordAccess bool, discordGuildId string, discordRoleId string, isTaxInclusive bool, billingPeriod int32, trialPeriodDays int32, expirationDays int32, statementDescriptor string, payWhatYouWant bool, metadata map[string]string, customFields []map[string]interface{}, stock int32, activationLimit int32, isListed bool, isFree bool, createdAt time.Time, updatedAt time.Time, isPermanentlyDeleted bool, brandId string, digitalLink string, instructions string, activationMessage string, expiryHours int32, businessId string, quantity float32, ) *CollectionProductDto`

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


### GetHasDiscordAccess

`func (o *CollectionProductDto) GetHasDiscordAccess() bool`

GetHasDiscordAccess returns the HasDiscordAccess field if non-nil, zero value otherwise.

### GetHasDiscordAccessOk

`func (o *CollectionProductDto) GetHasDiscordAccessOk() (*bool, bool)`

GetHasDiscordAccessOk returns a tuple with the HasDiscordAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasDiscordAccess

`func (o *CollectionProductDto) SetHasDiscordAccess(v bool)`

SetHasDiscordAccess sets HasDiscordAccess field to given value.


### GetDiscordGuildId

`func (o *CollectionProductDto) GetDiscordGuildId() string`

GetDiscordGuildId returns the DiscordGuildId field if non-nil, zero value otherwise.

### GetDiscordGuildIdOk

`func (o *CollectionProductDto) GetDiscordGuildIdOk() (*string, bool)`

GetDiscordGuildIdOk returns a tuple with the DiscordGuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordGuildId

`func (o *CollectionProductDto) SetDiscordGuildId(v string)`

SetDiscordGuildId sets DiscordGuildId field to given value.


### GetDiscordRoleId

`func (o *CollectionProductDto) GetDiscordRoleId() string`

GetDiscordRoleId returns the DiscordRoleId field if non-nil, zero value otherwise.

### GetDiscordRoleIdOk

`func (o *CollectionProductDto) GetDiscordRoleIdOk() (*string, bool)`

GetDiscordRoleIdOk returns a tuple with the DiscordRoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordRoleId

`func (o *CollectionProductDto) SetDiscordRoleId(v string)`

SetDiscordRoleId sets DiscordRoleId field to given value.


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


