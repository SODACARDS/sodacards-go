# SodacardsDevpublicV1PlaceOrderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Lines** | Pointer to [**[]SodacardsDevpublicV1OrderLine**](SodacardsDevpublicV1OrderLine.md) | lines are the products to buy and how many of each. At least one is required. | [optional] 
**Reference** | Pointer to **string** | reference is an optional identifier you attach to the order to correlate it  with your own system and look it up later. Reusing an Idempotency-Key with a  different reference is a conflict. | [optional] 

## Methods

### NewSodacardsDevpublicV1PlaceOrderRequest

`func NewSodacardsDevpublicV1PlaceOrderRequest() *SodacardsDevpublicV1PlaceOrderRequest`

NewSodacardsDevpublicV1PlaceOrderRequest instantiates a new SodacardsDevpublicV1PlaceOrderRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1PlaceOrderRequestWithDefaults

`func NewSodacardsDevpublicV1PlaceOrderRequestWithDefaults() *SodacardsDevpublicV1PlaceOrderRequest`

NewSodacardsDevpublicV1PlaceOrderRequestWithDefaults instantiates a new SodacardsDevpublicV1PlaceOrderRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLines

`func (o *SodacardsDevpublicV1PlaceOrderRequest) GetLines() []SodacardsDevpublicV1OrderLine`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *SodacardsDevpublicV1PlaceOrderRequest) GetLinesOk() (*[]SodacardsDevpublicV1OrderLine, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *SodacardsDevpublicV1PlaceOrderRequest) SetLines(v []SodacardsDevpublicV1OrderLine)`

SetLines sets Lines field to given value.

### HasLines

`func (o *SodacardsDevpublicV1PlaceOrderRequest) HasLines() bool`

HasLines returns a boolean if a field has been set.

### GetReference

`func (o *SodacardsDevpublicV1PlaceOrderRequest) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *SodacardsDevpublicV1PlaceOrderRequest) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *SodacardsDevpublicV1PlaceOrderRequest) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *SodacardsDevpublicV1PlaceOrderRequest) HasReference() bool`

HasReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


