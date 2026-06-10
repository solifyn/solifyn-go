# CreateCollectionDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | The friendly name of the collection | 
**Description** | Pointer to **string** | A detailed description of this collection | [optional] 
**ImageUrl** | Pointer to **string** | The display cover image URL for this collection | [optional] 
**Status** | Pointer to **string** | The collection status | [optional] 
**Products** | [**[]CollectionProductEntry**](CollectionProductEntry.md) | List of products to include in this collection. At least one product is required. | 

## Methods

### NewCreateCollectionDto

`func NewCreateCollectionDto(name string, products []CollectionProductEntry, ) *CreateCollectionDto`

NewCreateCollectionDto instantiates a new CreateCollectionDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCollectionDtoWithDefaults

`func NewCreateCollectionDtoWithDefaults() *CreateCollectionDto`

NewCreateCollectionDtoWithDefaults instantiates a new CreateCollectionDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateCollectionDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateCollectionDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateCollectionDto) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *CreateCollectionDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateCollectionDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateCollectionDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateCollectionDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetImageUrl

`func (o *CreateCollectionDto) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *CreateCollectionDto) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *CreateCollectionDto) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *CreateCollectionDto) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### GetStatus

`func (o *CreateCollectionDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateCollectionDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateCollectionDto) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateCollectionDto) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetProducts

`func (o *CreateCollectionDto) GetProducts() []CollectionProductEntry`

GetProducts returns the Products field if non-nil, zero value otherwise.

### GetProductsOk

`func (o *CreateCollectionDto) GetProductsOk() (*[]CollectionProductEntry, bool)`

GetProductsOk returns a tuple with the Products field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducts

`func (o *CreateCollectionDto) SetProducts(v []CollectionProductEntry)`

SetProducts sets Products field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


