# BusinessFullCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Indicates if creation was successful | 
**BusinessId** | **string** | The newly created business ID | 

## Methods

### NewBusinessFullCreateResponse

`func NewBusinessFullCreateResponse(success bool, businessId string, ) *BusinessFullCreateResponse`

NewBusinessFullCreateResponse instantiates a new BusinessFullCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBusinessFullCreateResponseWithDefaults

`func NewBusinessFullCreateResponseWithDefaults() *BusinessFullCreateResponse`

NewBusinessFullCreateResponseWithDefaults instantiates a new BusinessFullCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *BusinessFullCreateResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *BusinessFullCreateResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *BusinessFullCreateResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetBusinessId

`func (o *BusinessFullCreateResponse) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *BusinessFullCreateResponse) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *BusinessFullCreateResponse) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


