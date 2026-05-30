# MeterIngestResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Processed** | **float32** | Number of successfully processed events. | 
**Failed** | **float32** | Number of failed events. | 
**Errors** | **[]map[string]interface{}** | List of errors encountered during ingestion. | 

## Methods

### NewMeterIngestResponseDto

`func NewMeterIngestResponseDto(processed float32, failed float32, errors []map[string]interface{}, ) *MeterIngestResponseDto`

NewMeterIngestResponseDto instantiates a new MeterIngestResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMeterIngestResponseDtoWithDefaults

`func NewMeterIngestResponseDtoWithDefaults() *MeterIngestResponseDto`

NewMeterIngestResponseDtoWithDefaults instantiates a new MeterIngestResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProcessed

`func (o *MeterIngestResponseDto) GetProcessed() float32`

GetProcessed returns the Processed field if non-nil, zero value otherwise.

### GetProcessedOk

`func (o *MeterIngestResponseDto) GetProcessedOk() (*float32, bool)`

GetProcessedOk returns a tuple with the Processed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessed

`func (o *MeterIngestResponseDto) SetProcessed(v float32)`

SetProcessed sets Processed field to given value.


### GetFailed

`func (o *MeterIngestResponseDto) GetFailed() float32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *MeterIngestResponseDto) GetFailedOk() (*float32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *MeterIngestResponseDto) SetFailed(v float32)`

SetFailed sets Failed field to given value.


### GetErrors

`func (o *MeterIngestResponseDto) GetErrors() []map[string]interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *MeterIngestResponseDto) GetErrorsOk() (*[]map[string]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *MeterIngestResponseDto) SetErrors(v []map[string]interface{})`

SetErrors sets Errors field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


