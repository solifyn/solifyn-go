# ProductCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Product display name. | 
**Description** | Pointer to **string** | A description of the product. | [optional] 
**Price** | **float32** | Price value. | 
**Currency** | **string** | Product pricing currency. | [default to "USD"]
**ImageUrl** | Pointer to **string** | URL of the product cover image. | [optional] 
**TaxCategory** | **string** | Tax classification. | 
**Discount** | Pointer to **float32** | Percentage or flat rate discount. | [optional] 
**HasLicenseKey** | Pointer to **bool** | Whether to automatically issue license keys upon successful orders. | [optional] [default to false]
**HasDigitalDelivery** | Pointer to **bool** | Whether the purchase includes downloadable files. | [optional] [default to false]
**HasGithubAccess** | Pointer to **bool** | Whether the purchase includes GitHub repository access. | [optional] [default to false]
**GithubRepo** | Pointer to **string** | GitHub repository to grant access to (format: owner/repo). | [optional] 
**GithubPermission** | Pointer to **string** | GitHub collaborator permission level. | [optional] 
**IsTaxInclusive** | Pointer to **bool** | Whether tax is included in the base price. | [optional] [default to false]
**ActivationLimit** | Pointer to **NullableInt32** | Maximum concurrent activated instances allowed per license key. | [optional] 
**BrandId** | Pointer to **NullableString** | Brand id for the product, if not provided will default to primary brand. | [optional] 
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

## Methods

### NewProductCreate

`func NewProductCreate(name string, price float32, currency string, taxCategory string, ) *ProductCreate`

NewProductCreate instantiates a new ProductCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductCreateWithDefaults

`func NewProductCreateWithDefaults() *ProductCreate`

NewProductCreateWithDefaults instantiates a new ProductCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ProductCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductCreate) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *ProductCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProductCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProductCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProductCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPrice

`func (o *ProductCreate) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ProductCreate) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ProductCreate) SetPrice(v float32)`

SetPrice sets Price field to given value.


### GetCurrency

`func (o *ProductCreate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ProductCreate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ProductCreate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetImageUrl

`func (o *ProductCreate) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *ProductCreate) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *ProductCreate) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *ProductCreate) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### GetTaxCategory

`func (o *ProductCreate) GetTaxCategory() string`

GetTaxCategory returns the TaxCategory field if non-nil, zero value otherwise.

### GetTaxCategoryOk

`func (o *ProductCreate) GetTaxCategoryOk() (*string, bool)`

GetTaxCategoryOk returns a tuple with the TaxCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCategory

`func (o *ProductCreate) SetTaxCategory(v string)`

SetTaxCategory sets TaxCategory field to given value.


### GetDiscount

`func (o *ProductCreate) GetDiscount() float32`

GetDiscount returns the Discount field if non-nil, zero value otherwise.

### GetDiscountOk

`func (o *ProductCreate) GetDiscountOk() (*float32, bool)`

GetDiscountOk returns a tuple with the Discount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscount

`func (o *ProductCreate) SetDiscount(v float32)`

SetDiscount sets Discount field to given value.

### HasDiscount

`func (o *ProductCreate) HasDiscount() bool`

HasDiscount returns a boolean if a field has been set.

### GetHasLicenseKey

`func (o *ProductCreate) GetHasLicenseKey() bool`

GetHasLicenseKey returns the HasLicenseKey field if non-nil, zero value otherwise.

### GetHasLicenseKeyOk

`func (o *ProductCreate) GetHasLicenseKeyOk() (*bool, bool)`

GetHasLicenseKeyOk returns a tuple with the HasLicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasLicenseKey

`func (o *ProductCreate) SetHasLicenseKey(v bool)`

SetHasLicenseKey sets HasLicenseKey field to given value.

### HasHasLicenseKey

`func (o *ProductCreate) HasHasLicenseKey() bool`

HasHasLicenseKey returns a boolean if a field has been set.

### GetHasDigitalDelivery

`func (o *ProductCreate) GetHasDigitalDelivery() bool`

GetHasDigitalDelivery returns the HasDigitalDelivery field if non-nil, zero value otherwise.

### GetHasDigitalDeliveryOk

`func (o *ProductCreate) GetHasDigitalDeliveryOk() (*bool, bool)`

GetHasDigitalDeliveryOk returns a tuple with the HasDigitalDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasDigitalDelivery

`func (o *ProductCreate) SetHasDigitalDelivery(v bool)`

SetHasDigitalDelivery sets HasDigitalDelivery field to given value.

### HasHasDigitalDelivery

`func (o *ProductCreate) HasHasDigitalDelivery() bool`

HasHasDigitalDelivery returns a boolean if a field has been set.

### GetHasGithubAccess

`func (o *ProductCreate) GetHasGithubAccess() bool`

GetHasGithubAccess returns the HasGithubAccess field if non-nil, zero value otherwise.

### GetHasGithubAccessOk

`func (o *ProductCreate) GetHasGithubAccessOk() (*bool, bool)`

GetHasGithubAccessOk returns a tuple with the HasGithubAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasGithubAccess

`func (o *ProductCreate) SetHasGithubAccess(v bool)`

SetHasGithubAccess sets HasGithubAccess field to given value.

### HasHasGithubAccess

`func (o *ProductCreate) HasHasGithubAccess() bool`

HasHasGithubAccess returns a boolean if a field has been set.

### GetGithubRepo

`func (o *ProductCreate) GetGithubRepo() string`

GetGithubRepo returns the GithubRepo field if non-nil, zero value otherwise.

### GetGithubRepoOk

`func (o *ProductCreate) GetGithubRepoOk() (*string, bool)`

GetGithubRepoOk returns a tuple with the GithubRepo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubRepo

`func (o *ProductCreate) SetGithubRepo(v string)`

SetGithubRepo sets GithubRepo field to given value.

### HasGithubRepo

`func (o *ProductCreate) HasGithubRepo() bool`

HasGithubRepo returns a boolean if a field has been set.

### GetGithubPermission

`func (o *ProductCreate) GetGithubPermission() string`

GetGithubPermission returns the GithubPermission field if non-nil, zero value otherwise.

### GetGithubPermissionOk

`func (o *ProductCreate) GetGithubPermissionOk() (*string, bool)`

GetGithubPermissionOk returns a tuple with the GithubPermission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubPermission

`func (o *ProductCreate) SetGithubPermission(v string)`

SetGithubPermission sets GithubPermission field to given value.

### HasGithubPermission

`func (o *ProductCreate) HasGithubPermission() bool`

HasGithubPermission returns a boolean if a field has been set.

### GetIsTaxInclusive

`func (o *ProductCreate) GetIsTaxInclusive() bool`

GetIsTaxInclusive returns the IsTaxInclusive field if non-nil, zero value otherwise.

### GetIsTaxInclusiveOk

`func (o *ProductCreate) GetIsTaxInclusiveOk() (*bool, bool)`

GetIsTaxInclusiveOk returns a tuple with the IsTaxInclusive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTaxInclusive

`func (o *ProductCreate) SetIsTaxInclusive(v bool)`

SetIsTaxInclusive sets IsTaxInclusive field to given value.

### HasIsTaxInclusive

`func (o *ProductCreate) HasIsTaxInclusive() bool`

HasIsTaxInclusive returns a boolean if a field has been set.

### GetActivationLimit

`func (o *ProductCreate) GetActivationLimit() int32`

GetActivationLimit returns the ActivationLimit field if non-nil, zero value otherwise.

### GetActivationLimitOk

`func (o *ProductCreate) GetActivationLimitOk() (*int32, bool)`

GetActivationLimitOk returns a tuple with the ActivationLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationLimit

`func (o *ProductCreate) SetActivationLimit(v int32)`

SetActivationLimit sets ActivationLimit field to given value.

### HasActivationLimit

`func (o *ProductCreate) HasActivationLimit() bool`

HasActivationLimit returns a boolean if a field has been set.

### SetActivationLimitNil

`func (o *ProductCreate) SetActivationLimitNil(b bool)`

 SetActivationLimitNil sets the value for ActivationLimit to be an explicit nil

### UnsetActivationLimit
`func (o *ProductCreate) UnsetActivationLimit()`

UnsetActivationLimit ensures that no value is present for ActivationLimit, not even an explicit nil
### GetBrandId

`func (o *ProductCreate) GetBrandId() string`

GetBrandId returns the BrandId field if non-nil, zero value otherwise.

### GetBrandIdOk

`func (o *ProductCreate) GetBrandIdOk() (*string, bool)`

GetBrandIdOk returns a tuple with the BrandId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandId

`func (o *ProductCreate) SetBrandId(v string)`

SetBrandId sets BrandId field to given value.

### HasBrandId

`func (o *ProductCreate) HasBrandId() bool`

HasBrandId returns a boolean if a field has been set.

### SetBrandIdNil

`func (o *ProductCreate) SetBrandIdNil(b bool)`

 SetBrandIdNil sets the value for BrandId to be an explicit nil

### UnsetBrandId
`func (o *ProductCreate) UnsetBrandId()`

UnsetBrandId ensures that no value is present for BrandId, not even an explicit nil
### GetBillingPeriod

`func (o *ProductCreate) GetBillingPeriod() int32`

GetBillingPeriod returns the BillingPeriod field if non-nil, zero value otherwise.

### GetBillingPeriodOk

`func (o *ProductCreate) GetBillingPeriodOk() (*int32, bool)`

GetBillingPeriodOk returns a tuple with the BillingPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingPeriod

`func (o *ProductCreate) SetBillingPeriod(v int32)`

SetBillingPeriod sets BillingPeriod field to given value.

### HasBillingPeriod

`func (o *ProductCreate) HasBillingPeriod() bool`

HasBillingPeriod returns a boolean if a field has been set.

### GetTrialPeriodDays

`func (o *ProductCreate) GetTrialPeriodDays() int32`

GetTrialPeriodDays returns the TrialPeriodDays field if non-nil, zero value otherwise.

### GetTrialPeriodDaysOk

`func (o *ProductCreate) GetTrialPeriodDaysOk() (*int32, bool)`

GetTrialPeriodDaysOk returns a tuple with the TrialPeriodDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialPeriodDays

`func (o *ProductCreate) SetTrialPeriodDays(v int32)`

SetTrialPeriodDays sets TrialPeriodDays field to given value.

### HasTrialPeriodDays

`func (o *ProductCreate) HasTrialPeriodDays() bool`

HasTrialPeriodDays returns a boolean if a field has been set.

### GetExpirationDays

`func (o *ProductCreate) GetExpirationDays() int32`

GetExpirationDays returns the ExpirationDays field if non-nil, zero value otherwise.

### GetExpirationDaysOk

`func (o *ProductCreate) GetExpirationDaysOk() (*int32, bool)`

GetExpirationDaysOk returns a tuple with the ExpirationDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDays

`func (o *ProductCreate) SetExpirationDays(v int32)`

SetExpirationDays sets ExpirationDays field to given value.

### HasExpirationDays

`func (o *ProductCreate) HasExpirationDays() bool`

HasExpirationDays returns a boolean if a field has been set.

### GetStatementDescriptor

`func (o *ProductCreate) GetStatementDescriptor() string`

GetStatementDescriptor returns the StatementDescriptor field if non-nil, zero value otherwise.

### GetStatementDescriptorOk

`func (o *ProductCreate) GetStatementDescriptorOk() (*string, bool)`

GetStatementDescriptorOk returns a tuple with the StatementDescriptor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatementDescriptor

`func (o *ProductCreate) SetStatementDescriptor(v string)`

SetStatementDescriptor sets StatementDescriptor field to given value.

### HasStatementDescriptor

`func (o *ProductCreate) HasStatementDescriptor() bool`

HasStatementDescriptor returns a boolean if a field has been set.

### GetPayWhatYouWant

`func (o *ProductCreate) GetPayWhatYouWant() bool`

GetPayWhatYouWant returns the PayWhatYouWant field if non-nil, zero value otherwise.

### GetPayWhatYouWantOk

`func (o *ProductCreate) GetPayWhatYouWantOk() (*bool, bool)`

GetPayWhatYouWantOk returns a tuple with the PayWhatYouWant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayWhatYouWant

`func (o *ProductCreate) SetPayWhatYouWant(v bool)`

SetPayWhatYouWant sets PayWhatYouWant field to given value.

### HasPayWhatYouWant

`func (o *ProductCreate) HasPayWhatYouWant() bool`

HasPayWhatYouWant returns a boolean if a field has been set.

### GetMetadata

`func (o *ProductCreate) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ProductCreate) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ProductCreate) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ProductCreate) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetCustomFields

`func (o *ProductCreate) GetCustomFields() []ProductCreateCustomFieldsInner`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *ProductCreate) GetCustomFieldsOk() (*[]ProductCreateCustomFieldsInner, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *ProductCreate) SetCustomFields(v []ProductCreateCustomFieldsInner)`

SetCustomFields sets CustomFields field to given value.

### HasCustomFields

`func (o *ProductCreate) HasCustomFields() bool`

HasCustomFields returns a boolean if a field has been set.

### GetStock

`func (o *ProductCreate) GetStock() int32`

GetStock returns the Stock field if non-nil, zero value otherwise.

### GetStockOk

`func (o *ProductCreate) GetStockOk() (*int32, bool)`

GetStockOk returns a tuple with the Stock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStock

`func (o *ProductCreate) SetStock(v int32)`

SetStock sets Stock field to given value.

### HasStock

`func (o *ProductCreate) HasStock() bool`

HasStock returns a boolean if a field has been set.

### GetIsListed

`func (o *ProductCreate) GetIsListed() bool`

GetIsListed returns the IsListed field if non-nil, zero value otherwise.

### GetIsListedOk

`func (o *ProductCreate) GetIsListedOk() (*bool, bool)`

GetIsListedOk returns a tuple with the IsListed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsListed

`func (o *ProductCreate) SetIsListed(v bool)`

SetIsListed sets IsListed field to given value.

### HasIsListed

`func (o *ProductCreate) HasIsListed() bool`

HasIsListed returns a boolean if a field has been set.

### GetIsFree

`func (o *ProductCreate) GetIsFree() bool`

GetIsFree returns the IsFree field if non-nil, zero value otherwise.

### GetIsFreeOk

`func (o *ProductCreate) GetIsFreeOk() (*bool, bool)`

GetIsFreeOk returns a tuple with the IsFree field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFree

`func (o *ProductCreate) SetIsFree(v bool)`

SetIsFree sets IsFree field to given value.

### HasIsFree

`func (o *ProductCreate) HasIsFree() bool`

HasIsFree returns a boolean if a field has been set.

### GetAddons

`func (o *ProductCreate) GetAddons() []ProductCreateAddonsInner`

GetAddons returns the Addons field if non-nil, zero value otherwise.

### GetAddonsOk

`func (o *ProductCreate) GetAddonsOk() (*[]ProductCreateAddonsInner, bool)`

GetAddonsOk returns a tuple with the Addons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddons

`func (o *ProductCreate) SetAddons(v []ProductCreateAddonsInner)`

SetAddons sets Addons field to given value.

### HasAddons

`func (o *ProductCreate) HasAddons() bool`

HasAddons returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


