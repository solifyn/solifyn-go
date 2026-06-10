# BrandCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Name of the brand | 
**WebsiteUrl** | Pointer to **string** | The website URL associated with the brand | [optional] 
**SupportEmail** | Pointer to **string** | Support email address for customer service | [optional] 
**Description** | Pointer to **string** | Short description of the brand | [optional] 
**LogoUrl** | Pointer to **string** | Brand logo image URL | [optional] 
**StatementDescriptor** | Pointer to **string** | Credit card statement descriptor (Max 22 chars) | [optional] 

## Methods

### NewBrandCreate

`func NewBrandCreate(name string, ) *BrandCreate`

NewBrandCreate instantiates a new BrandCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBrandCreateWithDefaults

`func NewBrandCreateWithDefaults() *BrandCreate`

NewBrandCreateWithDefaults instantiates a new BrandCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *BrandCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *BrandCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *BrandCreate) SetName(v string)`

SetName sets Name field to given value.


### GetWebsiteUrl

`func (o *BrandCreate) GetWebsiteUrl() string`

GetWebsiteUrl returns the WebsiteUrl field if non-nil, zero value otherwise.

### GetWebsiteUrlOk

`func (o *BrandCreate) GetWebsiteUrlOk() (*string, bool)`

GetWebsiteUrlOk returns a tuple with the WebsiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsiteUrl

`func (o *BrandCreate) SetWebsiteUrl(v string)`

SetWebsiteUrl sets WebsiteUrl field to given value.

### HasWebsiteUrl

`func (o *BrandCreate) HasWebsiteUrl() bool`

HasWebsiteUrl returns a boolean if a field has been set.

### GetSupportEmail

`func (o *BrandCreate) GetSupportEmail() string`

GetSupportEmail returns the SupportEmail field if non-nil, zero value otherwise.

### GetSupportEmailOk

`func (o *BrandCreate) GetSupportEmailOk() (*string, bool)`

GetSupportEmailOk returns a tuple with the SupportEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportEmail

`func (o *BrandCreate) SetSupportEmail(v string)`

SetSupportEmail sets SupportEmail field to given value.

### HasSupportEmail

`func (o *BrandCreate) HasSupportEmail() bool`

HasSupportEmail returns a boolean if a field has been set.

### GetDescription

`func (o *BrandCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *BrandCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *BrandCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *BrandCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetLogoUrl

`func (o *BrandCreate) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *BrandCreate) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *BrandCreate) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.

### HasLogoUrl

`func (o *BrandCreate) HasLogoUrl() bool`

HasLogoUrl returns a boolean if a field has been set.

### GetStatementDescriptor

`func (o *BrandCreate) GetStatementDescriptor() string`

GetStatementDescriptor returns the StatementDescriptor field if non-nil, zero value otherwise.

### GetStatementDescriptorOk

`func (o *BrandCreate) GetStatementDescriptorOk() (*string, bool)`

GetStatementDescriptorOk returns a tuple with the StatementDescriptor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatementDescriptor

`func (o *BrandCreate) SetStatementDescriptor(v string)`

SetStatementDescriptor sets StatementDescriptor field to given value.

### HasStatementDescriptor

`func (o *BrandCreate) HasStatementDescriptor() bool`

HasStatementDescriptor returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


