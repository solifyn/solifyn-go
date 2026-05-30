# PayoutAccountLink

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | The URL redirecting to the Stripe Express onboarding/portal | 
**ExpiresAt** | **time.Time** | Expiration timestamp of the link | 

## Methods

### NewPayoutAccountLink

`func NewPayoutAccountLink(url string, expiresAt time.Time, ) *PayoutAccountLink`

NewPayoutAccountLink instantiates a new PayoutAccountLink object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPayoutAccountLinkWithDefaults

`func NewPayoutAccountLinkWithDefaults() *PayoutAccountLink`

NewPayoutAccountLinkWithDefaults instantiates a new PayoutAccountLink object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *PayoutAccountLink) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *PayoutAccountLink) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *PayoutAccountLink) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetExpiresAt

`func (o *PayoutAccountLink) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *PayoutAccountLink) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *PayoutAccountLink) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


