# FramerTemplateResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The unique Framer template ID. | 
**BusinessId** | **string** | The business ID owning the template. | 
**Name** | **string** | The name of the Framer template. | 
**RemixLink** | **string** | The public Framer remix link. | 
**Description** | Pointer to **string** | A brief description of the template. | [optional] 
**CreatedAt** | **string** | Creation timestamp. | 
**UpdatedAt** | **string** | Modification timestamp. | 

## Methods

### NewFramerTemplateResponseDto

`func NewFramerTemplateResponseDto(id string, businessId string, name string, remixLink string, createdAt string, updatedAt string, ) *FramerTemplateResponseDto`

NewFramerTemplateResponseDto instantiates a new FramerTemplateResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFramerTemplateResponseDtoWithDefaults

`func NewFramerTemplateResponseDtoWithDefaults() *FramerTemplateResponseDto`

NewFramerTemplateResponseDtoWithDefaults instantiates a new FramerTemplateResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FramerTemplateResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FramerTemplateResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FramerTemplateResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetBusinessId

`func (o *FramerTemplateResponseDto) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *FramerTemplateResponseDto) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *FramerTemplateResponseDto) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetName

`func (o *FramerTemplateResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FramerTemplateResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FramerTemplateResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetRemixLink

`func (o *FramerTemplateResponseDto) GetRemixLink() string`

GetRemixLink returns the RemixLink field if non-nil, zero value otherwise.

### GetRemixLinkOk

`func (o *FramerTemplateResponseDto) GetRemixLinkOk() (*string, bool)`

GetRemixLinkOk returns a tuple with the RemixLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemixLink

`func (o *FramerTemplateResponseDto) SetRemixLink(v string)`

SetRemixLink sets RemixLink field to given value.


### GetDescription

`func (o *FramerTemplateResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *FramerTemplateResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *FramerTemplateResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *FramerTemplateResponseDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCreatedAt

`func (o *FramerTemplateResponseDto) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FramerTemplateResponseDto) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FramerTemplateResponseDto) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *FramerTemplateResponseDto) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *FramerTemplateResponseDto) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *FramerTemplateResponseDto) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


