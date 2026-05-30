# UserPage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Store page record ID | 
**Subdomain** | **string** | Unique subdomain | 
**StoreName** | **string** | Friendly store name | 
**Config** | **map[string]interface{}** | Styling config JSON | 
**BusinessId** | **string** | Linked business ID | 

## Methods

### NewUserPage

`func NewUserPage(id string, subdomain string, storeName string, config map[string]interface{}, businessId string, ) *UserPage`

NewUserPage instantiates a new UserPage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserPageWithDefaults

`func NewUserPageWithDefaults() *UserPage`

NewUserPageWithDefaults instantiates a new UserPage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *UserPage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UserPage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UserPage) SetId(v string)`

SetId sets Id field to given value.


### GetSubdomain

`func (o *UserPage) GetSubdomain() string`

GetSubdomain returns the Subdomain field if non-nil, zero value otherwise.

### GetSubdomainOk

`func (o *UserPage) GetSubdomainOk() (*string, bool)`

GetSubdomainOk returns a tuple with the Subdomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubdomain

`func (o *UserPage) SetSubdomain(v string)`

SetSubdomain sets Subdomain field to given value.


### GetStoreName

`func (o *UserPage) GetStoreName() string`

GetStoreName returns the StoreName field if non-nil, zero value otherwise.

### GetStoreNameOk

`func (o *UserPage) GetStoreNameOk() (*string, bool)`

GetStoreNameOk returns a tuple with the StoreName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreName

`func (o *UserPage) SetStoreName(v string)`

SetStoreName sets StoreName field to given value.


### GetConfig

`func (o *UserPage) GetConfig() map[string]interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *UserPage) GetConfigOk() (*map[string]interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *UserPage) SetConfig(v map[string]interface{})`

SetConfig sets Config field to given value.


### GetBusinessId

`func (o *UserPage) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *UserPage) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *UserPage) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


