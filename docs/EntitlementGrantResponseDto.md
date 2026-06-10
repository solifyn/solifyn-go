# EntitlementGrantResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique entitlement grant ID. | 
**BusinessId** | **string** | The business ID context. | 
**CustomerId** | **string** | The customer ID. | 
**PaymentId** | Pointer to **string** | Associated payment transaction ID. | [optional] 
**ProductId** | **string** | The purchased product ID. | 
**Type** | **string** | The type of entitlement (e.g. GITHUB, DISCORD, TELEGRAM). | 
**GithubRepo** | Pointer to **string** | Target GitHub repository (owner/repo) if type is GITHUB. | [optional] 
**GithubPermission** | Pointer to **string** | GitHub access permission level if type is GITHUB. | [optional] 
**GithubUsername** | Pointer to **string** | The connected customer GitHub username. | [optional] 
**DiscordGuildId** | Pointer to **string** | Target Discord Guild ID if type is DISCORD. | [optional] 
**DiscordRoleId** | Pointer to **string** | Target Discord Role ID if type is DISCORD. | [optional] 
**DiscordUsername** | Pointer to **string** | The connected customer Discord username. | [optional] 
**DiscordUserId** | Pointer to **string** | The connected customer Discord user ID. | [optional] 
**Status** | **string** | Delivery status of the collaborator invite (PENDING, DELIVERED, FAILED, REVOKED). | 
**OauthUrl** | Pointer to **string** | OAuth URL to redirect the customer to. | [optional] 
**ErrorDetails** | Pointer to **string** | Error message if invitation delivery failed. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Platform-specific metadata. | [optional] 
**CreatedAt** | **string** | Creation timestamp. | 
**UpdatedAt** | **string** | Modification timestamp. | 

## Methods

### NewEntitlementGrantResponseDto

`func NewEntitlementGrantResponseDto(id string, businessId string, customerId string, productId string, type_ string, status string, createdAt string, updatedAt string, ) *EntitlementGrantResponseDto`

NewEntitlementGrantResponseDto instantiates a new EntitlementGrantResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntitlementGrantResponseDtoWithDefaults

`func NewEntitlementGrantResponseDtoWithDefaults() *EntitlementGrantResponseDto`

NewEntitlementGrantResponseDtoWithDefaults instantiates a new EntitlementGrantResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EntitlementGrantResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EntitlementGrantResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EntitlementGrantResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetBusinessId

`func (o *EntitlementGrantResponseDto) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *EntitlementGrantResponseDto) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *EntitlementGrantResponseDto) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetCustomerId

`func (o *EntitlementGrantResponseDto) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *EntitlementGrantResponseDto) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *EntitlementGrantResponseDto) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.


### GetPaymentId

`func (o *EntitlementGrantResponseDto) GetPaymentId() string`

GetPaymentId returns the PaymentId field if non-nil, zero value otherwise.

### GetPaymentIdOk

`func (o *EntitlementGrantResponseDto) GetPaymentIdOk() (*string, bool)`

GetPaymentIdOk returns a tuple with the PaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentId

`func (o *EntitlementGrantResponseDto) SetPaymentId(v string)`

SetPaymentId sets PaymentId field to given value.

### HasPaymentId

`func (o *EntitlementGrantResponseDto) HasPaymentId() bool`

HasPaymentId returns a boolean if a field has been set.

### GetProductId

`func (o *EntitlementGrantResponseDto) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *EntitlementGrantResponseDto) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *EntitlementGrantResponseDto) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetType

`func (o *EntitlementGrantResponseDto) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *EntitlementGrantResponseDto) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *EntitlementGrantResponseDto) SetType(v string)`

SetType sets Type field to given value.


### GetGithubRepo

`func (o *EntitlementGrantResponseDto) GetGithubRepo() string`

GetGithubRepo returns the GithubRepo field if non-nil, zero value otherwise.

### GetGithubRepoOk

`func (o *EntitlementGrantResponseDto) GetGithubRepoOk() (*string, bool)`

GetGithubRepoOk returns a tuple with the GithubRepo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubRepo

`func (o *EntitlementGrantResponseDto) SetGithubRepo(v string)`

SetGithubRepo sets GithubRepo field to given value.

### HasGithubRepo

`func (o *EntitlementGrantResponseDto) HasGithubRepo() bool`

HasGithubRepo returns a boolean if a field has been set.

### GetGithubPermission

`func (o *EntitlementGrantResponseDto) GetGithubPermission() string`

GetGithubPermission returns the GithubPermission field if non-nil, zero value otherwise.

### GetGithubPermissionOk

`func (o *EntitlementGrantResponseDto) GetGithubPermissionOk() (*string, bool)`

GetGithubPermissionOk returns a tuple with the GithubPermission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubPermission

`func (o *EntitlementGrantResponseDto) SetGithubPermission(v string)`

SetGithubPermission sets GithubPermission field to given value.

### HasGithubPermission

`func (o *EntitlementGrantResponseDto) HasGithubPermission() bool`

HasGithubPermission returns a boolean if a field has been set.

### GetGithubUsername

`func (o *EntitlementGrantResponseDto) GetGithubUsername() string`

GetGithubUsername returns the GithubUsername field if non-nil, zero value otherwise.

### GetGithubUsernameOk

`func (o *EntitlementGrantResponseDto) GetGithubUsernameOk() (*string, bool)`

GetGithubUsernameOk returns a tuple with the GithubUsername field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubUsername

`func (o *EntitlementGrantResponseDto) SetGithubUsername(v string)`

SetGithubUsername sets GithubUsername field to given value.

### HasGithubUsername

`func (o *EntitlementGrantResponseDto) HasGithubUsername() bool`

HasGithubUsername returns a boolean if a field has been set.

### GetDiscordGuildId

`func (o *EntitlementGrantResponseDto) GetDiscordGuildId() string`

GetDiscordGuildId returns the DiscordGuildId field if non-nil, zero value otherwise.

### GetDiscordGuildIdOk

`func (o *EntitlementGrantResponseDto) GetDiscordGuildIdOk() (*string, bool)`

GetDiscordGuildIdOk returns a tuple with the DiscordGuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordGuildId

`func (o *EntitlementGrantResponseDto) SetDiscordGuildId(v string)`

SetDiscordGuildId sets DiscordGuildId field to given value.

### HasDiscordGuildId

`func (o *EntitlementGrantResponseDto) HasDiscordGuildId() bool`

HasDiscordGuildId returns a boolean if a field has been set.

### GetDiscordRoleId

`func (o *EntitlementGrantResponseDto) GetDiscordRoleId() string`

GetDiscordRoleId returns the DiscordRoleId field if non-nil, zero value otherwise.

### GetDiscordRoleIdOk

`func (o *EntitlementGrantResponseDto) GetDiscordRoleIdOk() (*string, bool)`

GetDiscordRoleIdOk returns a tuple with the DiscordRoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordRoleId

`func (o *EntitlementGrantResponseDto) SetDiscordRoleId(v string)`

SetDiscordRoleId sets DiscordRoleId field to given value.

### HasDiscordRoleId

`func (o *EntitlementGrantResponseDto) HasDiscordRoleId() bool`

HasDiscordRoleId returns a boolean if a field has been set.

### GetDiscordUsername

`func (o *EntitlementGrantResponseDto) GetDiscordUsername() string`

GetDiscordUsername returns the DiscordUsername field if non-nil, zero value otherwise.

### GetDiscordUsernameOk

`func (o *EntitlementGrantResponseDto) GetDiscordUsernameOk() (*string, bool)`

GetDiscordUsernameOk returns a tuple with the DiscordUsername field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordUsername

`func (o *EntitlementGrantResponseDto) SetDiscordUsername(v string)`

SetDiscordUsername sets DiscordUsername field to given value.

### HasDiscordUsername

`func (o *EntitlementGrantResponseDto) HasDiscordUsername() bool`

HasDiscordUsername returns a boolean if a field has been set.

### GetDiscordUserId

`func (o *EntitlementGrantResponseDto) GetDiscordUserId() string`

GetDiscordUserId returns the DiscordUserId field if non-nil, zero value otherwise.

### GetDiscordUserIdOk

`func (o *EntitlementGrantResponseDto) GetDiscordUserIdOk() (*string, bool)`

GetDiscordUserIdOk returns a tuple with the DiscordUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordUserId

`func (o *EntitlementGrantResponseDto) SetDiscordUserId(v string)`

SetDiscordUserId sets DiscordUserId field to given value.

### HasDiscordUserId

`func (o *EntitlementGrantResponseDto) HasDiscordUserId() bool`

HasDiscordUserId returns a boolean if a field has been set.

### GetStatus

`func (o *EntitlementGrantResponseDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EntitlementGrantResponseDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EntitlementGrantResponseDto) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetOauthUrl

`func (o *EntitlementGrantResponseDto) GetOauthUrl() string`

GetOauthUrl returns the OauthUrl field if non-nil, zero value otherwise.

### GetOauthUrlOk

`func (o *EntitlementGrantResponseDto) GetOauthUrlOk() (*string, bool)`

GetOauthUrlOk returns a tuple with the OauthUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauthUrl

`func (o *EntitlementGrantResponseDto) SetOauthUrl(v string)`

SetOauthUrl sets OauthUrl field to given value.

### HasOauthUrl

`func (o *EntitlementGrantResponseDto) HasOauthUrl() bool`

HasOauthUrl returns a boolean if a field has been set.

### GetErrorDetails

`func (o *EntitlementGrantResponseDto) GetErrorDetails() string`

GetErrorDetails returns the ErrorDetails field if non-nil, zero value otherwise.

### GetErrorDetailsOk

`func (o *EntitlementGrantResponseDto) GetErrorDetailsOk() (*string, bool)`

GetErrorDetailsOk returns a tuple with the ErrorDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDetails

`func (o *EntitlementGrantResponseDto) SetErrorDetails(v string)`

SetErrorDetails sets ErrorDetails field to given value.

### HasErrorDetails

`func (o *EntitlementGrantResponseDto) HasErrorDetails() bool`

HasErrorDetails returns a boolean if a field has been set.

### GetMetadata

`func (o *EntitlementGrantResponseDto) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *EntitlementGrantResponseDto) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *EntitlementGrantResponseDto) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *EntitlementGrantResponseDto) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetCreatedAt

`func (o *EntitlementGrantResponseDto) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *EntitlementGrantResponseDto) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *EntitlementGrantResponseDto) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *EntitlementGrantResponseDto) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *EntitlementGrantResponseDto) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *EntitlementGrantResponseDto) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


