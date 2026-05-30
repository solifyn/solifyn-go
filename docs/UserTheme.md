# UserTheme

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Theme configuration ID | 
**Config** | **map[string]interface{}** | Styling config JSON (fontFamily, borderRadius, colors) | 
**AvatarUrl** | Pointer to **string** | Logo/avatar image URL | [optional] 
**BannerUrl** | Pointer to **string** | Header banner image URL | [optional] 
**BusinessId** | **string** | The linked business ID | 

## Methods

### NewUserTheme

`func NewUserTheme(id string, config map[string]interface{}, businessId string, ) *UserTheme`

NewUserTheme instantiates a new UserTheme object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserThemeWithDefaults

`func NewUserThemeWithDefaults() *UserTheme`

NewUserThemeWithDefaults instantiates a new UserTheme object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *UserTheme) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UserTheme) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UserTheme) SetId(v string)`

SetId sets Id field to given value.


### GetConfig

`func (o *UserTheme) GetConfig() map[string]interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *UserTheme) GetConfigOk() (*map[string]interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *UserTheme) SetConfig(v map[string]interface{})`

SetConfig sets Config field to given value.


### GetAvatarUrl

`func (o *UserTheme) GetAvatarUrl() string`

GetAvatarUrl returns the AvatarUrl field if non-nil, zero value otherwise.

### GetAvatarUrlOk

`func (o *UserTheme) GetAvatarUrlOk() (*string, bool)`

GetAvatarUrlOk returns a tuple with the AvatarUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarUrl

`func (o *UserTheme) SetAvatarUrl(v string)`

SetAvatarUrl sets AvatarUrl field to given value.

### HasAvatarUrl

`func (o *UserTheme) HasAvatarUrl() bool`

HasAvatarUrl returns a boolean if a field has been set.

### GetBannerUrl

`func (o *UserTheme) GetBannerUrl() string`

GetBannerUrl returns the BannerUrl field if non-nil, zero value otherwise.

### GetBannerUrlOk

`func (o *UserTheme) GetBannerUrlOk() (*string, bool)`

GetBannerUrlOk returns a tuple with the BannerUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBannerUrl

`func (o *UserTheme) SetBannerUrl(v string)`

SetBannerUrl sets BannerUrl field to given value.

### HasBannerUrl

`func (o *UserTheme) HasBannerUrl() bool`

HasBannerUrl returns a boolean if a field has been set.

### GetBusinessId

`func (o *UserTheme) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *UserTheme) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *UserTheme) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


