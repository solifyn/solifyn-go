# ProductUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Product display name. | [optional] 
**Description** | Pointer to **string** | A description of the product. | [optional] 
**Price** | Pointer to **float32** | Price value. | [optional] 
**Currency** | Pointer to **string** | Product pricing currency. | [optional] [default to "USD"]
**ImageUrl** | Pointer to **string** | URL of the product cover image. | [optional] 
**TaxCategory** | Pointer to **string** | Tax classification. | [optional] 
**Discount** | Pointer to **float32** | Percentage or flat rate discount. | [optional] 
**HasLicenseKey** | Pointer to **bool** | Whether to automatically issue license keys upon successful orders. | [optional] [default to false]
**HasDigitalDelivery** | Pointer to **bool** | Whether the purchase includes downloadable files. | [optional] [default to false]
**HasGithubAccess** | Pointer to **bool** | Whether the purchase includes GitHub repository access. | [optional] [default to false]
**GithubRepo** | Pointer to **string** | GitHub repository to grant access to (format: owner/repo). | [optional] 
**GithubPermission** | Pointer to **string** | GitHub collaborator permission level. | [optional] 
**HasDiscordAccess** | Pointer to **bool** | Whether the purchase includes Discord server role access. | [optional] [default to false]
**DiscordGuildId** | Pointer to **string** | Discord Guild (Server) ID to grant access to. | [optional] 
**DiscordRoleId** | Pointer to **string** | Discord Role ID to assign to the user. | [optional] 
**IsTaxInclusive** | Pointer to **bool** | Whether tax is included in the base price. | [optional] [default to false]
**ActivationLimit** | Pointer to **int32** | Maximum concurrent activated instances allowed per license key. | [optional] 
**BrandId** | Pointer to **string** | Brand id for the product, if not provided will default to primary brand. | [optional] 
**BillingPeriod** | Pointer to **int32** | Billing period in days (for Subscription products). | [optional] 
**TrialPeriodDays** | Pointer to **int32** | Trial duration in days. | [optional] 
**ExpirationDays** | Pointer to **int32** | Subscription expiration duration in days. | [optional] 
**StatementDescriptor** | Pointer to **string** | Custom billing descriptor. | [optional] 
**PayWhatYouWant** | Pointer to **bool** | Allow pay-what-you-want pricing. | [optional] [default to false]
**Metadata** | Pointer to **map[string]string** | Developer key-value metadata pairs. | [optional] 
**CustomFields** | Pointer to [**[]ProductCreateCustomFieldsInner**](ProductCreateCustomFieldsInner.md) | Form field configurations to gather during checkout. | [optional] 
**Stock** | Pointer to **int32** | Initial stock quantity limit. | [optional] 
**IsListed** | Pointer to **bool** | Whether the product is publicly visible. | [optional] [default to true]
**IsFree** | Pointer to **bool** | Whether the product is free of charge. | [optional] [default to false]
**Addons** | Pointer to [**[]ProductCreateAddonsInner**](ProductCreateAddonsInner.md) | Product addons configurations. | [optional] 
**EntitlementIds** | Pointer to **[]string** | Array of independent entitlement IDs to link to this product. | [optional] 

## Methods

### NewProductUpdate

`func NewProductUpdate() *ProductUpdate`

NewProductUpdate instantiates a new ProductUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductUpdateWithDefaults

`func NewProductUpdateWithDefaults() *ProductUpdate`

NewProductUpdateWithDefaults instantiates a new ProductUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ProductUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *ProductUpdate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProductUpdate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProductUpdate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProductUpdate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPrice

`func (o *ProductUpdate) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ProductUpdate) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ProductUpdate) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *ProductUpdate) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *ProductUpdate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ProductUpdate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ProductUpdate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ProductUpdate) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetImageUrl

`func (o *ProductUpdate) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *ProductUpdate) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *ProductUpdate) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *ProductUpdate) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### GetTaxCategory

`func (o *ProductUpdate) GetTaxCategory() string`

GetTaxCategory returns the TaxCategory field if non-nil, zero value otherwise.

### GetTaxCategoryOk

`func (o *ProductUpdate) GetTaxCategoryOk() (*string, bool)`

GetTaxCategoryOk returns a tuple with the TaxCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCategory

`func (o *ProductUpdate) SetTaxCategory(v string)`

SetTaxCategory sets TaxCategory field to given value.

### HasTaxCategory

`func (o *ProductUpdate) HasTaxCategory() bool`

HasTaxCategory returns a boolean if a field has been set.

### GetDiscount

`func (o *ProductUpdate) GetDiscount() float32`

GetDiscount returns the Discount field if non-nil, zero value otherwise.

### GetDiscountOk

`func (o *ProductUpdate) GetDiscountOk() (*float32, bool)`

GetDiscountOk returns a tuple with the Discount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscount

`func (o *ProductUpdate) SetDiscount(v float32)`

SetDiscount sets Discount field to given value.

### HasDiscount

`func (o *ProductUpdate) HasDiscount() bool`

HasDiscount returns a boolean if a field has been set.

### GetHasLicenseKey

`func (o *ProductUpdate) GetHasLicenseKey() bool`

GetHasLicenseKey returns the HasLicenseKey field if non-nil, zero value otherwise.

### GetHasLicenseKeyOk

`func (o *ProductUpdate) GetHasLicenseKeyOk() (*bool, bool)`

GetHasLicenseKeyOk returns a tuple with the HasLicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasLicenseKey

`func (o *ProductUpdate) SetHasLicenseKey(v bool)`

SetHasLicenseKey sets HasLicenseKey field to given value.

### HasHasLicenseKey

`func (o *ProductUpdate) HasHasLicenseKey() bool`

HasHasLicenseKey returns a boolean if a field has been set.

### GetHasDigitalDelivery

`func (o *ProductUpdate) GetHasDigitalDelivery() bool`

GetHasDigitalDelivery returns the HasDigitalDelivery field if non-nil, zero value otherwise.

### GetHasDigitalDeliveryOk

`func (o *ProductUpdate) GetHasDigitalDeliveryOk() (*bool, bool)`

GetHasDigitalDeliveryOk returns a tuple with the HasDigitalDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasDigitalDelivery

`func (o *ProductUpdate) SetHasDigitalDelivery(v bool)`

SetHasDigitalDelivery sets HasDigitalDelivery field to given value.

### HasHasDigitalDelivery

`func (o *ProductUpdate) HasHasDigitalDelivery() bool`

HasHasDigitalDelivery returns a boolean if a field has been set.

### GetHasGithubAccess

`func (o *ProductUpdate) GetHasGithubAccess() bool`

GetHasGithubAccess returns the HasGithubAccess field if non-nil, zero value otherwise.

### GetHasGithubAccessOk

`func (o *ProductUpdate) GetHasGithubAccessOk() (*bool, bool)`

GetHasGithubAccessOk returns a tuple with the HasGithubAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasGithubAccess

`func (o *ProductUpdate) SetHasGithubAccess(v bool)`

SetHasGithubAccess sets HasGithubAccess field to given value.

### HasHasGithubAccess

`func (o *ProductUpdate) HasHasGithubAccess() bool`

HasHasGithubAccess returns a boolean if a field has been set.

### GetGithubRepo

`func (o *ProductUpdate) GetGithubRepo() string`

GetGithubRepo returns the GithubRepo field if non-nil, zero value otherwise.

### GetGithubRepoOk

`func (o *ProductUpdate) GetGithubRepoOk() (*string, bool)`

GetGithubRepoOk returns a tuple with the GithubRepo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubRepo

`func (o *ProductUpdate) SetGithubRepo(v string)`

SetGithubRepo sets GithubRepo field to given value.

### HasGithubRepo

`func (o *ProductUpdate) HasGithubRepo() bool`

HasGithubRepo returns a boolean if a field has been set.

### GetGithubPermission

`func (o *ProductUpdate) GetGithubPermission() string`

GetGithubPermission returns the GithubPermission field if non-nil, zero value otherwise.

### GetGithubPermissionOk

`func (o *ProductUpdate) GetGithubPermissionOk() (*string, bool)`

GetGithubPermissionOk returns a tuple with the GithubPermission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubPermission

`func (o *ProductUpdate) SetGithubPermission(v string)`

SetGithubPermission sets GithubPermission field to given value.

### HasGithubPermission

`func (o *ProductUpdate) HasGithubPermission() bool`

HasGithubPermission returns a boolean if a field has been set.

### GetHasDiscordAccess

`func (o *ProductUpdate) GetHasDiscordAccess() bool`

GetHasDiscordAccess returns the HasDiscordAccess field if non-nil, zero value otherwise.

### GetHasDiscordAccessOk

`func (o *ProductUpdate) GetHasDiscordAccessOk() (*bool, bool)`

GetHasDiscordAccessOk returns a tuple with the HasDiscordAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasDiscordAccess

`func (o *ProductUpdate) SetHasDiscordAccess(v bool)`

SetHasDiscordAccess sets HasDiscordAccess field to given value.

### HasHasDiscordAccess

`func (o *ProductUpdate) HasHasDiscordAccess() bool`

HasHasDiscordAccess returns a boolean if a field has been set.

### GetDiscordGuildId

`func (o *ProductUpdate) GetDiscordGuildId() string`

GetDiscordGuildId returns the DiscordGuildId field if non-nil, zero value otherwise.

### GetDiscordGuildIdOk

`func (o *ProductUpdate) GetDiscordGuildIdOk() (*string, bool)`

GetDiscordGuildIdOk returns a tuple with the DiscordGuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordGuildId

`func (o *ProductUpdate) SetDiscordGuildId(v string)`

SetDiscordGuildId sets DiscordGuildId field to given value.

### HasDiscordGuildId

`func (o *ProductUpdate) HasDiscordGuildId() bool`

HasDiscordGuildId returns a boolean if a field has been set.

### GetDiscordRoleId

`func (o *ProductUpdate) GetDiscordRoleId() string`

GetDiscordRoleId returns the DiscordRoleId field if non-nil, zero value otherwise.

### GetDiscordRoleIdOk

`func (o *ProductUpdate) GetDiscordRoleIdOk() (*string, bool)`

GetDiscordRoleIdOk returns a tuple with the DiscordRoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordRoleId

`func (o *ProductUpdate) SetDiscordRoleId(v string)`

SetDiscordRoleId sets DiscordRoleId field to given value.

### HasDiscordRoleId

`func (o *ProductUpdate) HasDiscordRoleId() bool`

HasDiscordRoleId returns a boolean if a field has been set.

### GetIsTaxInclusive

`func (o *ProductUpdate) GetIsTaxInclusive() bool`

GetIsTaxInclusive returns the IsTaxInclusive field if non-nil, zero value otherwise.

### GetIsTaxInclusiveOk

`func (o *ProductUpdate) GetIsTaxInclusiveOk() (*bool, bool)`

GetIsTaxInclusiveOk returns a tuple with the IsTaxInclusive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTaxInclusive

`func (o *ProductUpdate) SetIsTaxInclusive(v bool)`

SetIsTaxInclusive sets IsTaxInclusive field to given value.

### HasIsTaxInclusive

`func (o *ProductUpdate) HasIsTaxInclusive() bool`

HasIsTaxInclusive returns a boolean if a field has been set.

### GetActivationLimit

`func (o *ProductUpdate) GetActivationLimit() int32`

GetActivationLimit returns the ActivationLimit field if non-nil, zero value otherwise.

### GetActivationLimitOk

`func (o *ProductUpdate) GetActivationLimitOk() (*int32, bool)`

GetActivationLimitOk returns a tuple with the ActivationLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationLimit

`func (o *ProductUpdate) SetActivationLimit(v int32)`

SetActivationLimit sets ActivationLimit field to given value.

### HasActivationLimit

`func (o *ProductUpdate) HasActivationLimit() bool`

HasActivationLimit returns a boolean if a field has been set.

### GetBrandId

`func (o *ProductUpdate) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *ProductUpdate) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *ProductUpdate) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.

### HasBrandId

`func (o *ProductUpdate) HasBrandId() bool`

HasBrandId returns a boolean if a field has been set.

### GetBillingPeriod

`func (o *ProductUpdate) GetBillingPeriod() int32`

GetBillingPeriod returns the BillingPeriod field if non-nil, zero value otherwise.

### GetBillingPeriodOk

`func (o *ProductUpdate) GetBillingPeriodOk() (*int32, bool)`

GetBillingPeriodOk returns a tuple with the BillingPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingPeriod

`func (o *ProductUpdate) SetBillingPeriod(v int32)`

SetBillingPeriod sets BillingPeriod field to given value.

### HasBillingPeriod

`func (o *ProductUpdate) HasBillingPeriod() bool`

HasBillingPeriod returns a boolean if a field has been set.

### GetTrialPeriodDays

`func (o *ProductUpdate) GetTrialPeriodDays() int32`

GetTrialPeriodDays returns the TrialPeriodDays field if non-nil, zero value otherwise.

### GetTrialPeriodDaysOk

`func (o *ProductUpdate) GetTrialPeriodDaysOk() (*int32, bool)`

GetTrialPeriodDaysOk returns a tuple with the TrialPeriodDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialPeriodDays

`func (o *ProductUpdate) SetTrialPeriodDays(v int32)`

SetTrialPeriodDays sets TrialPeriodDays field to given value.

### HasTrialPeriodDays

`func (o *ProductUpdate) HasTrialPeriodDays() bool`

HasTrialPeriodDays returns a boolean if a field has been set.

### GetExpirationDays

`func (o *ProductUpdate) GetExpirationDays() int32`

GetExpirationDays returns the ExpirationDays field if non-nil, zero value otherwise.

### GetExpirationDaysOk

`func (o *ProductUpdate) GetExpirationDaysOk() (*int32, bool)`

GetExpirationDaysOk returns a tuple with the ExpirationDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDays

`func (o *ProductUpdate) SetExpirationDays(v int32)`

SetExpirationDays sets ExpirationDays field to given value.

### HasExpirationDays

`func (o *ProductUpdate) HasExpirationDays() bool`

HasExpirationDays returns a boolean if a field has been set.

### GetStatementDescriptor

`func (o *ProductUpdate) GetStatementDescriptor() string`

GetStatementDescriptor returns the StatementDescriptor field if non-nil, zero value otherwise.

### GetStatementDescriptorOk

`func (o *ProductUpdate) GetStatementDescriptorOk() (*string, bool)`

GetStatementDescriptorOk returns a tuple with the StatementDescriptor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatementDescriptor

`func (o *ProductUpdate) SetStatementDescriptor(v string)`

SetStatementDescriptor sets StatementDescriptor field to given value.

### HasStatementDescriptor

`func (o *ProductUpdate) HasStatementDescriptor() bool`

HasStatementDescriptor returns a boolean if a field has been set.

### GetPayWhatYouWant

`func (o *ProductUpdate) GetPayWhatYouWant() bool`

GetPayWhatYouWant returns the PayWhatYouWant field if non-nil, zero value otherwise.

### GetPayWhatYouWantOk

`func (o *ProductUpdate) GetPayWhatYouWantOk() (*bool, bool)`

GetPayWhatYouWantOk returns a tuple with the PayWhatYouWant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayWhatYouWant

`func (o *ProductUpdate) SetPayWhatYouWant(v bool)`

SetPayWhatYouWant sets PayWhatYouWant field to given value.

### HasPayWhatYouWant

`func (o *ProductUpdate) HasPayWhatYouWant() bool`

HasPayWhatYouWant returns a boolean if a field has been set.

### GetMetadata

`func (o *ProductUpdate) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ProductUpdate) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ProductUpdate) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ProductUpdate) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetCustomFields

`func (o *ProductUpdate) GetCustomFields() []ProductCreateCustomFieldsInner`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *ProductUpdate) GetCustomFieldsOk() (*[]ProductCreateCustomFieldsInner, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *ProductUpdate) SetCustomFields(v []ProductCreateCustomFieldsInner)`

SetCustomFields sets CustomFields field to given value.

### HasCustomFields

`func (o *ProductUpdate) HasCustomFields() bool`

HasCustomFields returns a boolean if a field has been set.

### GetStock

`func (o *ProductUpdate) GetStock() int32`

GetStock returns the Stock field if non-nil, zero value otherwise.

### GetStockOk

`func (o *ProductUpdate) GetStockOk() (*int32, bool)`

GetStockOk returns a tuple with the Stock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStock

`func (o *ProductUpdate) SetStock(v int32)`

SetStock sets Stock field to given value.

### HasStock

`func (o *ProductUpdate) HasStock() bool`

HasStock returns a boolean if a field has been set.

### GetIsListed

`func (o *ProductUpdate) GetIsListed() bool`

GetIsListed returns the IsListed field if non-nil, zero value otherwise.

### GetIsListedOk

`func (o *ProductUpdate) GetIsListedOk() (*bool, bool)`

GetIsListedOk returns a tuple with the IsListed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsListed

`func (o *ProductUpdate) SetIsListed(v bool)`

SetIsListed sets IsListed field to given value.

### HasIsListed

`func (o *ProductUpdate) HasIsListed() bool`

HasIsListed returns a boolean if a field has been set.

### GetIsFree

`func (o *ProductUpdate) GetIsFree() bool`

GetIsFree returns the IsFree field if non-nil, zero value otherwise.

### GetIsFreeOk

`func (o *ProductUpdate) GetIsFreeOk() (*bool, bool)`

GetIsFreeOk returns a tuple with the IsFree field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFree

`func (o *ProductUpdate) SetIsFree(v bool)`

SetIsFree sets IsFree field to given value.

### HasIsFree

`func (o *ProductUpdate) HasIsFree() bool`

HasIsFree returns a boolean if a field has been set.

### GetAddons

`func (o *ProductUpdate) GetAddons() []ProductCreateAddonsInner`

GetAddons returns the Addons field if non-nil, zero value otherwise.

### GetAddonsOk

`func (o *ProductUpdate) GetAddonsOk() (*[]ProductCreateAddonsInner, bool)`

GetAddonsOk returns a tuple with the Addons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddons

`func (o *ProductUpdate) SetAddons(v []ProductCreateAddonsInner)`

SetAddons sets Addons field to given value.

### HasAddons

`func (o *ProductUpdate) HasAddons() bool`

HasAddons returns a boolean if a field has been set.

### GetEntitlementIds

`func (o *ProductUpdate) GetEntitlementIds() []string`

GetEntitlementIds returns the EntitlementIds field if non-nil, zero value otherwise.

### GetEntitlementIdsOk

`func (o *ProductUpdate) GetEntitlementIdsOk() (*[]string, bool)`

GetEntitlementIdsOk returns a tuple with the EntitlementIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntitlementIds

`func (o *ProductUpdate) SetEntitlementIds(v []string)`

SetEntitlementIds sets EntitlementIds field to given value.

### HasEntitlementIds

`func (o *ProductUpdate) HasEntitlementIds() bool`

HasEntitlementIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


