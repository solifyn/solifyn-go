# OrderCustomer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerId** | **string** | The customer identifier. | 
**Email** | **string** | The customer email address. | 
**Name** | **string** | The customer name. | 
**Username** | Pointer to **string** | The customer username. | [optional] 

## Methods

### NewOrderCustomer

`func NewOrderCustomer(customerId string, email string, name string, ) *OrderCustomer`

NewOrderCustomer instantiates a new OrderCustomer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderCustomerWithDefaults

`func NewOrderCustomerWithDefaults() *OrderCustomer`

NewOrderCustomerWithDefaults instantiates a new OrderCustomer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerId

`func (o *OrderCustomer) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *OrderCustomer) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *OrderCustomer) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.


### GetEmail

`func (o *OrderCustomer) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *OrderCustomer) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *OrderCustomer) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetName

`func (o *OrderCustomer) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OrderCustomer) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OrderCustomer) SetName(v string)`

SetName sets Name field to given value.


### GetUsername

`func (o *OrderCustomer) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *OrderCustomer) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *OrderCustomer) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *OrderCustomer) HasUsername() bool`

HasUsername returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


