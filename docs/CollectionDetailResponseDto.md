# CollectionDetailResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The collection ID | 
**Name** | **string** | The name of the collection | 
**Description** | Pointer to **NullableString** | A brief description of the collection | [optional] 
**ImageUrl** | Pointer to **NullableString** | URL of the collection image | [optional] 
**Status** | **string** | Status of the collection | 
**BusinessId** | **string** | The unique identifier of the business owning this collection. | 
**IsPermanentlyDeleted** | **bool** | Indicates if the collection has been permanently deleted. | 
**CreatedAt** | **time.Time** | Timestamp when the collection was created | 
**UpdatedAt** | **time.Time** | Timestamp when the collection was last updated | 
**Products** | Pointer to [**[]CollectionProductDto**](CollectionProductDto.md) | Full product details including quantity for each item in the collection | [optional] 

## Methods

### NewCollectionDetailResponseDto

`func NewCollectionDetailResponseDto(id string, name string, status string, businessId string, isPermanentlyDeleted bool, createdAt time.Time, updatedAt time.Time, ) *CollectionDetailResponseDto`

NewCollectionDetailResponseDto instantiates a new CollectionDetailResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCollectionDetailResponseDtoWithDefaults

`func NewCollectionDetailResponseDtoWithDefaults() *CollectionDetailResponseDto`

NewCollectionDetailResponseDtoWithDefaults instantiates a new CollectionDetailResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CollectionDetailResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CollectionDetailResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CollectionDetailResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *CollectionDetailResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CollectionDetailResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CollectionDetailResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *CollectionDetailResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CollectionDetailResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CollectionDetailResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CollectionDetailResponseDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CollectionDetailResponseDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CollectionDetailResponseDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetImageUrl

`func (o *CollectionDetailResponseDto) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *CollectionDetailResponseDto) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *CollectionDetailResponseDto) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *CollectionDetailResponseDto) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *CollectionDetailResponseDto) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *CollectionDetailResponseDto) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetStatus

`func (o *CollectionDetailResponseDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CollectionDetailResponseDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CollectionDetailResponseDto) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetBusinessId

`func (o *CollectionDetailResponseDto) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *CollectionDetailResponseDto) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *CollectionDetailResponseDto) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetIsPermanentlyDeleted

`func (o *CollectionDetailResponseDto) GetIsPermanentlyDeleted() bool`

GetIsPermanentlyDeleted returns the IsPermanentlyDeleted field if non-nil, zero value otherwise.

### GetIsPermanentlyDeletedOk

`func (o *CollectionDetailResponseDto) GetIsPermanentlyDeletedOk() (*bool, bool)`

GetIsPermanentlyDeletedOk returns a tuple with the IsPermanentlyDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPermanentlyDeleted

`func (o *CollectionDetailResponseDto) SetIsPermanentlyDeleted(v bool)`

SetIsPermanentlyDeleted sets IsPermanentlyDeleted field to given value.


### GetCreatedAt

`func (o *CollectionDetailResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CollectionDetailResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CollectionDetailResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *CollectionDetailResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CollectionDetailResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CollectionDetailResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetProducts

`func (o *CollectionDetailResponseDto) GetProducts() []CollectionProductDto`

GetProducts returns the Products field if non-nil, zero value otherwise.

### GetProductsOk

`func (o *CollectionDetailResponseDto) GetProductsOk() (*[]CollectionProductDto, bool)`

GetProductsOk returns a tuple with the Products field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducts

`func (o *CollectionDetailResponseDto) SetProducts(v []CollectionProductDto)`

SetProducts sets Products field to given value.

### HasProducts

`func (o *CollectionDetailResponseDto) HasProducts() bool`

HasProducts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


