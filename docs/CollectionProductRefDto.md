# CollectionProductRefDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The public product identifier (whopId or internal ID) | 
**Quantity** | **float32** | Quantity of this product in the collection | 

## Methods

### NewCollectionProductRefDto

`func NewCollectionProductRefDto(id string, quantity float32, ) *CollectionProductRefDto`

NewCollectionProductRefDto instantiates a new CollectionProductRefDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCollectionProductRefDtoWithDefaults

`func NewCollectionProductRefDtoWithDefaults() *CollectionProductRefDto`

NewCollectionProductRefDtoWithDefaults instantiates a new CollectionProductRefDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CollectionProductRefDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CollectionProductRefDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CollectionProductRefDto) SetId(v string)`

SetId sets Id field to given value.


### GetQuantity

`func (o *CollectionProductRefDto) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CollectionProductRefDto) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CollectionProductRefDto) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


