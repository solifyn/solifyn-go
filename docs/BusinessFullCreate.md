# BusinessFullCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | **string** | The title/name of the business | 
**WebsiteUrl** | Pointer to **string** | The primary website URL for the business | [optional] 
**Country** | **string** | Country name of the business registration | 
**Category** | Pointer to **string** | The business market category (e.g. software, media) | [optional] 
**ReferredByCode** | Pointer to **string** | Optional partner referral code used during signup | [optional] 

## Methods

### NewBusinessFullCreate

`func NewBusinessFullCreate(title string, country string, ) *BusinessFullCreate`

NewBusinessFullCreate instantiates a new BusinessFullCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBusinessFullCreateWithDefaults

`func NewBusinessFullCreateWithDefaults() *BusinessFullCreate`

NewBusinessFullCreateWithDefaults instantiates a new BusinessFullCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *BusinessFullCreate) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *BusinessFullCreate) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *BusinessFullCreate) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetWebsiteUrl

`func (o *BusinessFullCreate) GetWebsiteUrl() string`

GetWebsiteUrl returns the WebsiteUrl field if non-nil, zero value otherwise.

### GetWebsiteUrlOk

`func (o *BusinessFullCreate) GetWebsiteUrlOk() (*string, bool)`

GetWebsiteUrlOk returns a tuple with the WebsiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsiteUrl

`func (o *BusinessFullCreate) SetWebsiteUrl(v string)`

SetWebsiteUrl sets WebsiteUrl field to given value.

### HasWebsiteUrl

`func (o *BusinessFullCreate) HasWebsiteUrl() bool`

HasWebsiteUrl returns a boolean if a field has been set.

### GetCountry

`func (o *BusinessFullCreate) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *BusinessFullCreate) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *BusinessFullCreate) SetCountry(v string)`

SetCountry sets Country field to given value.


### GetCategory

`func (o *BusinessFullCreate) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *BusinessFullCreate) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *BusinessFullCreate) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *BusinessFullCreate) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetReferredByCode

`func (o *BusinessFullCreate) GetReferredByCode() string`

GetReferredByCode returns the ReferredByCode field if non-nil, zero value otherwise.

### GetReferredByCodeOk

`func (o *BusinessFullCreate) GetReferredByCodeOk() (*string, bool)`

GetReferredByCodeOk returns a tuple with the ReferredByCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferredByCode

`func (o *BusinessFullCreate) SetReferredByCode(v string)`

SetReferredByCode sets ReferredByCode field to given value.

### HasReferredByCode

`func (o *BusinessFullCreate) HasReferredByCode() bool`

HasReferredByCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


