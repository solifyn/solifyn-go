# LicensesCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductId** | **string** | The unique product identifier (internal product ID or ID) for which the license key will be issued. | 
**CustomerId** | **string** | The unique customer identifier (internal customer ID or ID) who will own this license key. | 
**ActivationLimit** | Pointer to **int32** | The maximum number of concurrent device or server activations allowed for this license key. | [optional] 
**ExpiryHours** | Pointer to **int32** | Relative validity period of the license in hours starting from the time of creation. | [optional] 
**Key** | Pointer to **string** | Optional custom license key string. If not provided, a random uppercase cryptographic serial key (e.g., ABCD-EFGH) will be generated automatically. | [optional] 

## Methods

### NewLicensesCreateRequest

`func NewLicensesCreateRequest(productId string, customerId string, ) *LicensesCreateRequest`

NewLicensesCreateRequest instantiates a new LicensesCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicensesCreateRequestWithDefaults

`func NewLicensesCreateRequestWithDefaults() *LicensesCreateRequest`

NewLicensesCreateRequestWithDefaults instantiates a new LicensesCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductId

`func (o *LicensesCreateRequest) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *LicensesCreateRequest) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *LicensesCreateRequest) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetCustomerId

`func (o *LicensesCreateRequest) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *LicensesCreateRequest) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *LicensesCreateRequest) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.


### GetActivationLimit

`func (o *LicensesCreateRequest) GetActivationLimit() int32`

GetActivationLimit returns the ActivationLimit field if non-nil, zero value otherwise.

### GetActivationLimitOk

`func (o *LicensesCreateRequest) GetActivationLimitOk() (*int32, bool)`

GetActivationLimitOk returns a tuple with the ActivationLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationLimit

`func (o *LicensesCreateRequest) SetActivationLimit(v int32)`

SetActivationLimit sets ActivationLimit field to given value.

### HasActivationLimit

`func (o *LicensesCreateRequest) HasActivationLimit() bool`

HasActivationLimit returns a boolean if a field has been set.

### GetExpiryHours

`func (o *LicensesCreateRequest) GetExpiryHours() int32`

GetExpiryHours returns the ExpiryHours field if non-nil, zero value otherwise.

### GetExpiryHoursOk

`func (o *LicensesCreateRequest) GetExpiryHoursOk() (*int32, bool)`

GetExpiryHoursOk returns a tuple with the ExpiryHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryHours

`func (o *LicensesCreateRequest) SetExpiryHours(v int32)`

SetExpiryHours sets ExpiryHours field to given value.

### HasExpiryHours

`func (o *LicensesCreateRequest) HasExpiryHours() bool`

HasExpiryHours returns a boolean if a field has been set.

### GetKey

`func (o *LicensesCreateRequest) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *LicensesCreateRequest) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *LicensesCreateRequest) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *LicensesCreateRequest) HasKey() bool`

HasKey returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


