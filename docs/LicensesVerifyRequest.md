# LicensesVerifyRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** | The license key to validate. | 
**ProductId** | **string** | The product ID associated with the license. | 

## Methods

### NewLicensesVerifyRequest

`func NewLicensesVerifyRequest(key string, productId string, ) *LicensesVerifyRequest`

NewLicensesVerifyRequest instantiates a new LicensesVerifyRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicensesVerifyRequestWithDefaults

`func NewLicensesVerifyRequestWithDefaults() *LicensesVerifyRequest`

NewLicensesVerifyRequestWithDefaults instantiates a new LicensesVerifyRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *LicensesVerifyRequest) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *LicensesVerifyRequest) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *LicensesVerifyRequest) SetKey(v string)`

SetKey sets Key field to given value.


### GetProductId

`func (o *LicensesVerifyRequest) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *LicensesVerifyRequest) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *LicensesVerifyRequest) SetProductId(v string)`

SetProductId sets ProductId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


