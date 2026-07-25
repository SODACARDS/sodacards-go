# SodacardsDevpublicV1Order

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | id identifies the order. | [optional] 
**Status** | Pointer to **string** | status is the order&#39;s current state: \&quot;pending\&quot;, \&quot;processing\&quot;, \&quot;completed\&quot;,  \&quot;failed\&quot; or \&quot;refunded\&quot;. | [optional] 
**Total** | Pointer to [**SodacardsDevpublicV1Money**](SodacardsDevpublicV1Money.md) | total is the amount charged for the order, in FCFA. | [optional] 
**CreatedAt** | Pointer to **string** | created_at is when the order was placed (RFC 3339). | [optional] 
**Reference** | Pointer to **string** | reference is the identifier you attached at creation, empty if none. | [optional] 
**Lines** | Pointer to [**[]SodacardsDevpublicV1OrderItem**](SodacardsDevpublicV1OrderItem.md) | lines are the ordered products. | [optional] 

## Methods

### NewSodacardsDevpublicV1Order

`func NewSodacardsDevpublicV1Order() *SodacardsDevpublicV1Order`

NewSodacardsDevpublicV1Order instantiates a new SodacardsDevpublicV1Order object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1OrderWithDefaults

`func NewSodacardsDevpublicV1OrderWithDefaults() *SodacardsDevpublicV1Order`

NewSodacardsDevpublicV1OrderWithDefaults instantiates a new SodacardsDevpublicV1Order object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SodacardsDevpublicV1Order) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SodacardsDevpublicV1Order) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SodacardsDevpublicV1Order) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SodacardsDevpublicV1Order) HasId() bool`

HasId returns a boolean if a field has been set.

### GetStatus

`func (o *SodacardsDevpublicV1Order) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SodacardsDevpublicV1Order) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SodacardsDevpublicV1Order) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SodacardsDevpublicV1Order) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTotal

`func (o *SodacardsDevpublicV1Order) GetTotal() SodacardsDevpublicV1Money`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *SodacardsDevpublicV1Order) GetTotalOk() (*SodacardsDevpublicV1Money, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *SodacardsDevpublicV1Order) SetTotal(v SodacardsDevpublicV1Money)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *SodacardsDevpublicV1Order) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetCreatedAt

`func (o *SodacardsDevpublicV1Order) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SodacardsDevpublicV1Order) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SodacardsDevpublicV1Order) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *SodacardsDevpublicV1Order) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetReference

`func (o *SodacardsDevpublicV1Order) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *SodacardsDevpublicV1Order) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *SodacardsDevpublicV1Order) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *SodacardsDevpublicV1Order) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetLines

`func (o *SodacardsDevpublicV1Order) GetLines() []SodacardsDevpublicV1OrderItem`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *SodacardsDevpublicV1Order) GetLinesOk() (*[]SodacardsDevpublicV1OrderItem, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *SodacardsDevpublicV1Order) SetLines(v []SodacardsDevpublicV1OrderItem)`

SetLines sets Lines field to given value.

### HasLines

`func (o *SodacardsDevpublicV1Order) HasLines() bool`

HasLines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


