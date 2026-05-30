# Business

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique business ID | 
**Title** | **string** | Title or name of the business | 
**Description** | Pointer to **string** | A description explaining what the business does | [optional] 
**WhopId** | **string** | The Whop Company ID | 
**MerchantId** | **string** | The merchant owner ID | 
**Verified** | **bool** | Whether the business has been KYC-verified on Whop | 
**SendCustomerEmails** | **bool** | Whether auto-emails are enabled for customers | 
**MemberCount** | **float32** | Total members/customers under this business | 
**Route** | Pointer to **string** | Whop friendly URL path route | [optional] 
**DefaultCurrency** | **string** | The default currency of the business | 
**PublishedReviewsCount** | **float32** | Number of published user reviews on Whop | 
**Metadata** | Pointer to **map[string]interface{}** | Custom key-value metadata | [optional] 
**TargetAudience** | Pointer to **string** | The target audience description | [optional] 
**SocialLinks** | Pointer to **map[string]interface{}** | Social links setup | [optional] 
**AffiliateInstructions** | Pointer to **string** | Markdown instructions for affiliates | [optional] 
**WhopCreatedAt** | Pointer to **time.Time** | Whop account creation timestamp | [optional] 
**WhopUpdatedAt** | Pointer to **time.Time** | Whop account last updated timestamp | [optional] 
**CreatedAt** | **time.Time** | Timestamp when the business record was created | 
**UpdatedAt** | **time.Time** | Timestamp when the business record was last updated | 
**LogoUrl** | Pointer to **string** | Brand logo image URL resolved from primary brand | [optional] 

## Methods

### NewBusiness

`func NewBusiness(id string, title string, whopId string, merchantId string, verified bool, sendCustomerEmails bool, memberCount float32, defaultCurrency string, publishedReviewsCount float32, createdAt time.Time, updatedAt time.Time, ) *Business`

NewBusiness instantiates a new Business object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBusinessWithDefaults

`func NewBusinessWithDefaults() *Business`

NewBusinessWithDefaults instantiates a new Business object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Business) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Business) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Business) SetId(v string)`

SetId sets Id field to given value.


### GetTitle

`func (o *Business) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Business) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Business) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetDescription

`func (o *Business) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Business) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Business) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Business) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetWhopId

`func (o *Business) GetWhopId() string`

GetWhopId returns the WhopId field if non-nil, zero value otherwise.

### GetWhopIdOk

`func (o *Business) GetWhopIdOk() (*string, bool)`

GetWhopIdOk returns a tuple with the WhopId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhopId

`func (o *Business) SetWhopId(v string)`

SetWhopId sets WhopId field to given value.


### GetMerchantId

`func (o *Business) GetMerchantId() string`

GetMerchantId returns the MerchantId field if non-nil, zero value otherwise.

### GetMerchantIdOk

`func (o *Business) GetMerchantIdOk() (*string, bool)`

GetMerchantIdOk returns a tuple with the MerchantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchantId

`func (o *Business) SetMerchantId(v string)`

SetMerchantId sets MerchantId field to given value.


### GetVerified

`func (o *Business) GetVerified() bool`

GetVerified returns the Verified field if non-nil, zero value otherwise.

### GetVerifiedOk

`func (o *Business) GetVerifiedOk() (*bool, bool)`

GetVerifiedOk returns a tuple with the Verified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerified

`func (o *Business) SetVerified(v bool)`

SetVerified sets Verified field to given value.


### GetSendCustomerEmails

`func (o *Business) GetSendCustomerEmails() bool`

GetSendCustomerEmails returns the SendCustomerEmails field if non-nil, zero value otherwise.

### GetSendCustomerEmailsOk

`func (o *Business) GetSendCustomerEmailsOk() (*bool, bool)`

GetSendCustomerEmailsOk returns a tuple with the SendCustomerEmails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendCustomerEmails

`func (o *Business) SetSendCustomerEmails(v bool)`

SetSendCustomerEmails sets SendCustomerEmails field to given value.


### GetMemberCount

`func (o *Business) GetMemberCount() float32`

GetMemberCount returns the MemberCount field if non-nil, zero value otherwise.

### GetMemberCountOk

`func (o *Business) GetMemberCountOk() (*float32, bool)`

GetMemberCountOk returns a tuple with the MemberCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemberCount

`func (o *Business) SetMemberCount(v float32)`

SetMemberCount sets MemberCount field to given value.


### GetRoute

`func (o *Business) GetRoute() string`

GetRoute returns the Route field if non-nil, zero value otherwise.

### GetRouteOk

`func (o *Business) GetRouteOk() (*string, bool)`

GetRouteOk returns a tuple with the Route field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoute

`func (o *Business) SetRoute(v string)`

SetRoute sets Route field to given value.

### HasRoute

`func (o *Business) HasRoute() bool`

HasRoute returns a boolean if a field has been set.

### GetDefaultCurrency

`func (o *Business) GetDefaultCurrency() string`

GetDefaultCurrency returns the DefaultCurrency field if non-nil, zero value otherwise.

### GetDefaultCurrencyOk

`func (o *Business) GetDefaultCurrencyOk() (*string, bool)`

GetDefaultCurrencyOk returns a tuple with the DefaultCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCurrency

`func (o *Business) SetDefaultCurrency(v string)`

SetDefaultCurrency sets DefaultCurrency field to given value.


### GetPublishedReviewsCount

`func (o *Business) GetPublishedReviewsCount() float32`

GetPublishedReviewsCount returns the PublishedReviewsCount field if non-nil, zero value otherwise.

### GetPublishedReviewsCountOk

`func (o *Business) GetPublishedReviewsCountOk() (*float32, bool)`

GetPublishedReviewsCountOk returns a tuple with the PublishedReviewsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedReviewsCount

`func (o *Business) SetPublishedReviewsCount(v float32)`

SetPublishedReviewsCount sets PublishedReviewsCount field to given value.


### GetMetadata

`func (o *Business) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Business) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Business) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *Business) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetTargetAudience

`func (o *Business) GetTargetAudience() string`

GetTargetAudience returns the TargetAudience field if non-nil, zero value otherwise.

### GetTargetAudienceOk

`func (o *Business) GetTargetAudienceOk() (*string, bool)`

GetTargetAudienceOk returns a tuple with the TargetAudience field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetAudience

`func (o *Business) SetTargetAudience(v string)`

SetTargetAudience sets TargetAudience field to given value.

### HasTargetAudience

`func (o *Business) HasTargetAudience() bool`

HasTargetAudience returns a boolean if a field has been set.

### GetSocialLinks

`func (o *Business) GetSocialLinks() map[string]interface{}`

GetSocialLinks returns the SocialLinks field if non-nil, zero value otherwise.

### GetSocialLinksOk

`func (o *Business) GetSocialLinksOk() (*map[string]interface{}, bool)`

GetSocialLinksOk returns a tuple with the SocialLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSocialLinks

`func (o *Business) SetSocialLinks(v map[string]interface{})`

SetSocialLinks sets SocialLinks field to given value.

### HasSocialLinks

`func (o *Business) HasSocialLinks() bool`

HasSocialLinks returns a boolean if a field has been set.

### GetAffiliateInstructions

`func (o *Business) GetAffiliateInstructions() string`

GetAffiliateInstructions returns the AffiliateInstructions field if non-nil, zero value otherwise.

### GetAffiliateInstructionsOk

`func (o *Business) GetAffiliateInstructionsOk() (*string, bool)`

GetAffiliateInstructionsOk returns a tuple with the AffiliateInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAffiliateInstructions

`func (o *Business) SetAffiliateInstructions(v string)`

SetAffiliateInstructions sets AffiliateInstructions field to given value.

### HasAffiliateInstructions

`func (o *Business) HasAffiliateInstructions() bool`

HasAffiliateInstructions returns a boolean if a field has been set.

### GetWhopCreatedAt

`func (o *Business) GetWhopCreatedAt() time.Time`

GetWhopCreatedAt returns the WhopCreatedAt field if non-nil, zero value otherwise.

### GetWhopCreatedAtOk

`func (o *Business) GetWhopCreatedAtOk() (*time.Time, bool)`

GetWhopCreatedAtOk returns a tuple with the WhopCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhopCreatedAt

`func (o *Business) SetWhopCreatedAt(v time.Time)`

SetWhopCreatedAt sets WhopCreatedAt field to given value.

### HasWhopCreatedAt

`func (o *Business) HasWhopCreatedAt() bool`

HasWhopCreatedAt returns a boolean if a field has been set.

### GetWhopUpdatedAt

`func (o *Business) GetWhopUpdatedAt() time.Time`

GetWhopUpdatedAt returns the WhopUpdatedAt field if non-nil, zero value otherwise.

### GetWhopUpdatedAtOk

`func (o *Business) GetWhopUpdatedAtOk() (*time.Time, bool)`

GetWhopUpdatedAtOk returns a tuple with the WhopUpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhopUpdatedAt

`func (o *Business) SetWhopUpdatedAt(v time.Time)`

SetWhopUpdatedAt sets WhopUpdatedAt field to given value.

### HasWhopUpdatedAt

`func (o *Business) HasWhopUpdatedAt() bool`

HasWhopUpdatedAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Business) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Business) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Business) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Business) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Business) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Business) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetLogoUrl

`func (o *Business) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *Business) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *Business) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.

### HasLogoUrl

`func (o *Business) HasLogoUrl() bool`

HasLogoUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


