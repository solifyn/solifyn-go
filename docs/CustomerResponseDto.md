# CustomerResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The customer ID | 
**MemberId** | Pointer to **string** | The Membership ID associated with this customer | [optional] 
**Email** | **string** | The email address of the customer | 
**Name** | Pointer to **string** | The name of the customer | [optional] 
**Username** | Pointer to **string** | The username of the customer | [optional] 
**Phone** | Pointer to **string** | The phone number of the customer | [optional] 
**PhoneNumber** | Pointer to **string** | The phone number of the customer | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Additional metadata associated with the customer | [optional] 
**CreatedAt** | **time.Time** | Timestamp when the customer was created | 
**UpdatedAt** | **time.Time** | Timestamp when the customer was last updated | 
**BusinessId** | **string** | The business ID associated with the customer | 

## Methods

### NewCustomerResponseDto

`func NewCustomerResponseDto(id string, email string, createdAt time.Time, updatedAt time.Time, businessId string, ) *CustomerResponseDto`

NewCustomerResponseDto instantiates a new CustomerResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerResponseDtoWithDefaults

`func NewCustomerResponseDtoWithDefaults() *CustomerResponseDto`

NewCustomerResponseDtoWithDefaults instantiates a new CustomerResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomerResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomerResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomerResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetMemberId

`func (o *CustomerResponseDto) GetMemberId() string`

GetMemberId returns the MemberId field if non-nil, zero value otherwise.

### GetMemberIdOk

`func (o *CustomerResponseDto) GetMemberIdOk() (*string, bool)`

GetMemberIdOk returns a tuple with the MemberId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemberId

`func (o *CustomerResponseDto) SetMemberId(v string)`

SetMemberId sets MemberId field to given value.

### HasMemberId

`func (o *CustomerResponseDto) HasMemberId() bool`

HasMemberId returns a boolean if a field has been set.

### GetEmail

`func (o *CustomerResponseDto) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CustomerResponseDto) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CustomerResponseDto) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetName

`func (o *CustomerResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomerResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomerResponseDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CustomerResponseDto) HasName() bool`

HasName returns a boolean if a field has been set.

### GetUsername

`func (o *CustomerResponseDto) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *CustomerResponseDto) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *CustomerResponseDto) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *CustomerResponseDto) HasUsername() bool`

HasUsername returns a boolean if a field has been set.

### GetPhone

`func (o *CustomerResponseDto) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *CustomerResponseDto) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *CustomerResponseDto) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *CustomerResponseDto) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetPhoneNumber

`func (o *CustomerResponseDto) GetPhoneNumber() string`

GetPhoneNumber returns the PhoneNumber field if non-nil, zero value otherwise.

### GetPhoneNumberOk

`func (o *CustomerResponseDto) GetPhoneNumberOk() (*string, bool)`

GetPhoneNumberOk returns a tuple with the PhoneNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhoneNumber

`func (o *CustomerResponseDto) SetPhoneNumber(v string)`

SetPhoneNumber sets PhoneNumber field to given value.

### HasPhoneNumber

`func (o *CustomerResponseDto) HasPhoneNumber() bool`

HasPhoneNumber returns a boolean if a field has been set.

### GetMetadata

`func (o *CustomerResponseDto) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CustomerResponseDto) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CustomerResponseDto) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *CustomerResponseDto) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetCreatedAt

`func (o *CustomerResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CustomerResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CustomerResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *CustomerResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CustomerResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CustomerResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetBusinessId

`func (o *CustomerResponseDto) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *CustomerResponseDto) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *CustomerResponseDto) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


