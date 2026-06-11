# EntitlementDetailResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique entitlement ID | 
**BusinessId** | **string** | The owning business ID | 
**Name** | **string** | The name of the entitlement | 
**Type** | **string** | The type of access to grant | 
**Status** | **string** | Status of the entitlement | 
**CreatedAt** | **time.Time** | When the entitlement was created | 
**UpdatedAt** | **time.Time** | When the entitlement was last updated | 
**GithubRepo** | Pointer to **string** | The GitHub repository (e.g., owner/repo) | [optional] 
**GithubPermission** | Pointer to **string** | The GitHub repository permission level | [optional] 
**DiscordGuildId** | Pointer to **string** | The Discord Guild/Server ID | [optional] 
**DiscordRoleId** | Pointer to **string** | The Discord Role ID to assign | [optional] 
**FramerTemplateId** | Pointer to **string** | The associated Framer Template ID | [optional] 
**LicenseKey** | Pointer to **string** | The static License Key (if not dynamically generated) | [optional] 
**ActivationLimit** | Pointer to **float32** | The maximum activation limit for licenses | [optional] 
**ActivationMessage** | Pointer to **string** | A message shown to the user upon license activation | [optional] 
**ExpiryHours** | Pointer to **float32** | The number of hours until the entitlement expires | [optional] 
**DigitalLink** | Pointer to **string** | The digital download URL or redirect link | [optional] 
**Instructions** | Pointer to **string** | Custom setup instructions for the user | [optional] 
**GrantsCount** | **float32** | Number of active customer grants issued from this entitlement | 
**Products** | [**[]LinkedProductDto**](LinkedProductDto.md) | Products that are currently linked to this entitlement | 

## Methods

### NewEntitlementDetailResponseDto

`func NewEntitlementDetailResponseDto(id string, businessId string, name string, type_ string, status string, createdAt time.Time, updatedAt time.Time, grantsCount float32, products []LinkedProductDto, ) *EntitlementDetailResponseDto`

NewEntitlementDetailResponseDto instantiates a new EntitlementDetailResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntitlementDetailResponseDtoWithDefaults

`func NewEntitlementDetailResponseDtoWithDefaults() *EntitlementDetailResponseDto`

NewEntitlementDetailResponseDtoWithDefaults instantiates a new EntitlementDetailResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EntitlementDetailResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EntitlementDetailResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EntitlementDetailResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetBusinessId

`func (o *EntitlementDetailResponseDto) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *EntitlementDetailResponseDto) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *EntitlementDetailResponseDto) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetName

`func (o *EntitlementDetailResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *EntitlementDetailResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *EntitlementDetailResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetType

`func (o *EntitlementDetailResponseDto) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *EntitlementDetailResponseDto) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *EntitlementDetailResponseDto) SetType(v string)`

SetType sets Type field to given value.


### GetStatus

`func (o *EntitlementDetailResponseDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EntitlementDetailResponseDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EntitlementDetailResponseDto) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *EntitlementDetailResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *EntitlementDetailResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *EntitlementDetailResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *EntitlementDetailResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *EntitlementDetailResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *EntitlementDetailResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetGithubRepo

`func (o *EntitlementDetailResponseDto) GetGithubRepo() string`

GetGithubRepo returns the GithubRepo field if non-nil, zero value otherwise.

### GetGithubRepoOk

`func (o *EntitlementDetailResponseDto) GetGithubRepoOk() (*string, bool)`

GetGithubRepoOk returns a tuple with the GithubRepo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubRepo

`func (o *EntitlementDetailResponseDto) SetGithubRepo(v string)`

SetGithubRepo sets GithubRepo field to given value.

### HasGithubRepo

`func (o *EntitlementDetailResponseDto) HasGithubRepo() bool`

HasGithubRepo returns a boolean if a field has been set.

### GetGithubPermission

`func (o *EntitlementDetailResponseDto) GetGithubPermission() string`

GetGithubPermission returns the GithubPermission field if non-nil, zero value otherwise.

### GetGithubPermissionOk

`func (o *EntitlementDetailResponseDto) GetGithubPermissionOk() (*string, bool)`

GetGithubPermissionOk returns a tuple with the GithubPermission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubPermission

`func (o *EntitlementDetailResponseDto) SetGithubPermission(v string)`

SetGithubPermission sets GithubPermission field to given value.

### HasGithubPermission

`func (o *EntitlementDetailResponseDto) HasGithubPermission() bool`

HasGithubPermission returns a boolean if a field has been set.

### GetDiscordGuildId

`func (o *EntitlementDetailResponseDto) GetDiscordGuildId() string`

GetDiscordGuildId returns the DiscordGuildId field if non-nil, zero value otherwise.

### GetDiscordGuildIdOk

`func (o *EntitlementDetailResponseDto) GetDiscordGuildIdOk() (*string, bool)`

GetDiscordGuildIdOk returns a tuple with the DiscordGuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordGuildId

`func (o *EntitlementDetailResponseDto) SetDiscordGuildId(v string)`

SetDiscordGuildId sets DiscordGuildId field to given value.

### HasDiscordGuildId

`func (o *EntitlementDetailResponseDto) HasDiscordGuildId() bool`

HasDiscordGuildId returns a boolean if a field has been set.

### GetDiscordRoleId

`func (o *EntitlementDetailResponseDto) GetDiscordRoleId() string`

GetDiscordRoleId returns the DiscordRoleId field if non-nil, zero value otherwise.

### GetDiscordRoleIdOk

`func (o *EntitlementDetailResponseDto) GetDiscordRoleIdOk() (*string, bool)`

GetDiscordRoleIdOk returns a tuple with the DiscordRoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordRoleId

`func (o *EntitlementDetailResponseDto) SetDiscordRoleId(v string)`

SetDiscordRoleId sets DiscordRoleId field to given value.

### HasDiscordRoleId

`func (o *EntitlementDetailResponseDto) HasDiscordRoleId() bool`

HasDiscordRoleId returns a boolean if a field has been set.

### GetFramerTemplateId

`func (o *EntitlementDetailResponseDto) GetFramerTemplateId() string`

GetFramerTemplateId returns the FramerTemplateId field if non-nil, zero value otherwise.

### GetFramerTemplateIdOk

`func (o *EntitlementDetailResponseDto) GetFramerTemplateIdOk() (*string, bool)`

GetFramerTemplateIdOk returns a tuple with the FramerTemplateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFramerTemplateId

`func (o *EntitlementDetailResponseDto) SetFramerTemplateId(v string)`

SetFramerTemplateId sets FramerTemplateId field to given value.

### HasFramerTemplateId

`func (o *EntitlementDetailResponseDto) HasFramerTemplateId() bool`

HasFramerTemplateId returns a boolean if a field has been set.

### GetLicenseKey

`func (o *EntitlementDetailResponseDto) GetLicenseKey() string`

GetLicenseKey returns the LicenseKey field if non-nil, zero value otherwise.

### GetLicenseKeyOk

`func (o *EntitlementDetailResponseDto) GetLicenseKeyOk() (*string, bool)`

GetLicenseKeyOk returns a tuple with the LicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseKey

`func (o *EntitlementDetailResponseDto) SetLicenseKey(v string)`

SetLicenseKey sets LicenseKey field to given value.

### HasLicenseKey

`func (o *EntitlementDetailResponseDto) HasLicenseKey() bool`

HasLicenseKey returns a boolean if a field has been set.

### GetActivationLimit

`func (o *EntitlementDetailResponseDto) GetActivationLimit() float32`

GetActivationLimit returns the ActivationLimit field if non-nil, zero value otherwise.

### GetActivationLimitOk

`func (o *EntitlementDetailResponseDto) GetActivationLimitOk() (*float32, bool)`

GetActivationLimitOk returns a tuple with the ActivationLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationLimit

`func (o *EntitlementDetailResponseDto) SetActivationLimit(v float32)`

SetActivationLimit sets ActivationLimit field to given value.

### HasActivationLimit

`func (o *EntitlementDetailResponseDto) HasActivationLimit() bool`

HasActivationLimit returns a boolean if a field has been set.

### GetActivationMessage

`func (o *EntitlementDetailResponseDto) GetActivationMessage() string`

GetActivationMessage returns the ActivationMessage field if non-nil, zero value otherwise.

### GetActivationMessageOk

`func (o *EntitlementDetailResponseDto) GetActivationMessageOk() (*string, bool)`

GetActivationMessageOk returns a tuple with the ActivationMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationMessage

`func (o *EntitlementDetailResponseDto) SetActivationMessage(v string)`

SetActivationMessage sets ActivationMessage field to given value.

### HasActivationMessage

`func (o *EntitlementDetailResponseDto) HasActivationMessage() bool`

HasActivationMessage returns a boolean if a field has been set.

### GetExpiryHours

`func (o *EntitlementDetailResponseDto) GetExpiryHours() float32`

GetExpiryHours returns the ExpiryHours field if non-nil, zero value otherwise.

### GetExpiryHoursOk

`func (o *EntitlementDetailResponseDto) GetExpiryHoursOk() (*float32, bool)`

GetExpiryHoursOk returns a tuple with the ExpiryHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryHours

`func (o *EntitlementDetailResponseDto) SetExpiryHours(v float32)`

SetExpiryHours sets ExpiryHours field to given value.

### HasExpiryHours

`func (o *EntitlementDetailResponseDto) HasExpiryHours() bool`

HasExpiryHours returns a boolean if a field has been set.

### GetDigitalLink

`func (o *EntitlementDetailResponseDto) GetDigitalLink() string`

GetDigitalLink returns the DigitalLink field if non-nil, zero value otherwise.

### GetDigitalLinkOk

`func (o *EntitlementDetailResponseDto) GetDigitalLinkOk() (*string, bool)`

GetDigitalLinkOk returns a tuple with the DigitalLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDigitalLink

`func (o *EntitlementDetailResponseDto) SetDigitalLink(v string)`

SetDigitalLink sets DigitalLink field to given value.

### HasDigitalLink

`func (o *EntitlementDetailResponseDto) HasDigitalLink() bool`

HasDigitalLink returns a boolean if a field has been set.

### GetInstructions

`func (o *EntitlementDetailResponseDto) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *EntitlementDetailResponseDto) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *EntitlementDetailResponseDto) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.

### HasInstructions

`func (o *EntitlementDetailResponseDto) HasInstructions() bool`

HasInstructions returns a boolean if a field has been set.

### GetGrantsCount

`func (o *EntitlementDetailResponseDto) GetGrantsCount() float32`

GetGrantsCount returns the GrantsCount field if non-nil, zero value otherwise.

### GetGrantsCountOk

`func (o *EntitlementDetailResponseDto) GetGrantsCountOk() (*float32, bool)`

GetGrantsCountOk returns a tuple with the GrantsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrantsCount

`func (o *EntitlementDetailResponseDto) SetGrantsCount(v float32)`

SetGrantsCount sets GrantsCount field to given value.


### GetProducts

`func (o *EntitlementDetailResponseDto) GetProducts() []LinkedProductDto`

GetProducts returns the Products field if non-nil, zero value otherwise.

### GetProductsOk

`func (o *EntitlementDetailResponseDto) GetProductsOk() (*[]LinkedProductDto, bool)`

GetProductsOk returns a tuple with the Products field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducts

`func (o *EntitlementDetailResponseDto) SetProducts(v []LinkedProductDto)`

SetProducts sets Products field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


