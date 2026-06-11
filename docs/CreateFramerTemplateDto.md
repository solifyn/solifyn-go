# CreateFramerTemplateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | The name of the Framer template. | 
**RemixLink** | **string** | The public Framer remix link. | 
**Description** | Pointer to **string** | A brief description of the template. | [optional] 

## Methods

### NewCreateFramerTemplateDto

`func NewCreateFramerTemplateDto(name string, remixLink string, ) *CreateFramerTemplateDto`

NewCreateFramerTemplateDto instantiates a new CreateFramerTemplateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateFramerTemplateDtoWithDefaults

`func NewCreateFramerTemplateDtoWithDefaults() *CreateFramerTemplateDto`

NewCreateFramerTemplateDtoWithDefaults instantiates a new CreateFramerTemplateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateFramerTemplateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateFramerTemplateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateFramerTemplateDto) SetName(v string)`

SetName sets Name field to given value.


### GetRemixLink

`func (o *CreateFramerTemplateDto) GetRemixLink() string`

GetRemixLink returns the RemixLink field if non-nil, zero value otherwise.

### GetRemixLinkOk

`func (o *CreateFramerTemplateDto) GetRemixLinkOk() (*string, bool)`

GetRemixLinkOk returns a tuple with the RemixLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemixLink

`func (o *CreateFramerTemplateDto) SetRemixLink(v string)`

SetRemixLink sets RemixLink field to given value.


### GetDescription

`func (o *CreateFramerTemplateDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateFramerTemplateDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateFramerTemplateDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateFramerTemplateDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


