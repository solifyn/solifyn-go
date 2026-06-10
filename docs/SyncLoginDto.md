# SyncLoginDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LiveToken** | **string** | The JWT access token from the Live API server | 

## Methods

### NewSyncLoginDto

`func NewSyncLoginDto(liveToken string, ) *SyncLoginDto`

NewSyncLoginDto instantiates a new SyncLoginDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncLoginDtoWithDefaults

`func NewSyncLoginDtoWithDefaults() *SyncLoginDto`

NewSyncLoginDtoWithDefaults instantiates a new SyncLoginDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLiveToken

`func (o *SyncLoginDto) GetLiveToken() string`

GetLiveToken returns the LiveToken field if non-nil, zero value otherwise.

### GetLiveTokenOk

`func (o *SyncLoginDto) GetLiveTokenOk() (*string, bool)`

GetLiveTokenOk returns a tuple with the LiveToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiveToken

`func (o *SyncLoginDto) SetLiveToken(v string)`

SetLiveToken sets LiveToken field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


