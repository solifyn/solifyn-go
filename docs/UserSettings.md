# UserSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | User ID | 
**Email** | **string** | Primary email address | 
**FirstName** | Pointer to **string** | First name | [optional] 
**LastName** | Pointer to **string** | Last name | [optional] 
**AvatarUrl** | Pointer to **string** | Profile avatar image URL | [optional] 
**PayoutThreshold** | **float32** | Auto-payout minimum threshold limit in cents | 
**NotifyOnSuccess** | **bool** | Auto-email receipt toggled | 
**SendLicenseKeyEmail** | **bool** | Send license keys email automatically | 
**SendDigitalFileEmail** | **bool** | Send digital delivery download link emails automatically | 

## Methods

### NewUserSettings

`func NewUserSettings(id string, email string, payoutThreshold float32, notifyOnSuccess bool, sendLicenseKeyEmail bool, sendDigitalFileEmail bool, ) *UserSettings`

NewUserSettings instantiates a new UserSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserSettingsWithDefaults

`func NewUserSettingsWithDefaults() *UserSettings`

NewUserSettingsWithDefaults instantiates a new UserSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *UserSettings) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UserSettings) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UserSettings) SetId(v string)`

SetId sets Id field to given value.


### GetEmail

`func (o *UserSettings) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserSettings) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserSettings) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetFirstName

`func (o *UserSettings) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *UserSettings) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *UserSettings) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *UserSettings) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *UserSettings) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *UserSettings) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *UserSettings) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *UserSettings) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetAvatarUrl

`func (o *UserSettings) GetAvatarUrl() string`

GetAvatarUrl returns the AvatarUrl field if non-nil, zero value otherwise.

### GetAvatarUrlOk

`func (o *UserSettings) GetAvatarUrlOk() (*string, bool)`

GetAvatarUrlOk returns a tuple with the AvatarUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarUrl

`func (o *UserSettings) SetAvatarUrl(v string)`

SetAvatarUrl sets AvatarUrl field to given value.

### HasAvatarUrl

`func (o *UserSettings) HasAvatarUrl() bool`

HasAvatarUrl returns a boolean if a field has been set.

### GetPayoutThreshold

`func (o *UserSettings) GetPayoutThreshold() float32`

GetPayoutThreshold returns the PayoutThreshold field if non-nil, zero value otherwise.

### GetPayoutThresholdOk

`func (o *UserSettings) GetPayoutThresholdOk() (*float32, bool)`

GetPayoutThresholdOk returns a tuple with the PayoutThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayoutThreshold

`func (o *UserSettings) SetPayoutThreshold(v float32)`

SetPayoutThreshold sets PayoutThreshold field to given value.


### GetNotifyOnSuccess

`func (o *UserSettings) GetNotifyOnSuccess() bool`

GetNotifyOnSuccess returns the NotifyOnSuccess field if non-nil, zero value otherwise.

### GetNotifyOnSuccessOk

`func (o *UserSettings) GetNotifyOnSuccessOk() (*bool, bool)`

GetNotifyOnSuccessOk returns a tuple with the NotifyOnSuccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyOnSuccess

`func (o *UserSettings) SetNotifyOnSuccess(v bool)`

SetNotifyOnSuccess sets NotifyOnSuccess field to given value.


### GetSendLicenseKeyEmail

`func (o *UserSettings) GetSendLicenseKeyEmail() bool`

GetSendLicenseKeyEmail returns the SendLicenseKeyEmail field if non-nil, zero value otherwise.

### GetSendLicenseKeyEmailOk

`func (o *UserSettings) GetSendLicenseKeyEmailOk() (*bool, bool)`

GetSendLicenseKeyEmailOk returns a tuple with the SendLicenseKeyEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendLicenseKeyEmail

`func (o *UserSettings) SetSendLicenseKeyEmail(v bool)`

SetSendLicenseKeyEmail sets SendLicenseKeyEmail field to given value.


### GetSendDigitalFileEmail

`func (o *UserSettings) GetSendDigitalFileEmail() bool`

GetSendDigitalFileEmail returns the SendDigitalFileEmail field if non-nil, zero value otherwise.

### GetSendDigitalFileEmailOk

`func (o *UserSettings) GetSendDigitalFileEmailOk() (*bool, bool)`

GetSendDigitalFileEmailOk returns a tuple with the SendDigitalFileEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendDigitalFileEmail

`func (o *UserSettings) SetSendDigitalFileEmail(v bool)`

SetSendDigitalFileEmail sets SendDigitalFileEmail field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


