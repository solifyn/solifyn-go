# CheckoutResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique identifier for the checkout session in database | 
**SessionId** | **string** | The unique session ID format for external clients | 
**CheckoutUrl** | **string** | The public redirect URL to the custom payment steps page | 

## Methods

### NewCheckoutResponseDto

`func NewCheckoutResponseDto(id string, sessionId string, checkoutUrl string, ) *CheckoutResponseDto`

NewCheckoutResponseDto instantiates a new CheckoutResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCheckoutResponseDtoWithDefaults

`func NewCheckoutResponseDtoWithDefaults() *CheckoutResponseDto`

NewCheckoutResponseDtoWithDefaults instantiates a new CheckoutResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CheckoutResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CheckoutResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CheckoutResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetSessionId

`func (o *CheckoutResponseDto) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *CheckoutResponseDto) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *CheckoutResponseDto) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.


### GetCheckoutUrl

`func (o *CheckoutResponseDto) GetCheckoutUrl() string`

GetCheckoutUrl returns the CheckoutUrl field if non-nil, zero value otherwise.

### GetCheckoutUrlOk

`func (o *CheckoutResponseDto) GetCheckoutUrlOk() (*string, bool)`

GetCheckoutUrlOk returns a tuple with the CheckoutUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutUrl

`func (o *CheckoutResponseDto) SetCheckoutUrl(v string)`

SetCheckoutUrl sets CheckoutUrl field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


