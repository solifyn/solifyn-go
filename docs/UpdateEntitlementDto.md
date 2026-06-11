# UpdateEntitlementDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | The user-friendly name of the entitlement | [optional] 
**Type** | Pointer to **string** | The type of access to grant | [optional] 
**GithubRepo** | Pointer to **string** | The GitHub repository (e.g., owner/repo) | [optional] 
**GithubPermission** | Pointer to **string** | The GitHub repository permission level | [optional] [default to "pull"]
**DiscordGuildId** | Pointer to **string** | The Discord Guild/Server ID | [optional] 
**DiscordRoleId** | Pointer to **string** | The Discord Role ID to assign | [optional] 
**FramerTemplateId** | Pointer to **string** | The associated Framer Template ID | [optional] 
**LicenseKey** | Pointer to **string** | The static License Key (if not dynamically generated) | [optional] 
**ActivationLimit** | Pointer to **float32** | The maximum activation limit for licenses | [optional] 
**ActivationMessage** | Pointer to **string** | A message shown to the user upon license activation | [optional] 
**ExpiryHours** | Pointer to **float32** | The number of hours until the entitlement expires | [optional] 
**DigitalLink** | Pointer to **string** | The digital download URL or redirect link | [optional] 
**Instructions** | Pointer to **string** | Custom setup instructions for the user | [optional] 

## Methods

### NewUpdateEntitlementDto

`func NewUpdateEntitlementDto() *UpdateEntitlementDto`

NewUpdateEntitlementDto instantiates a new UpdateEntitlementDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateEntitlementDtoWithDefaults

`func NewUpdateEntitlementDtoWithDefaults() *UpdateEntitlementDto`

NewUpdateEntitlementDtoWithDefaults instantiates a new UpdateEntitlementDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateEntitlementDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateEntitlementDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateEntitlementDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateEntitlementDto) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *UpdateEntitlementDto) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *UpdateEntitlementDto) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *UpdateEntitlementDto) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *UpdateEntitlementDto) HasType() bool`

HasType returns a boolean if a field has been set.

### GetGithubRepo

`func (o *UpdateEntitlementDto) GetGithubRepo() string`

GetGithubRepo returns the GithubRepo field if non-nil, zero value otherwise.

### GetGithubRepoOk

`func (o *UpdateEntitlementDto) GetGithubRepoOk() (*string, bool)`

GetGithubRepoOk returns a tuple with the GithubRepo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubRepo

`func (o *UpdateEntitlementDto) SetGithubRepo(v string)`

SetGithubRepo sets GithubRepo field to given value.

### HasGithubRepo

`func (o *UpdateEntitlementDto) HasGithubRepo() bool`

HasGithubRepo returns a boolean if a field has been set.

### GetGithubPermission

`func (o *UpdateEntitlementDto) GetGithubPermission() string`

GetGithubPermission returns the GithubPermission field if non-nil, zero value otherwise.

### GetGithubPermissionOk

`func (o *UpdateEntitlementDto) GetGithubPermissionOk() (*string, bool)`

GetGithubPermissionOk returns a tuple with the GithubPermission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubPermission

`func (o *UpdateEntitlementDto) SetGithubPermission(v string)`

SetGithubPermission sets GithubPermission field to given value.

### HasGithubPermission

`func (o *UpdateEntitlementDto) HasGithubPermission() bool`

HasGithubPermission returns a boolean if a field has been set.

### GetDiscordGuildId

`func (o *UpdateEntitlementDto) GetDiscordGuildId() string`

GetDiscordGuildId returns the DiscordGuildId field if non-nil, zero value otherwise.

### GetDiscordGuildIdOk

`func (o *UpdateEntitlementDto) GetDiscordGuildIdOk() (*string, bool)`

GetDiscordGuildIdOk returns a tuple with the DiscordGuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordGuildId

`func (o *UpdateEntitlementDto) SetDiscordGuildId(v string)`

SetDiscordGuildId sets DiscordGuildId field to given value.

### HasDiscordGuildId

`func (o *UpdateEntitlementDto) HasDiscordGuildId() bool`

HasDiscordGuildId returns a boolean if a field has been set.

### GetDiscordRoleId

`func (o *UpdateEntitlementDto) GetDiscordRoleId() string`

GetDiscordRoleId returns the DiscordRoleId field if non-nil, zero value otherwise.

### GetDiscordRoleIdOk

`func (o *UpdateEntitlementDto) GetDiscordRoleIdOk() (*string, bool)`

GetDiscordRoleIdOk returns a tuple with the DiscordRoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordRoleId

`func (o *UpdateEntitlementDto) SetDiscordRoleId(v string)`

SetDiscordRoleId sets DiscordRoleId field to given value.

### HasDiscordRoleId

`func (o *UpdateEntitlementDto) HasDiscordRoleId() bool`

HasDiscordRoleId returns a boolean if a field has been set.

### GetFramerTemplateId

`func (o *UpdateEntitlementDto) GetFramerTemplateId() string`

GetFramerTemplateId returns the FramerTemplateId field if non-nil, zero value otherwise.

### GetFramerTemplateIdOk

`func (o *UpdateEntitlementDto) GetFramerTemplateIdOk() (*string, bool)`

GetFramerTemplateIdOk returns a tuple with the FramerTemplateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFramerTemplateId

`func (o *UpdateEntitlementDto) SetFramerTemplateId(v string)`

SetFramerTemplateId sets FramerTemplateId field to given value.

### HasFramerTemplateId

`func (o *UpdateEntitlementDto) HasFramerTemplateId() bool`

HasFramerTemplateId returns a boolean if a field has been set.

### GetLicenseKey

`func (o *UpdateEntitlementDto) GetLicenseKey() string`

GetLicenseKey returns the LicenseKey field if non-nil, zero value otherwise.

### GetLicenseKeyOk

`func (o *UpdateEntitlementDto) GetLicenseKeyOk() (*string, bool)`

GetLicenseKeyOk returns a tuple with the LicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseKey

`func (o *UpdateEntitlementDto) SetLicenseKey(v string)`

SetLicenseKey sets LicenseKey field to given value.

### HasLicenseKey

`func (o *UpdateEntitlementDto) HasLicenseKey() bool`

HasLicenseKey returns a boolean if a field has been set.

### GetActivationLimit

`func (o *UpdateEntitlementDto) GetActivationLimit() float32`

GetActivationLimit returns the ActivationLimit field if non-nil, zero value otherwise.

### GetActivationLimitOk

`func (o *UpdateEntitlementDto) GetActivationLimitOk() (*float32, bool)`

GetActivationLimitOk returns a tuple with the ActivationLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationLimit

`func (o *UpdateEntitlementDto) SetActivationLimit(v float32)`

SetActivationLimit sets ActivationLimit field to given value.

### HasActivationLimit

`func (o *UpdateEntitlementDto) HasActivationLimit() bool`

HasActivationLimit returns a boolean if a field has been set.

### GetActivationMessage

`func (o *UpdateEntitlementDto) GetActivationMessage() string`

GetActivationMessage returns the ActivationMessage field if non-nil, zero value otherwise.

### GetActivationMessageOk

`func (o *UpdateEntitlementDto) GetActivationMessageOk() (*string, bool)`

GetActivationMessageOk returns a tuple with the ActivationMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationMessage

`func (o *UpdateEntitlementDto) SetActivationMessage(v string)`

SetActivationMessage sets ActivationMessage field to given value.

### HasActivationMessage

`func (o *UpdateEntitlementDto) HasActivationMessage() bool`

HasActivationMessage returns a boolean if a field has been set.

### GetExpiryHours

`func (o *UpdateEntitlementDto) GetExpiryHours() float32`

GetExpiryHours returns the ExpiryHours field if non-nil, zero value otherwise.

### GetExpiryHoursOk

`func (o *UpdateEntitlementDto) GetExpiryHoursOk() (*float32, bool)`

GetExpiryHoursOk returns a tuple with the ExpiryHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryHours

`func (o *UpdateEntitlementDto) SetExpiryHours(v float32)`

SetExpiryHours sets ExpiryHours field to given value.

### HasExpiryHours

`func (o *UpdateEntitlementDto) HasExpiryHours() bool`

HasExpiryHours returns a boolean if a field has been set.

### GetDigitalLink

`func (o *UpdateEntitlementDto) GetDigitalLink() string`

GetDigitalLink returns the DigitalLink field if non-nil, zero value otherwise.

### GetDigitalLinkOk

`func (o *UpdateEntitlementDto) GetDigitalLinkOk() (*string, bool)`

GetDigitalLinkOk returns a tuple with the DigitalLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDigitalLink

`func (o *UpdateEntitlementDto) SetDigitalLink(v string)`

SetDigitalLink sets DigitalLink field to given value.

### HasDigitalLink

`func (o *UpdateEntitlementDto) HasDigitalLink() bool`

HasDigitalLink returns a boolean if a field has been set.

### GetInstructions

`func (o *UpdateEntitlementDto) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *UpdateEntitlementDto) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *UpdateEntitlementDto) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.

### HasInstructions

`func (o *UpdateEntitlementDto) HasInstructions() bool`

HasInstructions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


