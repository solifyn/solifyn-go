# PricePreviewResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OriginalPrice** | **float32** | Original price of the product after discounts | 
**OriginalCurrency** | **string** | Original ISO currency code of the product | 
**ConvertedPrice** | **float32** | Converted price of the product | 
**ConvertedCurrency** | **string** | Converted ISO currency code of the product | 

## Methods

### NewPricePreviewResponseDto

`func NewPricePreviewResponseDto(originalPrice float32, originalCurrency string, convertedPrice float32, convertedCurrency string, ) *PricePreviewResponseDto`

NewPricePreviewResponseDto instantiates a new PricePreviewResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPricePreviewResponseDtoWithDefaults

`func NewPricePreviewResponseDtoWithDefaults() *PricePreviewResponseDto`

NewPricePreviewResponseDtoWithDefaults instantiates a new PricePreviewResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOriginalPrice

`func (o *PricePreviewResponseDto) GetOriginalPrice() float32`

GetOriginalPrice returns the OriginalPrice field if non-nil, zero value otherwise.

### GetOriginalPriceOk

`func (o *PricePreviewResponseDto) GetOriginalPriceOk() (*float32, bool)`

GetOriginalPriceOk returns a tuple with the OriginalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalPrice

`func (o *PricePreviewResponseDto) SetOriginalPrice(v float32)`

SetOriginalPrice sets OriginalPrice field to given value.


### GetOriginalCurrency

`func (o *PricePreviewResponseDto) GetOriginalCurrency() string`

GetOriginalCurrency returns the OriginalCurrency field if non-nil, zero value otherwise.

### GetOriginalCurrencyOk

`func (o *PricePreviewResponseDto) GetOriginalCurrencyOk() (*string, bool)`

GetOriginalCurrencyOk returns a tuple with the OriginalCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalCurrency

`func (o *PricePreviewResponseDto) SetOriginalCurrency(v string)`

SetOriginalCurrency sets OriginalCurrency field to given value.


### GetConvertedPrice

`func (o *PricePreviewResponseDto) GetConvertedPrice() float32`

GetConvertedPrice returns the ConvertedPrice field if non-nil, zero value otherwise.

### GetConvertedPriceOk

`func (o *PricePreviewResponseDto) GetConvertedPriceOk() (*float32, bool)`

GetConvertedPriceOk returns a tuple with the ConvertedPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConvertedPrice

`func (o *PricePreviewResponseDto) SetConvertedPrice(v float32)`

SetConvertedPrice sets ConvertedPrice field to given value.


### GetConvertedCurrency

`func (o *PricePreviewResponseDto) GetConvertedCurrency() string`

GetConvertedCurrency returns the ConvertedCurrency field if non-nil, zero value otherwise.

### GetConvertedCurrencyOk

`func (o *PricePreviewResponseDto) GetConvertedCurrencyOk() (*string, bool)`

GetConvertedCurrencyOk returns a tuple with the ConvertedCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConvertedCurrency

`func (o *PricePreviewResponseDto) SetConvertedCurrency(v string)`

SetConvertedCurrency sets ConvertedCurrency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


