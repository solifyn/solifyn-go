# UserSettingsUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Subdomain** | Pointer to **string** | The custom store subdomain | [optional] 
**StoreName** | Pointer to **string** | The store name shown to customers | [optional] 
**SocialLinks** | Pointer to **map[string]interface{}** | JSON structure listing social/contact URLs | [optional] 
**PageTitle** | Pointer to **string** | SEO title tag of the store page | [optional] 
**SeoDescription** | Pointer to **string** | SEO description meta tag | [optional] 
**SeoImage** | Pointer to **string** | SEO preview image URL | [optional] 
**FaviconUrl** | Pointer to **string** | Favicon image URL | [optional] 
**GoogleAnalyticsId** | Pointer to **string** | Google Analytics 4 Property ID | [optional] 
**GoogleTagManagerId** | Pointer to **string** | Google Tag Manager Container ID | [optional] 
**MetaPixelId** | Pointer to **string** | Facebook Meta Pixel ID | [optional] 
**LogoUrl** | Pointer to **string** | Company/Store logo image URL | [optional] 
**BusinessTitle** | Pointer to **string** | Name of the business entity | [optional] 
**StatementDescriptor** | Pointer to **string** | Credit card statement descriptor | [optional] 
**DefaultCurrency** | Pointer to **string** | Three-letter currency symbol | [optional] 
**Email** | Pointer to **string** | User contact email | [optional] 
**FirstName** | Pointer to **string** | User first name | [optional] 
**LastName** | Pointer to **string** | User last name | [optional] 
**AvatarUrl** | Pointer to **string** | User profile avatar URL | [optional] 
**PayoutThreshold** | Pointer to **float32** | Minimum balance required for automatic payouts in cents | [optional] 
**NotifyOnSuccess** | Pointer to **bool** | Send email notifications on successful payments | [optional] 
**SendLicenseKeyEmail** | Pointer to **bool** | Send license keys automatically via email | [optional] 
**SendDigitalFileEmail** | Pointer to **bool** | Send download links automatically via email | [optional] 
**NotifyOnSubscriptionPlanChanged** | Pointer to **bool** | Send email notifications on subscription plan changes | [optional] 
**NotifyOnSubscriptionSetToCancel** | Pointer to **bool** | Send email notifications when subscription is set to cancel | [optional] 
**NotifyOnSubscriptionCancelled** | Pointer to **bool** | Send email notifications when subscription is cancelled | [optional] 
**NotifyOnRefundSuccessful** | Pointer to **bool** | Send email notifications when refund is successful | [optional] 
**NotifyOnPaymentFailed** | Pointer to **bool** | Send email notifications when payment fails | [optional] 
**NotifyOnSubscriptionRenewalFailed** | Pointer to **bool** | Send email notifications when subscription renewal fails | [optional] 
**NotifyOnSubscriptionTrialEnding** | Pointer to **bool** | Send email notifications when subscription trial is ending | [optional] 
**NotifyOnSubscriptionPaused** | Pointer to **bool** | Send email notifications when subscription is paused | [optional] 

## Methods

### NewUserSettingsUpdate

`func NewUserSettingsUpdate() *UserSettingsUpdate`

NewUserSettingsUpdate instantiates a new UserSettingsUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserSettingsUpdateWithDefaults

`func NewUserSettingsUpdateWithDefaults() *UserSettingsUpdate`

NewUserSettingsUpdateWithDefaults instantiates a new UserSettingsUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSubdomain

`func (o *UserSettingsUpdate) GetSubdomain() string`

GetSubdomain returns the Subdomain field if non-nil, zero value otherwise.

### GetSubdomainOk

`func (o *UserSettingsUpdate) GetSubdomainOk() (*string, bool)`

GetSubdomainOk returns a tuple with the Subdomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubdomain

`func (o *UserSettingsUpdate) SetSubdomain(v string)`

SetSubdomain sets Subdomain field to given value.

### HasSubdomain

`func (o *UserSettingsUpdate) HasSubdomain() bool`

HasSubdomain returns a boolean if a field has been set.

### GetStoreName

`func (o *UserSettingsUpdate) GetStoreName() string`

GetStoreName returns the StoreName field if non-nil, zero value otherwise.

### GetStoreNameOk

`func (o *UserSettingsUpdate) GetStoreNameOk() (*string, bool)`

GetStoreNameOk returns a tuple with the StoreName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreName

`func (o *UserSettingsUpdate) SetStoreName(v string)`

SetStoreName sets StoreName field to given value.

### HasStoreName

`func (o *UserSettingsUpdate) HasStoreName() bool`

HasStoreName returns a boolean if a field has been set.

### GetSocialLinks

`func (o *UserSettingsUpdate) GetSocialLinks() map[string]interface{}`

GetSocialLinks returns the SocialLinks field if non-nil, zero value otherwise.

### GetSocialLinksOk

`func (o *UserSettingsUpdate) GetSocialLinksOk() (*map[string]interface{}, bool)`

GetSocialLinksOk returns a tuple with the SocialLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSocialLinks

`func (o *UserSettingsUpdate) SetSocialLinks(v map[string]interface{})`

SetSocialLinks sets SocialLinks field to given value.

### HasSocialLinks

`func (o *UserSettingsUpdate) HasSocialLinks() bool`

HasSocialLinks returns a boolean if a field has been set.

### GetPageTitle

`func (o *UserSettingsUpdate) GetPageTitle() string`

GetPageTitle returns the PageTitle field if non-nil, zero value otherwise.

### GetPageTitleOk

`func (o *UserSettingsUpdate) GetPageTitleOk() (*string, bool)`

GetPageTitleOk returns a tuple with the PageTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageTitle

`func (o *UserSettingsUpdate) SetPageTitle(v string)`

SetPageTitle sets PageTitle field to given value.

### HasPageTitle

`func (o *UserSettingsUpdate) HasPageTitle() bool`

HasPageTitle returns a boolean if a field has been set.

### GetSeoDescription

`func (o *UserSettingsUpdate) GetSeoDescription() string`

GetSeoDescription returns the SeoDescription field if non-nil, zero value otherwise.

### GetSeoDescriptionOk

`func (o *UserSettingsUpdate) GetSeoDescriptionOk() (*string, bool)`

GetSeoDescriptionOk returns a tuple with the SeoDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeoDescription

`func (o *UserSettingsUpdate) SetSeoDescription(v string)`

SetSeoDescription sets SeoDescription field to given value.

### HasSeoDescription

`func (o *UserSettingsUpdate) HasSeoDescription() bool`

HasSeoDescription returns a boolean if a field has been set.

### GetSeoImage

`func (o *UserSettingsUpdate) GetSeoImage() string`

GetSeoImage returns the SeoImage field if non-nil, zero value otherwise.

### GetSeoImageOk

`func (o *UserSettingsUpdate) GetSeoImageOk() (*string, bool)`

GetSeoImageOk returns a tuple with the SeoImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeoImage

`func (o *UserSettingsUpdate) SetSeoImage(v string)`

SetSeoImage sets SeoImage field to given value.

### HasSeoImage

`func (o *UserSettingsUpdate) HasSeoImage() bool`

HasSeoImage returns a boolean if a field has been set.

### GetFaviconUrl

`func (o *UserSettingsUpdate) GetFaviconUrl() string`

GetFaviconUrl returns the FaviconUrl field if non-nil, zero value otherwise.

### GetFaviconUrlOk

`func (o *UserSettingsUpdate) GetFaviconUrlOk() (*string, bool)`

GetFaviconUrlOk returns a tuple with the FaviconUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFaviconUrl

`func (o *UserSettingsUpdate) SetFaviconUrl(v string)`

SetFaviconUrl sets FaviconUrl field to given value.

### HasFaviconUrl

`func (o *UserSettingsUpdate) HasFaviconUrl() bool`

HasFaviconUrl returns a boolean if a field has been set.

### GetGoogleAnalyticsId

`func (o *UserSettingsUpdate) GetGoogleAnalyticsId() string`

GetGoogleAnalyticsId returns the GoogleAnalyticsId field if non-nil, zero value otherwise.

### GetGoogleAnalyticsIdOk

`func (o *UserSettingsUpdate) GetGoogleAnalyticsIdOk() (*string, bool)`

GetGoogleAnalyticsIdOk returns a tuple with the GoogleAnalyticsId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoogleAnalyticsId

`func (o *UserSettingsUpdate) SetGoogleAnalyticsId(v string)`

SetGoogleAnalyticsId sets GoogleAnalyticsId field to given value.

### HasGoogleAnalyticsId

`func (o *UserSettingsUpdate) HasGoogleAnalyticsId() bool`

HasGoogleAnalyticsId returns a boolean if a field has been set.

### GetGoogleTagManagerId

`func (o *UserSettingsUpdate) GetGoogleTagManagerId() string`

GetGoogleTagManagerId returns the GoogleTagManagerId field if non-nil, zero value otherwise.

### GetGoogleTagManagerIdOk

`func (o *UserSettingsUpdate) GetGoogleTagManagerIdOk() (*string, bool)`

GetGoogleTagManagerIdOk returns a tuple with the GoogleTagManagerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoogleTagManagerId

`func (o *UserSettingsUpdate) SetGoogleTagManagerId(v string)`

SetGoogleTagManagerId sets GoogleTagManagerId field to given value.

### HasGoogleTagManagerId

`func (o *UserSettingsUpdate) HasGoogleTagManagerId() bool`

HasGoogleTagManagerId returns a boolean if a field has been set.

### GetMetaPixelId

`func (o *UserSettingsUpdate) GetMetaPixelId() string`

GetMetaPixelId returns the MetaPixelId field if non-nil, zero value otherwise.

### GetMetaPixelIdOk

`func (o *UserSettingsUpdate) GetMetaPixelIdOk() (*string, bool)`

GetMetaPixelIdOk returns a tuple with the MetaPixelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetaPixelId

`func (o *UserSettingsUpdate) SetMetaPixelId(v string)`

SetMetaPixelId sets MetaPixelId field to given value.

### HasMetaPixelId

`func (o *UserSettingsUpdate) HasMetaPixelId() bool`

HasMetaPixelId returns a boolean if a field has been set.

### GetLogoUrl

`func (o *UserSettingsUpdate) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *UserSettingsUpdate) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *UserSettingsUpdate) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.

### HasLogoUrl

`func (o *UserSettingsUpdate) HasLogoUrl() bool`

HasLogoUrl returns a boolean if a field has been set.

### GetBusinessTitle

`func (o *UserSettingsUpdate) GetBusinessTitle() string`

GetBusinessTitle returns the BusinessTitle field if non-nil, zero value otherwise.

### GetBusinessTitleOk

`func (o *UserSettingsUpdate) GetBusinessTitleOk() (*string, bool)`

GetBusinessTitleOk returns a tuple with the BusinessTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessTitle

`func (o *UserSettingsUpdate) SetBusinessTitle(v string)`

SetBusinessTitle sets BusinessTitle field to given value.

### HasBusinessTitle

`func (o *UserSettingsUpdate) HasBusinessTitle() bool`

HasBusinessTitle returns a boolean if a field has been set.

### GetStatementDescriptor

`func (o *UserSettingsUpdate) GetStatementDescriptor() string`

GetStatementDescriptor returns the StatementDescriptor field if non-nil, zero value otherwise.

### GetStatementDescriptorOk

`func (o *UserSettingsUpdate) GetStatementDescriptorOk() (*string, bool)`

GetStatementDescriptorOk returns a tuple with the StatementDescriptor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatementDescriptor

`func (o *UserSettingsUpdate) SetStatementDescriptor(v string)`

SetStatementDescriptor sets StatementDescriptor field to given value.

### HasStatementDescriptor

`func (o *UserSettingsUpdate) HasStatementDescriptor() bool`

HasStatementDescriptor returns a boolean if a field has been set.

### GetDefaultCurrency

`func (o *UserSettingsUpdate) GetDefaultCurrency() string`

GetDefaultCurrency returns the DefaultCurrency field if non-nil, zero value otherwise.

### GetDefaultCurrencyOk

`func (o *UserSettingsUpdate) GetDefaultCurrencyOk() (*string, bool)`

GetDefaultCurrencyOk returns a tuple with the DefaultCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCurrency

`func (o *UserSettingsUpdate) SetDefaultCurrency(v string)`

SetDefaultCurrency sets DefaultCurrency field to given value.

### HasDefaultCurrency

`func (o *UserSettingsUpdate) HasDefaultCurrency() bool`

HasDefaultCurrency returns a boolean if a field has been set.

### GetEmail

`func (o *UserSettingsUpdate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserSettingsUpdate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserSettingsUpdate) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *UserSettingsUpdate) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetFirstName

`func (o *UserSettingsUpdate) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *UserSettingsUpdate) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *UserSettingsUpdate) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *UserSettingsUpdate) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *UserSettingsUpdate) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *UserSettingsUpdate) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *UserSettingsUpdate) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *UserSettingsUpdate) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetAvatarUrl

`func (o *UserSettingsUpdate) GetAvatarUrl() string`

GetAvatarUrl returns the AvatarUrl field if non-nil, zero value otherwise.

### GetAvatarUrlOk

`func (o *UserSettingsUpdate) GetAvatarUrlOk() (*string, bool)`

GetAvatarUrlOk returns a tuple with the AvatarUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarUrl

`func (o *UserSettingsUpdate) SetAvatarUrl(v string)`

SetAvatarUrl sets AvatarUrl field to given value.

### HasAvatarUrl

`func (o *UserSettingsUpdate) HasAvatarUrl() bool`

HasAvatarUrl returns a boolean if a field has been set.

### GetPayoutThreshold

`func (o *UserSettingsUpdate) GetPayoutThreshold() float32`

GetPayoutThreshold returns the PayoutThreshold field if non-nil, zero value otherwise.

### GetPayoutThresholdOk

`func (o *UserSettingsUpdate) GetPayoutThresholdOk() (*float32, bool)`

GetPayoutThresholdOk returns a tuple with the PayoutThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayoutThreshold

`func (o *UserSettingsUpdate) SetPayoutThreshold(v float32)`

SetPayoutThreshold sets PayoutThreshold field to given value.

### HasPayoutThreshold

`func (o *UserSettingsUpdate) HasPayoutThreshold() bool`

HasPayoutThreshold returns a boolean if a field has been set.

### GetNotifyOnSuccess

`func (o *UserSettingsUpdate) GetNotifyOnSuccess() bool`

GetNotifyOnSuccess returns the NotifyOnSuccess field if non-nil, zero value otherwise.

### GetNotifyOnSuccessOk

`func (o *UserSettingsUpdate) GetNotifyOnSuccessOk() (*bool, bool)`

GetNotifyOnSuccessOk returns a tuple with the NotifyOnSuccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyOnSuccess

`func (o *UserSettingsUpdate) SetNotifyOnSuccess(v bool)`

SetNotifyOnSuccess sets NotifyOnSuccess field to given value.

### HasNotifyOnSuccess

`func (o *UserSettingsUpdate) HasNotifyOnSuccess() bool`

HasNotifyOnSuccess returns a boolean if a field has been set.

### GetSendLicenseKeyEmail

`func (o *UserSettingsUpdate) GetSendLicenseKeyEmail() bool`

GetSendLicenseKeyEmail returns the SendLicenseKeyEmail field if non-nil, zero value otherwise.

### GetSendLicenseKeyEmailOk

`func (o *UserSettingsUpdate) GetSendLicenseKeyEmailOk() (*bool, bool)`

GetSendLicenseKeyEmailOk returns a tuple with the SendLicenseKeyEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendLicenseKeyEmail

`func (o *UserSettingsUpdate) SetSendLicenseKeyEmail(v bool)`

SetSendLicenseKeyEmail sets SendLicenseKeyEmail field to given value.

### HasSendLicenseKeyEmail

`func (o *UserSettingsUpdate) HasSendLicenseKeyEmail() bool`

HasSendLicenseKeyEmail returns a boolean if a field has been set.

### GetSendDigitalFileEmail

`func (o *UserSettingsUpdate) GetSendDigitalFileEmail() bool`

GetSendDigitalFileEmail returns the SendDigitalFileEmail field if non-nil, zero value otherwise.

### GetSendDigitalFileEmailOk

`func (o *UserSettingsUpdate) GetSendDigitalFileEmailOk() (*bool, bool)`

GetSendDigitalFileEmailOk returns a tuple with the SendDigitalFileEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendDigitalFileEmail

`func (o *UserSettingsUpdate) SetSendDigitalFileEmail(v bool)`

SetSendDigitalFileEmail sets SendDigitalFileEmail field to given value.

### HasSendDigitalFileEmail

`func (o *UserSettingsUpdate) HasSendDigitalFileEmail() bool`

HasSendDigitalFileEmail returns a boolean if a field has been set.

### GetNotifyOnSubscriptionPlanChanged

`func (o *UserSettingsUpdate) GetNotifyOnSubscriptionPlanChanged() bool`

GetNotifyOnSubscriptionPlanChanged returns the NotifyOnSubscriptionPlanChanged field if non-nil, zero value otherwise.

### GetNotifyOnSubscriptionPlanChangedOk

`func (o *UserSettingsUpdate) GetNotifyOnSubscriptionPlanChangedOk() (*bool, bool)`

GetNotifyOnSubscriptionPlanChangedOk returns a tuple with the NotifyOnSubscriptionPlanChanged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyOnSubscriptionPlanChanged

`func (o *UserSettingsUpdate) SetNotifyOnSubscriptionPlanChanged(v bool)`

SetNotifyOnSubscriptionPlanChanged sets NotifyOnSubscriptionPlanChanged field to given value.

### HasNotifyOnSubscriptionPlanChanged

`func (o *UserSettingsUpdate) HasNotifyOnSubscriptionPlanChanged() bool`

HasNotifyOnSubscriptionPlanChanged returns a boolean if a field has been set.

### GetNotifyOnSubscriptionSetToCancel

`func (o *UserSettingsUpdate) GetNotifyOnSubscriptionSetToCancel() bool`

GetNotifyOnSubscriptionSetToCancel returns the NotifyOnSubscriptionSetToCancel field if non-nil, zero value otherwise.

### GetNotifyOnSubscriptionSetToCancelOk

`func (o *UserSettingsUpdate) GetNotifyOnSubscriptionSetToCancelOk() (*bool, bool)`

GetNotifyOnSubscriptionSetToCancelOk returns a tuple with the NotifyOnSubscriptionSetToCancel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyOnSubscriptionSetToCancel

`func (o *UserSettingsUpdate) SetNotifyOnSubscriptionSetToCancel(v bool)`

SetNotifyOnSubscriptionSetToCancel sets NotifyOnSubscriptionSetToCancel field to given value.

### HasNotifyOnSubscriptionSetToCancel

`func (o *UserSettingsUpdate) HasNotifyOnSubscriptionSetToCancel() bool`

HasNotifyOnSubscriptionSetToCancel returns a boolean if a field has been set.

### GetNotifyOnSubscriptionCancelled

`func (o *UserSettingsUpdate) GetNotifyOnSubscriptionCancelled() bool`

GetNotifyOnSubscriptionCancelled returns the NotifyOnSubscriptionCancelled field if non-nil, zero value otherwise.

### GetNotifyOnSubscriptionCancelledOk

`func (o *UserSettingsUpdate) GetNotifyOnSubscriptionCancelledOk() (*bool, bool)`

GetNotifyOnSubscriptionCancelledOk returns a tuple with the NotifyOnSubscriptionCancelled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyOnSubscriptionCancelled

`func (o *UserSettingsUpdate) SetNotifyOnSubscriptionCancelled(v bool)`

SetNotifyOnSubscriptionCancelled sets NotifyOnSubscriptionCancelled field to given value.

### HasNotifyOnSubscriptionCancelled

`func (o *UserSettingsUpdate) HasNotifyOnSubscriptionCancelled() bool`

HasNotifyOnSubscriptionCancelled returns a boolean if a field has been set.

### GetNotifyOnRefundSuccessful

`func (o *UserSettingsUpdate) GetNotifyOnRefundSuccessful() bool`

GetNotifyOnRefundSuccessful returns the NotifyOnRefundSuccessful field if non-nil, zero value otherwise.

### GetNotifyOnRefundSuccessfulOk

`func (o *UserSettingsUpdate) GetNotifyOnRefundSuccessfulOk() (*bool, bool)`

GetNotifyOnRefundSuccessfulOk returns a tuple with the NotifyOnRefundSuccessful field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyOnRefundSuccessful

`func (o *UserSettingsUpdate) SetNotifyOnRefundSuccessful(v bool)`

SetNotifyOnRefundSuccessful sets NotifyOnRefundSuccessful field to given value.

### HasNotifyOnRefundSuccessful

`func (o *UserSettingsUpdate) HasNotifyOnRefundSuccessful() bool`

HasNotifyOnRefundSuccessful returns a boolean if a field has been set.

### GetNotifyOnPaymentFailed

`func (o *UserSettingsUpdate) GetNotifyOnPaymentFailed() bool`

GetNotifyOnPaymentFailed returns the NotifyOnPaymentFailed field if non-nil, zero value otherwise.

### GetNotifyOnPaymentFailedOk

`func (o *UserSettingsUpdate) GetNotifyOnPaymentFailedOk() (*bool, bool)`

GetNotifyOnPaymentFailedOk returns a tuple with the NotifyOnPaymentFailed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyOnPaymentFailed

`func (o *UserSettingsUpdate) SetNotifyOnPaymentFailed(v bool)`

SetNotifyOnPaymentFailed sets NotifyOnPaymentFailed field to given value.

### HasNotifyOnPaymentFailed

`func (o *UserSettingsUpdate) HasNotifyOnPaymentFailed() bool`

HasNotifyOnPaymentFailed returns a boolean if a field has been set.

### GetNotifyOnSubscriptionRenewalFailed

`func (o *UserSettingsUpdate) GetNotifyOnSubscriptionRenewalFailed() bool`

GetNotifyOnSubscriptionRenewalFailed returns the NotifyOnSubscriptionRenewalFailed field if non-nil, zero value otherwise.

### GetNotifyOnSubscriptionRenewalFailedOk

`func (o *UserSettingsUpdate) GetNotifyOnSubscriptionRenewalFailedOk() (*bool, bool)`

GetNotifyOnSubscriptionRenewalFailedOk returns a tuple with the NotifyOnSubscriptionRenewalFailed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyOnSubscriptionRenewalFailed

`func (o *UserSettingsUpdate) SetNotifyOnSubscriptionRenewalFailed(v bool)`

SetNotifyOnSubscriptionRenewalFailed sets NotifyOnSubscriptionRenewalFailed field to given value.

### HasNotifyOnSubscriptionRenewalFailed

`func (o *UserSettingsUpdate) HasNotifyOnSubscriptionRenewalFailed() bool`

HasNotifyOnSubscriptionRenewalFailed returns a boolean if a field has been set.

### GetNotifyOnSubscriptionTrialEnding

`func (o *UserSettingsUpdate) GetNotifyOnSubscriptionTrialEnding() bool`

GetNotifyOnSubscriptionTrialEnding returns the NotifyOnSubscriptionTrialEnding field if non-nil, zero value otherwise.

### GetNotifyOnSubscriptionTrialEndingOk

`func (o *UserSettingsUpdate) GetNotifyOnSubscriptionTrialEndingOk() (*bool, bool)`

GetNotifyOnSubscriptionTrialEndingOk returns a tuple with the NotifyOnSubscriptionTrialEnding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyOnSubscriptionTrialEnding

`func (o *UserSettingsUpdate) SetNotifyOnSubscriptionTrialEnding(v bool)`

SetNotifyOnSubscriptionTrialEnding sets NotifyOnSubscriptionTrialEnding field to given value.

### HasNotifyOnSubscriptionTrialEnding

`func (o *UserSettingsUpdate) HasNotifyOnSubscriptionTrialEnding() bool`

HasNotifyOnSubscriptionTrialEnding returns a boolean if a field has been set.

### GetNotifyOnSubscriptionPaused

`func (o *UserSettingsUpdate) GetNotifyOnSubscriptionPaused() bool`

GetNotifyOnSubscriptionPaused returns the NotifyOnSubscriptionPaused field if non-nil, zero value otherwise.

### GetNotifyOnSubscriptionPausedOk

`func (o *UserSettingsUpdate) GetNotifyOnSubscriptionPausedOk() (*bool, bool)`

GetNotifyOnSubscriptionPausedOk returns a tuple with the NotifyOnSubscriptionPaused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyOnSubscriptionPaused

`func (o *UserSettingsUpdate) SetNotifyOnSubscriptionPaused(v bool)`

SetNotifyOnSubscriptionPaused sets NotifyOnSubscriptionPaused field to given value.

### HasNotifyOnSubscriptionPaused

`func (o *UserSettingsUpdate) HasNotifyOnSubscriptionPaused() bool`

HasNotifyOnSubscriptionPaused returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


