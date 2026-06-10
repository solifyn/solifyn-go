# Brand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique brand ID | 
**Name** | **string** | The brand name | 
**WebsiteUrl** | Pointer to **string** | The website URL associated with the brand | [optional] 
**SupportEmail** | Pointer to **string** | Support email address for customer service | [optional] 
**Description** | Pointer to **string** | Short description of the brand | [optional] 
**LogoUrl** | Pointer to **string** | Brand logo image URL | [optional] 
**IsPrimary** | **bool** | Whether this is the primary brand for the merchant business | 
**StatementDescriptor** | Pointer to **string** | Credit card statement descriptor | [optional] 
**MerchantId** | **string** | The merchant ID owning the brand | 
**BusinessId** | Pointer to **string** | The business ID linked to the brand | [optional] 
**CreatedAt** | **time.Time** | Timestamp when the brand was created | 
**UpdatedAt** | **time.Time** | Timestamp when the brand was last updated | 

## Methods

### NewBrand

`func NewBrand(id string, name string, isPrimary bool, merchantId string, createdAt time.Time, updatedAt time.Time, ) *Brand`

NewBrand instantiates a new Brand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBrandWithDefaults

`func NewBrandWithDefaults() *Brand`

NewBrandWithDefaults instantiates a new Brand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Brand) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Brand) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Brand) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *Brand) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Brand) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Brand) SetName(v string)`

SetName sets Name field to given value.


### GetWebsiteUrl

`func (o *Brand) GetWebsiteUrl() string`

GetWebsiteUrl returns the WebsiteUrl field if non-nil, zero value otherwise.

### GetWebsiteUrlOk

`func (o *Brand) GetWebsiteUrlOk() (*string, bool)`

GetWebsiteUrlOk returns a tuple with the WebsiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsiteUrl

`func (o *Brand) SetWebsiteUrl(v string)`

SetWebsiteUrl sets WebsiteUrl field to given value.

### HasWebsiteUrl

`func (o *Brand) HasWebsiteUrl() bool`

HasWebsiteUrl returns a boolean if a field has been set.

### GetSupportEmail

`func (o *Brand) GetSupportEmail() string`

GetSupportEmail returns the SupportEmail field if non-nil, zero value otherwise.

### GetSupportEmailOk

`func (o *Brand) GetSupportEmailOk() (*string, bool)`

GetSupportEmailOk returns a tuple with the SupportEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportEmail

`func (o *Brand) SetSupportEmail(v string)`

SetSupportEmail sets SupportEmail field to given value.

### HasSupportEmail

`func (o *Brand) HasSupportEmail() bool`

HasSupportEmail returns a boolean if a field has been set.

### GetDescription

`func (o *Brand) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Brand) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Brand) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Brand) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetLogoUrl

`func (o *Brand) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *Brand) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *Brand) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.

### HasLogoUrl

`func (o *Brand) HasLogoUrl() bool`

HasLogoUrl returns a boolean if a field has been set.

### GetIsPrimary

`func (o *Brand) GetIsPrimary() bool`

GetIsPrimary returns the IsPrimary field if non-nil, zero value otherwise.

### GetIsPrimaryOk

`func (o *Brand) GetIsPrimaryOk() (*bool, bool)`

GetIsPrimaryOk returns a tuple with the IsPrimary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPrimary

`func (o *Brand) SetIsPrimary(v bool)`

SetIsPrimary sets IsPrimary field to given value.


### GetStatementDescriptor

`func (o *Brand) GetStatementDescriptor() string`

GetStatementDescriptor returns the StatementDescriptor field if non-nil, zero value otherwise.

### GetStatementDescriptorOk

`func (o *Brand) GetStatementDescriptorOk() (*string, bool)`

GetStatementDescriptorOk returns a tuple with the StatementDescriptor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatementDescriptor

`func (o *Brand) SetStatementDescriptor(v string)`

SetStatementDescriptor sets StatementDescriptor field to given value.

### HasStatementDescriptor

`func (o *Brand) HasStatementDescriptor() bool`

HasStatementDescriptor returns a boolean if a field has been set.

### GetMerchantId

`func (o *Brand) GetMerchantId() string`

GetMerchantId returns the MerchantId field if non-nil, zero value otherwise.

### GetMerchantIdOk

`func (o *Brand) GetMerchantIdOk() (*string, bool)`

GetMerchantIdOk returns a tuple with the MerchantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchantId

`func (o *Brand) SetMerchantId(v string)`

SetMerchantId sets MerchantId field to given value.


### GetBusinessId

`func (o *Brand) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *Brand) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *Brand) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.

### HasBusinessId

`func (o *Brand) HasBusinessId() bool`

HasBusinessId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Brand) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Brand) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Brand) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Brand) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Brand) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Brand) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


