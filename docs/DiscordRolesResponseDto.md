# DiscordRolesResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The Discord Role ID | 
**Name** | **string** | The Discord Role Name | 
**Position** | **float32** | The position of the role in the server hierarchy | 
**Color** | **float32** | The color of the role (hex integer code) | 

## Methods

### NewDiscordRolesResponseDto

`func NewDiscordRolesResponseDto(id string, name string, position float32, color float32, ) *DiscordRolesResponseDto`

NewDiscordRolesResponseDto instantiates a new DiscordRolesResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiscordRolesResponseDtoWithDefaults

`func NewDiscordRolesResponseDtoWithDefaults() *DiscordRolesResponseDto`

NewDiscordRolesResponseDtoWithDefaults instantiates a new DiscordRolesResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DiscordRolesResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DiscordRolesResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DiscordRolesResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *DiscordRolesResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DiscordRolesResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DiscordRolesResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetPosition

`func (o *DiscordRolesResponseDto) GetPosition() float32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *DiscordRolesResponseDto) GetPositionOk() (*float32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *DiscordRolesResponseDto) SetPosition(v float32)`

SetPosition sets Position field to given value.


### GetColor

`func (o *DiscordRolesResponseDto) GetColor() float32`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *DiscordRolesResponseDto) GetColorOk() (*float32, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *DiscordRolesResponseDto) SetColor(v float32)`

SetColor sets Color field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


