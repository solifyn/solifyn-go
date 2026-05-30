# UserThemeUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | Pointer to **map[string]interface{}** | JSON object specifying styling parameters (colors, fonts, borders) | [optional] 
**AvatarUrl** | Pointer to **string** | URL of the store avatar/logo | [optional] 
**BannerUrl** | Pointer to **string** | URL of the store banner header image | [optional] 

## Methods

### NewUserThemeUpdate

`func NewUserThemeUpdate() *UserThemeUpdate`

NewUserThemeUpdate instantiates a new UserThemeUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserThemeUpdateWithDefaults

`func NewUserThemeUpdateWithDefaults() *UserThemeUpdate`

NewUserThemeUpdateWithDefaults instantiates a new UserThemeUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *UserThemeUpdate) GetConfig() map[string]interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *UserThemeUpdate) GetConfigOk() (*map[string]interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *UserThemeUpdate) SetConfig(v map[string]interface{})`

SetConfig sets Config field to given value.

### HasConfig

`func (o *UserThemeUpdate) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### GetAvatarUrl

`func (o *UserThemeUpdate) GetAvatarUrl() string`

GetAvatarUrl returns the AvatarUrl field if non-nil, zero value otherwise.

### GetAvatarUrlOk

`func (o *UserThemeUpdate) GetAvatarUrlOk() (*string, bool)`

GetAvatarUrlOk returns a tuple with the AvatarUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarUrl

`func (o *UserThemeUpdate) SetAvatarUrl(v string)`

SetAvatarUrl sets AvatarUrl field to given value.

### HasAvatarUrl

`func (o *UserThemeUpdate) HasAvatarUrl() bool`

HasAvatarUrl returns a boolean if a field has been set.

### GetBannerUrl

`func (o *UserThemeUpdate) GetBannerUrl() string`

GetBannerUrl returns the BannerUrl field if non-nil, zero value otherwise.

### GetBannerUrlOk

`func (o *UserThemeUpdate) GetBannerUrlOk() (*string, bool)`

GetBannerUrlOk returns a tuple with the BannerUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBannerUrl

`func (o *UserThemeUpdate) SetBannerUrl(v string)`

SetBannerUrl sets BannerUrl field to given value.

### HasBannerUrl

`func (o *UserThemeUpdate) HasBannerUrl() bool`

HasBannerUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


