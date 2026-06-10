# DisputeList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]Dispute**](Dispute.md) | List of disputes | 
**Meta** | [**DisputeListMetaDto**](DisputeListMetaDto.md) | Pagination metadata | 

## Methods

### NewDisputeList

`func NewDisputeList(data []Dispute, meta DisputeListMetaDto, ) *DisputeList`

NewDisputeList instantiates a new DisputeList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDisputeListWithDefaults

`func NewDisputeListWithDefaults() *DisputeList`

NewDisputeListWithDefaults instantiates a new DisputeList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *DisputeList) GetData() []Dispute`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *DisputeList) GetDataOk() (*[]Dispute, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *DisputeList) SetData(v []Dispute)`

SetData sets Data field to given value.


### GetMeta

`func (o *DisputeList) GetMeta() DisputeListMetaDto`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *DisputeList) GetMetaOk() (*DisputeListMetaDto, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *DisputeList) SetMeta(v DisputeListMetaDto)`

SetMeta sets Meta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


