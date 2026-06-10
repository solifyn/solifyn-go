# LicenseValidationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Valid** | **bool** |  | 
**License** | [**LicenseSubDto**](LicenseSubDto.md) |  | 

## Methods

### NewLicenseValidationResponse

`func NewLicenseValidationResponse(success bool, valid bool, license LicenseSubDto, ) *LicenseValidationResponse`

NewLicenseValidationResponse instantiates a new LicenseValidationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicenseValidationResponseWithDefaults

`func NewLicenseValidationResponseWithDefaults() *LicenseValidationResponse`

NewLicenseValidationResponseWithDefaults instantiates a new LicenseValidationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *LicenseValidationResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *LicenseValidationResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *LicenseValidationResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetValid

`func (o *LicenseValidationResponse) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *LicenseValidationResponse) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *LicenseValidationResponse) SetValid(v bool)`

SetValid sets Valid field to given value.


### GetLicense

`func (o *LicenseValidationResponse) GetLicense() LicenseSubDto`

GetLicense returns the License field if non-nil, zero value otherwise.

### GetLicenseOk

`func (o *LicenseValidationResponse) GetLicenseOk() (*LicenseSubDto, bool)`

GetLicenseOk returns a tuple with the License field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicense

`func (o *LicenseValidationResponse) SetLicense(v LicenseSubDto)`

SetLicense sets License field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


