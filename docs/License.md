# License

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique prefix-based identifier of the license key. | 
**Key** | **string** | The cryptographically generated license key string delivered to the customer. | 
**Status** | **string** | Lifecycle status of the license. ACTIVE &#x3D; active. DISABLED &#x3D; suspended. REVOKED &#x3D; hard-revoked. | 
**BusinessId** | **string** | The unique identifier associated with the business this license belongs to. | 
**ProductId** | **NullableString** | The unique ID of the product this license key is associated with. | 
**PaymentId** | **NullableString** | The unique payment identifier that triggered the issuance of this license key. | 
**CustomerId** | **NullableString** | The unique customer identifier (ID) who received this license key. | 
**ActivationLimit** | **NullableFloat32** | Maximum number of simultaneous active device instances allowed for this license. Null means unlimited. | 
**ActivationMessage** | **NullableString** | Optional message displayed to the customer upon successful activation. | 
**InstancesCount** | **float32** | Running count of how many times this license key has been activated. | 
**ExpiryHours** | **NullableFloat32** | Relative expiry duration in hours from the time of issuance. | 
**ExpiresAt** | **NullableString** | Absolute expiration timestamp. The license becomes invalid after this point. | 
**Filters** | **map[string]interface{}** | Optional custom metadata filters associated with the license. | 
**Archived** | **bool** | Indicates if the license key is archived. | 
**CreatedAt** | **string** | Timestamp indicating exactly when the license key was issued. | 
**UpdatedAt** | **string** | Timestamp indicating when the license key was last modified. | 

## Methods

### NewLicense

`func NewLicense(id string, key string, status string, businessId string, productId NullableString, paymentId NullableString, customerId NullableString, activationLimit NullableFloat32, activationMessage NullableString, instancesCount float32, expiryHours NullableFloat32, expiresAt NullableString, filters map[string]interface{}, archived bool, createdAt string, updatedAt string, ) *License`

NewLicense instantiates a new License object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicenseWithDefaults

`func NewLicenseWithDefaults() *License`

NewLicenseWithDefaults instantiates a new License object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *License) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *License) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *License) SetId(v string)`

SetId sets Id field to given value.


### GetKey

`func (o *License) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *License) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *License) SetKey(v string)`

SetKey sets Key field to given value.


### GetStatus

`func (o *License) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *License) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *License) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetBusinessId

`func (o *License) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *License) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *License) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetProductId

`func (o *License) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *License) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *License) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### SetProductIdNil

`func (o *License) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *License) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetPaymentId

`func (o *License) GetPaymentId() string`

GetPaymentId returns the PaymentId field if non-nil, zero value otherwise.

### GetPaymentIdOk

`func (o *License) GetPaymentIdOk() (*string, bool)`

GetPaymentIdOk returns a tuple with the PaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentId

`func (o *License) SetPaymentId(v string)`

SetPaymentId sets PaymentId field to given value.


### SetPaymentIdNil

`func (o *License) SetPaymentIdNil(b bool)`

 SetPaymentIdNil sets the value for PaymentId to be an explicit nil

### UnsetPaymentId
`func (o *License) UnsetPaymentId()`

UnsetPaymentId ensures that no value is present for PaymentId, not even an explicit nil
### GetCustomerId

`func (o *License) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *License) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *License) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.


### SetCustomerIdNil

`func (o *License) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *License) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetActivationLimit

`func (o *License) GetActivationLimit() float32`

GetActivationLimit returns the ActivationLimit field if non-nil, zero value otherwise.

### GetActivationLimitOk

`func (o *License) GetActivationLimitOk() (*float32, bool)`

GetActivationLimitOk returns a tuple with the ActivationLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationLimit

`func (o *License) SetActivationLimit(v float32)`

SetActivationLimit sets ActivationLimit field to given value.


### SetActivationLimitNil

`func (o *License) SetActivationLimitNil(b bool)`

 SetActivationLimitNil sets the value for ActivationLimit to be an explicit nil

### UnsetActivationLimit
`func (o *License) UnsetActivationLimit()`

UnsetActivationLimit ensures that no value is present for ActivationLimit, not even an explicit nil
### GetActivationMessage

`func (o *License) GetActivationMessage() string`

GetActivationMessage returns the ActivationMessage field if non-nil, zero value otherwise.

### GetActivationMessageOk

`func (o *License) GetActivationMessageOk() (*string, bool)`

GetActivationMessageOk returns a tuple with the ActivationMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationMessage

`func (o *License) SetActivationMessage(v string)`

SetActivationMessage sets ActivationMessage field to given value.


### SetActivationMessageNil

`func (o *License) SetActivationMessageNil(b bool)`

 SetActivationMessageNil sets the value for ActivationMessage to be an explicit nil

### UnsetActivationMessage
`func (o *License) UnsetActivationMessage()`

UnsetActivationMessage ensures that no value is present for ActivationMessage, not even an explicit nil
### GetInstancesCount

`func (o *License) GetInstancesCount() float32`

GetInstancesCount returns the InstancesCount field if non-nil, zero value otherwise.

### GetInstancesCountOk

`func (o *License) GetInstancesCountOk() (*float32, bool)`

GetInstancesCountOk returns a tuple with the InstancesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstancesCount

`func (o *License) SetInstancesCount(v float32)`

SetInstancesCount sets InstancesCount field to given value.


### GetExpiryHours

`func (o *License) GetExpiryHours() float32`

GetExpiryHours returns the ExpiryHours field if non-nil, zero value otherwise.

### GetExpiryHoursOk

`func (o *License) GetExpiryHoursOk() (*float32, bool)`

GetExpiryHoursOk returns a tuple with the ExpiryHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryHours

`func (o *License) SetExpiryHours(v float32)`

SetExpiryHours sets ExpiryHours field to given value.


### SetExpiryHoursNil

`func (o *License) SetExpiryHoursNil(b bool)`

 SetExpiryHoursNil sets the value for ExpiryHours to be an explicit nil

### UnsetExpiryHours
`func (o *License) UnsetExpiryHours()`

UnsetExpiryHours ensures that no value is present for ExpiryHours, not even an explicit nil
### GetExpiresAt

`func (o *License) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *License) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *License) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.


### SetExpiresAtNil

`func (o *License) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *License) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetFilters

`func (o *License) GetFilters() map[string]interface{}`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *License) GetFiltersOk() (*map[string]interface{}, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *License) SetFilters(v map[string]interface{})`

SetFilters sets Filters field to given value.


### SetFiltersNil

`func (o *License) SetFiltersNil(b bool)`

 SetFiltersNil sets the value for Filters to be an explicit nil

### UnsetFilters
`func (o *License) UnsetFilters()`

UnsetFilters ensures that no value is present for Filters, not even an explicit nil
### GetArchived

`func (o *License) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *License) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *License) SetArchived(v bool)`

SetArchived sets Archived field to given value.


### GetCreatedAt

`func (o *License) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *License) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *License) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *License) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *License) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *License) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


