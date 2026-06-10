# Dispute

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The dispute ID | 
**WhopId** | **string** | The Whop Dispute ID | 
**Amount** | **float32** | The dispute amount | 
**Currency** | **string** | The currency code | 
**Status** | **string** | The status of the dispute | 
**Reason** | Pointer to **string** | The reason for the dispute | [optional] 
**Editable** | **bool** | Whether the evidence is still editable | 
**NeedsResponseBy** | Pointer to **time.Time** | Timestamp by when evidence must be submitted | [optional] 
**VisaRdr** | **bool** | Whether Visa RDR was applied | 
**BillingAddress** | Pointer to **string** | Customer billing address details | [optional] 
**CustomerName** | Pointer to **string** | Customer name | [optional] 
**CustomerEmail** | Pointer to **string** | Customer email address | [optional] 
**Notes** | Pointer to **string** | Additional notes | [optional] 
**ProductDescription** | Pointer to **string** | Product or service description | [optional] 
**ServiceDate** | Pointer to **string** | Service or purchase date | [optional] 
**AccessActivityLog** | Pointer to **string** | Log of access activity | [optional] 
**Evidence** | Pointer to [**DisputeEvidenceDto**](DisputeEvidenceDto.md) | Evidence attachments associated with the dispute | [optional] 
**PaymentId** | **string** | The associated payment ID | 
**BusinessId** | **string** | The associated business ID | 
**CreatedAt** | **time.Time** | Timestamp when the dispute was created | 
**UpdatedAt** | **time.Time** | Timestamp when the dispute was last updated | 

## Methods

### NewDispute

`func NewDispute(id string, whopId string, amount float32, currency string, status string, editable bool, visaRdr bool, paymentId string, businessId string, createdAt time.Time, updatedAt time.Time, ) *Dispute`

NewDispute instantiates a new Dispute object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDisputeWithDefaults

`func NewDisputeWithDefaults() *Dispute`

NewDisputeWithDefaults instantiates a new Dispute object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Dispute) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Dispute) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Dispute) SetId(v string)`

SetId sets Id field to given value.


### GetWhopId

`func (o *Dispute) GetWhopId() string`

GetWhopId returns the WhopId field if non-nil, zero value otherwise.

### GetWhopIdOk

`func (o *Dispute) GetWhopIdOk() (*string, bool)`

GetWhopIdOk returns a tuple with the WhopId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhopId

`func (o *Dispute) SetWhopId(v string)`

SetWhopId sets WhopId field to given value.


### GetAmount

`func (o *Dispute) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *Dispute) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *Dispute) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### GetCurrency

`func (o *Dispute) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Dispute) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Dispute) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetStatus

`func (o *Dispute) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Dispute) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Dispute) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetReason

`func (o *Dispute) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *Dispute) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *Dispute) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *Dispute) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetEditable

`func (o *Dispute) GetEditable() bool`

GetEditable returns the Editable field if non-nil, zero value otherwise.

### GetEditableOk

`func (o *Dispute) GetEditableOk() (*bool, bool)`

GetEditableOk returns a tuple with the Editable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEditable

`func (o *Dispute) SetEditable(v bool)`

SetEditable sets Editable field to given value.


### GetNeedsResponseBy

`func (o *Dispute) GetNeedsResponseBy() time.Time`

GetNeedsResponseBy returns the NeedsResponseBy field if non-nil, zero value otherwise.

### GetNeedsResponseByOk

`func (o *Dispute) GetNeedsResponseByOk() (*time.Time, bool)`

GetNeedsResponseByOk returns a tuple with the NeedsResponseBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeedsResponseBy

`func (o *Dispute) SetNeedsResponseBy(v time.Time)`

SetNeedsResponseBy sets NeedsResponseBy field to given value.

### HasNeedsResponseBy

`func (o *Dispute) HasNeedsResponseBy() bool`

HasNeedsResponseBy returns a boolean if a field has been set.

### GetVisaRdr

`func (o *Dispute) GetVisaRdr() bool`

GetVisaRdr returns the VisaRdr field if non-nil, zero value otherwise.

### GetVisaRdrOk

`func (o *Dispute) GetVisaRdrOk() (*bool, bool)`

GetVisaRdrOk returns a tuple with the VisaRdr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisaRdr

`func (o *Dispute) SetVisaRdr(v bool)`

SetVisaRdr sets VisaRdr field to given value.


### GetBillingAddress

`func (o *Dispute) GetBillingAddress() string`

GetBillingAddress returns the BillingAddress field if non-nil, zero value otherwise.

### GetBillingAddressOk

`func (o *Dispute) GetBillingAddressOk() (*string, bool)`

GetBillingAddressOk returns a tuple with the BillingAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingAddress

`func (o *Dispute) SetBillingAddress(v string)`

SetBillingAddress sets BillingAddress field to given value.

### HasBillingAddress

`func (o *Dispute) HasBillingAddress() bool`

HasBillingAddress returns a boolean if a field has been set.

### GetCustomerName

`func (o *Dispute) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *Dispute) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *Dispute) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.

### HasCustomerName

`func (o *Dispute) HasCustomerName() bool`

HasCustomerName returns a boolean if a field has been set.

### GetCustomerEmail

`func (o *Dispute) GetCustomerEmail() string`

GetCustomerEmail returns the CustomerEmail field if non-nil, zero value otherwise.

### GetCustomerEmailOk

`func (o *Dispute) GetCustomerEmailOk() (*string, bool)`

GetCustomerEmailOk returns a tuple with the CustomerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerEmail

`func (o *Dispute) SetCustomerEmail(v string)`

SetCustomerEmail sets CustomerEmail field to given value.

### HasCustomerEmail

`func (o *Dispute) HasCustomerEmail() bool`

HasCustomerEmail returns a boolean if a field has been set.

### GetNotes

`func (o *Dispute) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *Dispute) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *Dispute) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *Dispute) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetProductDescription

`func (o *Dispute) GetProductDescription() string`

GetProductDescription returns the ProductDescription field if non-nil, zero value otherwise.

### GetProductDescriptionOk

`func (o *Dispute) GetProductDescriptionOk() (*string, bool)`

GetProductDescriptionOk returns a tuple with the ProductDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductDescription

`func (o *Dispute) SetProductDescription(v string)`

SetProductDescription sets ProductDescription field to given value.

### HasProductDescription

`func (o *Dispute) HasProductDescription() bool`

HasProductDescription returns a boolean if a field has been set.

### GetServiceDate

`func (o *Dispute) GetServiceDate() string`

GetServiceDate returns the ServiceDate field if non-nil, zero value otherwise.

### GetServiceDateOk

`func (o *Dispute) GetServiceDateOk() (*string, bool)`

GetServiceDateOk returns a tuple with the ServiceDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceDate

`func (o *Dispute) SetServiceDate(v string)`

SetServiceDate sets ServiceDate field to given value.

### HasServiceDate

`func (o *Dispute) HasServiceDate() bool`

HasServiceDate returns a boolean if a field has been set.

### GetAccessActivityLog

`func (o *Dispute) GetAccessActivityLog() string`

GetAccessActivityLog returns the AccessActivityLog field if non-nil, zero value otherwise.

### GetAccessActivityLogOk

`func (o *Dispute) GetAccessActivityLogOk() (*string, bool)`

GetAccessActivityLogOk returns a tuple with the AccessActivityLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessActivityLog

`func (o *Dispute) SetAccessActivityLog(v string)`

SetAccessActivityLog sets AccessActivityLog field to given value.

### HasAccessActivityLog

`func (o *Dispute) HasAccessActivityLog() bool`

HasAccessActivityLog returns a boolean if a field has been set.

### GetEvidence

`func (o *Dispute) GetEvidence() DisputeEvidenceDto`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *Dispute) GetEvidenceOk() (*DisputeEvidenceDto, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *Dispute) SetEvidence(v DisputeEvidenceDto)`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *Dispute) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### GetPaymentId

`func (o *Dispute) GetPaymentId() string`

GetPaymentId returns the PaymentId field if non-nil, zero value otherwise.

### GetPaymentIdOk

`func (o *Dispute) GetPaymentIdOk() (*string, bool)`

GetPaymentIdOk returns a tuple with the PaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentId

`func (o *Dispute) SetPaymentId(v string)`

SetPaymentId sets PaymentId field to given value.


### GetBusinessId

`func (o *Dispute) GetBusinessId() string`

GetBusinessId returns the BusinessId field if non-nil, zero value otherwise.

### GetBusinessIdOk

`func (o *Dispute) GetBusinessIdOk() (*string, bool)`

GetBusinessIdOk returns a tuple with the BusinessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessId

`func (o *Dispute) SetBusinessId(v string)`

SetBusinessId sets BusinessId field to given value.


### GetCreatedAt

`func (o *Dispute) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Dispute) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Dispute) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Dispute) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Dispute) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Dispute) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


