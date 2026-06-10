# WebhookEntitlementGrantPayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The unique entitlement grant ID. | [optional] 
**BusinessId** | Pointer to **string** | The business ID context. | [optional] 
**CustomerId** | Pointer to **string** | The customer ID. | [optional] 
**PaymentId** | Pointer to **string** | Associated payment transaction ID. | [optional] 
**ProductId** | Pointer to **string** | The purchased product ID. | [optional] 
**Type** | Pointer to **string** | The type of entitlement (e.g. GITHUB). | [optional] 
**GithubRepo** | Pointer to **string** | Target GitHub repository (owner/repo) if type is GITHUB. | [optional] 
**GithubPermission** | Pointer to **string** | GitHub access permission level if type is GITHUB. | [optional] 
**GithubUsername** | Pointer to **string** | The connected customer GitHub username. | [optional] 
**Status** | Pointer to **string** | Delivery status of the collaborator invite (PENDING, DELIVERED, FAILED, REVOKED). | [optional] 
**OauthUrl** | Pointer to **string** | OAuth URL to redirect the customer to. | [optional] 
**ErrorDetails** | Pointer to **string** | Error message if invitation delivery failed. | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewWebhookEntitlementGrantPayload

`func NewWebhookEntitlementGrantPayload() *WebhookEntitlementGrantPayload`

NewWebhookEntitlementGrantPayload instantiates a new WebhookEntitlementGrantPayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookEntitlementGrantPayloadWithDefaults

`func NewWebhookEntitlementGrantPayloadWithDefaults() *WebhookEntitlementGrantPayload`

NewWebhookEntitlementGrantPayloadWithDefaults instantiates a new WebhookEntitlementGrantPayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WebhookEntitlementGrantPayload) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WebhookEntitlementGrantPayload) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WebhookEntitlementGrantPayload) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *WebhookEntitlementGrantPayload) HasId() bool`

HasId returns a boolean if a field has been set.

### GetBusinessId

`func (o *WebhookEntitlementGrantPayload) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *WebhookEntitlementGrantPayload) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *WebhookEntitlementGrantPayload) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.

### HasBusinessId

`func (o *WebhookEntitlementGrantPayload) HasBusinessId() bool`

HasBusinessId returns a boolean if a field has been set.

### GetCustomerId

`func (o *WebhookEntitlementGrantPayload) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *WebhookEntitlementGrantPayload) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *WebhookEntitlementGrantPayload) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *WebhookEntitlementGrantPayload) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetPaymentId

`func (o *WebhookEntitlementGrantPayload) GetPaymentId() string`

GetPaymentId returns the PaymentId field if non-nil, zero value otherwise.

### GetPaymentIdOk

`func (o *WebhookEntitlementGrantPayload) GetPaymentIdOk() (*string, bool)`

GetPaymentIdOk returns a tuple with the PaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentId

`func (o *WebhookEntitlementGrantPayload) SetPaymentId(v string)`

SetPaymentId sets PaymentId field to given value.

### HasPaymentId

`func (o *WebhookEntitlementGrantPayload) HasPaymentId() bool`

HasPaymentId returns a boolean if a field has been set.

### GetProductId

`func (o *WebhookEntitlementGrantPayload) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *WebhookEntitlementGrantPayload) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *WebhookEntitlementGrantPayload) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *WebhookEntitlementGrantPayload) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### GetType

`func (o *WebhookEntitlementGrantPayload) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *WebhookEntitlementGrantPayload) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *WebhookEntitlementGrantPayload) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *WebhookEntitlementGrantPayload) HasType() bool`

HasType returns a boolean if a field has been set.

### GetGithubRepo

`func (o *WebhookEntitlementGrantPayload) GetGithubRepo() string`

GetGithubRepo returns the GithubRepo field if non-nil, zero value otherwise.

### GetGithubRepoOk

`func (o *WebhookEntitlementGrantPayload) GetGithubRepoOk() (*string, bool)`

GetGithubRepoOk returns a tuple with the GithubRepo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubRepo

`func (o *WebhookEntitlementGrantPayload) SetGithubRepo(v string)`

SetGithubRepo sets GithubRepo field to given value.

### HasGithubRepo

`func (o *WebhookEntitlementGrantPayload) HasGithubRepo() bool`

HasGithubRepo returns a boolean if a field has been set.

### GetGithubPermission

`func (o *WebhookEntitlementGrantPayload) GetGithubPermission() string`

GetGithubPermission returns the GithubPermission field if non-nil, zero value otherwise.

### GetGithubPermissionOk

`func (o *WebhookEntitlementGrantPayload) GetGithubPermissionOk() (*string, bool)`

GetGithubPermissionOk returns a tuple with the GithubPermission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubPermission

`func (o *WebhookEntitlementGrantPayload) SetGithubPermission(v string)`

SetGithubPermission sets GithubPermission field to given value.

### HasGithubPermission

`func (o *WebhookEntitlementGrantPayload) HasGithubPermission() bool`

HasGithubPermission returns a boolean if a field has been set.

### GetGithubUsername

`func (o *WebhookEntitlementGrantPayload) GetGithubUsername() string`

GetGithubUsername returns the GithubUsername field if non-nil, zero value otherwise.

### GetGithubUsernameOk

`func (o *WebhookEntitlementGrantPayload) GetGithubUsernameOk() (*string, bool)`

GetGithubUsernameOk returns a tuple with the GithubUsername field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubUsername

`func (o *WebhookEntitlementGrantPayload) SetGithubUsername(v string)`

SetGithubUsername sets GithubUsername field to given value.

### HasGithubUsername

`func (o *WebhookEntitlementGrantPayload) HasGithubUsername() bool`

HasGithubUsername returns a boolean if a field has been set.

### GetStatus

`func (o *WebhookEntitlementGrantPayload) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WebhookEntitlementGrantPayload) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WebhookEntitlementGrantPayload) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *WebhookEntitlementGrantPayload) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetOauthUrl

`func (o *WebhookEntitlementGrantPayload) GetOauthUrl() string`

GetOauthUrl returns the OauthUrl field if non-nil, zero value otherwise.

### GetOauthUrlOk

`func (o *WebhookEntitlementGrantPayload) GetOauthUrlOk() (*string, bool)`

GetOauthUrlOk returns a tuple with the OauthUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauthUrl

`func (o *WebhookEntitlementGrantPayload) SetOauthUrl(v string)`

SetOauthUrl sets OauthUrl field to given value.

### HasOauthUrl

`func (o *WebhookEntitlementGrantPayload) HasOauthUrl() bool`

HasOauthUrl returns a boolean if a field has been set.

### GetErrorDetails

`func (o *WebhookEntitlementGrantPayload) GetErrorDetails() string`

GetErrorDetails returns the ErrorDetails field if non-nil, zero value otherwise.

### GetErrorDetailsOk

`func (o *WebhookEntitlementGrantPayload) GetErrorDetailsOk() (*string, bool)`

GetErrorDetailsOk returns a tuple with the ErrorDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDetails

`func (o *WebhookEntitlementGrantPayload) SetErrorDetails(v string)`

SetErrorDetails sets ErrorDetails field to given value.

### HasErrorDetails

`func (o *WebhookEntitlementGrantPayload) HasErrorDetails() bool`

HasErrorDetails returns a boolean if a field has been set.

### GetCreatedAt

`func (o *WebhookEntitlementGrantPayload) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WebhookEntitlementGrantPayload) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WebhookEntitlementGrantPayload) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *WebhookEntitlementGrantPayload) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *WebhookEntitlementGrantPayload) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *WebhookEntitlementGrantPayload) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *WebhookEntitlementGrantPayload) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *WebhookEntitlementGrantPayload) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


