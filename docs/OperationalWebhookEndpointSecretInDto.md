# OperationalWebhookEndpointSecretInDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | Pointer to **string** | Optional custom endpoint signing secret (base64 encoded random bytes optionally prefixed with whsec_). If not set, a new random secret is generated. | [optional] 

## Methods

### NewOperationalWebhookEndpointSecretInDto

`func NewOperationalWebhookEndpointSecretInDto() *OperationalWebhookEndpointSecretInDto`

NewOperationalWebhookEndpointSecretInDto instantiates a new OperationalWebhookEndpointSecretInDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationalWebhookEndpointSecretInDtoWithDefaults

`func NewOperationalWebhookEndpointSecretInDtoWithDefaults() *OperationalWebhookEndpointSecretInDto`

NewOperationalWebhookEndpointSecretInDtoWithDefaults instantiates a new OperationalWebhookEndpointSecretInDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *OperationalWebhookEndpointSecretInDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *OperationalWebhookEndpointSecretInDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *OperationalWebhookEndpointSecretInDto) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *OperationalWebhookEndpointSecretInDto) HasKey() bool`

HasKey returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


