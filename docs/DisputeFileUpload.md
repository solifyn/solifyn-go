# DisputeFileUpload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Uploaded file ID | 
**Filename** | **string** | Name of the file | 
**UploadUrl** | Pointer to **string** | S3 presigned upload URL | [optional] 
**UploadHeaders** | Pointer to **map[string]interface{}** | HTTP headers required for the S3 upload request | [optional] 

## Methods

### NewDisputeFileUpload

`func NewDisputeFileUpload(id string, filename string, ) *DisputeFileUpload`

NewDisputeFileUpload instantiates a new DisputeFileUpload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDisputeFileUploadWithDefaults

`func NewDisputeFileUploadWithDefaults() *DisputeFileUpload`

NewDisputeFileUploadWithDefaults instantiates a new DisputeFileUpload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DisputeFileUpload) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DisputeFileUpload) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DisputeFileUpload) SetId(v string)`

SetId sets Id field to given value.


### GetFilename

`func (o *DisputeFileUpload) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *DisputeFileUpload) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *DisputeFileUpload) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetUploadUrl

`func (o *DisputeFileUpload) GetUploadUrl() string`

GetUploadUrl returns the UploadUrl field if non-nil, zero value otherwise.

### GetUploadUrlOk

`func (o *DisputeFileUpload) GetUploadUrlOk() (*string, bool)`

GetUploadUrlOk returns a tuple with the UploadUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadUrl

`func (o *DisputeFileUpload) SetUploadUrl(v string)`

SetUploadUrl sets UploadUrl field to given value.

### HasUploadUrl

`func (o *DisputeFileUpload) HasUploadUrl() bool`

HasUploadUrl returns a boolean if a field has been set.

### GetUploadHeaders

`func (o *DisputeFileUpload) GetUploadHeaders() map[string]interface{}`

GetUploadHeaders returns the UploadHeaders field if non-nil, zero value otherwise.

### GetUploadHeadersOk

`func (o *DisputeFileUpload) GetUploadHeadersOk() (*map[string]interface{}, bool)`

GetUploadHeadersOk returns a tuple with the UploadHeaders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadHeaders

`func (o *DisputeFileUpload) SetUploadHeaders(v map[string]interface{})`

SetUploadHeaders sets UploadHeaders field to given value.

### HasUploadHeaders

`func (o *DisputeFileUpload) HasUploadHeaders() bool`

HasUploadHeaders returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


