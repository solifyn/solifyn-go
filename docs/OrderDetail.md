# OrderDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FilesSnapshot** | Pointer to **[]string** | Snapshot of files accessible after payment. | [optional] 
**LicenseKey** | Pointer to **string** | Assigned license key, if applicable. | [optional] 
**Status** | Pointer to **string** | Order resolution status. | [optional] 

## Methods

### NewOrderDetail

`func NewOrderDetail() *OrderDetail`

NewOrderDetail instantiates a new OrderDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderDetailWithDefaults

`func NewOrderDetailWithDefaults() *OrderDetail`

NewOrderDetailWithDefaults instantiates a new OrderDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFilesSnapshot

`func (o *OrderDetail) GetFilesSnapshot() []string`

GetFilesSnapshot returns the FilesSnapshot field if non-nil, zero value otherwise.

### GetFilesSnapshotOk

`func (o *OrderDetail) GetFilesSnapshotOk() (*[]string, bool)`

GetFilesSnapshotOk returns a tuple with the FilesSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesSnapshot

`func (o *OrderDetail) SetFilesSnapshot(v []string)`

SetFilesSnapshot sets FilesSnapshot field to given value.

### HasFilesSnapshot

`func (o *OrderDetail) HasFilesSnapshot() bool`

HasFilesSnapshot returns a boolean if a field has been set.

### GetLicenseKey

`func (o *OrderDetail) GetLicenseKey() string`

GetLicenseKey returns the LicenseKey field if non-nil, zero value otherwise.

### GetLicenseKeyOk

`func (o *OrderDetail) GetLicenseKeyOk() (*string, bool)`

GetLicenseKeyOk returns a tuple with the LicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseKey

`func (o *OrderDetail) SetLicenseKey(v string)`

SetLicenseKey sets LicenseKey field to given value.

### HasLicenseKey

`func (o *OrderDetail) HasLicenseKey() bool`

HasLicenseKey returns a boolean if a field has been set.

### GetStatus

`func (o *OrderDetail) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OrderDetail) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OrderDetail) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *OrderDetail) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


