# CustomerSharedInviteResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Token** | **string** | The generated invite token | 
**ExpiresAt** | **time.Time** | The expiration timestamp of the token | 
**Url** | Pointer to **string** | The self-service shared portal URL | [optional] 

## Methods

### NewCustomerSharedInviteResponseDto

`func NewCustomerSharedInviteResponseDto(token string, expiresAt time.Time, ) *CustomerSharedInviteResponseDto`

NewCustomerSharedInviteResponseDto instantiates a new CustomerSharedInviteResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerSharedInviteResponseDtoWithDefaults

`func NewCustomerSharedInviteResponseDtoWithDefaults() *CustomerSharedInviteResponseDto`

NewCustomerSharedInviteResponseDtoWithDefaults instantiates a new CustomerSharedInviteResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetToken

`func (o *CustomerSharedInviteResponseDto) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *CustomerSharedInviteResponseDto) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *CustomerSharedInviteResponseDto) SetToken(v string)`

SetToken sets Token field to given value.


### GetExpiresAt

`func (o *CustomerSharedInviteResponseDto) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CustomerSharedInviteResponseDto) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CustomerSharedInviteResponseDto) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetUrl

`func (o *CustomerSharedInviteResponseDto) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CustomerSharedInviteResponseDto) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CustomerSharedInviteResponseDto) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CustomerSharedInviteResponseDto) HasUrl() bool`

HasUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


