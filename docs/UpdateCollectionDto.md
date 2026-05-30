# UpdateCollectionDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | The friendly name of the collection | [optional] 
**Description** | Pointer to **string** | A detailed description of this collection | [optional] 
**ImageUrl** | Pointer to **string** | The display cover image URL for this collection | [optional] 

## Methods

### NewUpdateCollectionDto

`func NewUpdateCollectionDto() *UpdateCollectionDto`

NewUpdateCollectionDto instantiates a new UpdateCollectionDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateCollectionDtoWithDefaults

`func NewUpdateCollectionDtoWithDefaults() *UpdateCollectionDto`

NewUpdateCollectionDtoWithDefaults instantiates a new UpdateCollectionDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateCollectionDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateCollectionDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateCollectionDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateCollectionDto) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateCollectionDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateCollectionDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateCollectionDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateCollectionDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetImageUrl

`func (o *UpdateCollectionDto) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *UpdateCollectionDto) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *UpdateCollectionDto) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *UpdateCollectionDto) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


