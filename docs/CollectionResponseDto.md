# CollectionResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The collection ID | 
**Name** | **string** | The name of the collection | 
**Description** | Pointer to **string** | A brief description of the collection | [optional] 
**ImageUrl** | Pointer to **string** | URL of the collection image | [optional] 
**Status** | **string** | Status of the collection | 
**BusinessId** | **string** | The unique identifier of the business owning this collection. | 
**IsPermanentlyDeleted** | **bool** | Indicates if the collection has been permanently deleted. | 
**CreatedAt** | **time.Time** | Timestamp when the collection was created | 
**UpdatedAt** | **time.Time** | Timestamp when the collection was last updated | 
**Products** | Pointer to [**[]CollectionProductRefDto**](CollectionProductRefDto.md) | List of product references (id + quantity). Full product details are available via GET /products/:id. | [optional] 

## Methods

### NewCollectionResponseDto

`func NewCollectionResponseDto(id string, name string, status string, businessId string, isPermanentlyDeleted bool, createdAt time.Time, updatedAt time.Time, ) *CollectionResponseDto`

NewCollectionResponseDto instantiates a new CollectionResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCollectionResponseDtoWithDefaults

`func NewCollectionResponseDtoWithDefaults() *CollectionResponseDto`

NewCollectionResponseDtoWithDefaults instantiates a new CollectionResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CollectionResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CollectionResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CollectionResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *CollectionResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CollectionResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CollectionResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *CollectionResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CollectionResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CollectionResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CollectionResponseDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetImageUrl

`func (o *CollectionResponseDto) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *CollectionResponseDto) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *CollectionResponseDto) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *CollectionResponseDto) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### GetStatus

`func (o *CollectionResponseDto) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CollectionResponseDto) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CollectionResponseDto) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetBusinessId

`func (o *CollectionResponseDto) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *CollectionResponseDto) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *CollectionResponseDto) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetIsPermanentlyDeleted

`func (o *CollectionResponseDto) GetIsPermanentlyDeleted() bool`

GetIsPermanentlyDeleted returns the IsPermanentlyDeleted field if non-nil, zero value otherwise.

### GetIsPermanentlyDeletedOk

`func (o *CollectionResponseDto) GetIsPermanentlyDeletedOk() (*bool, bool)`

GetIsPermanentlyDeletedOk returns a tuple with the IsPermanentlyDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPermanentlyDeleted

`func (o *CollectionResponseDto) SetIsPermanentlyDeleted(v bool)`

SetIsPermanentlyDeleted sets IsPermanentlyDeleted field to given value.


### GetCreatedAt

`func (o *CollectionResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CollectionResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CollectionResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *CollectionResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CollectionResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CollectionResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetProducts

`func (o *CollectionResponseDto) GetProducts() []CollectionProductRefDto`

GetProducts returns the Products field if non-nil, zero value otherwise.

### GetProductsOk

`func (o *CollectionResponseDto) GetProductsOk() (*[]CollectionProductRefDto, bool)`

GetProductsOk returns a tuple with the Products field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducts

`func (o *CollectionResponseDto) SetProducts(v []CollectionProductRefDto)`

SetProducts sets Products field to given value.

### HasProducts

`func (o *CollectionResponseDto) HasProducts() bool`

HasProducts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


