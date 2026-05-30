# SubscriptionProductDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique ID of the product | 
**Title** | **string** | The title/name of the product | 
**Metadata** | Pointer to **map[string]interface{}** | Additional metadata associated with the product | [optional] 

## Methods

### NewSubscriptionProductDto

`func NewSubscriptionProductDto(id string, title string, ) *SubscriptionProductDto`

NewSubscriptionProductDto instantiates a new SubscriptionProductDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionProductDtoWithDefaults

`func NewSubscriptionProductDtoWithDefaults() *SubscriptionProductDto`

NewSubscriptionProductDtoWithDefaults instantiates a new SubscriptionProductDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SubscriptionProductDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SubscriptionProductDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SubscriptionProductDto) SetId(v string)`

SetId sets Id field to given value.


### GetTitle

`func (o *SubscriptionProductDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *SubscriptionProductDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *SubscriptionProductDto) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetMetadata

`func (o *SubscriptionProductDto) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *SubscriptionProductDto) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *SubscriptionProductDto) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *SubscriptionProductDto) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


