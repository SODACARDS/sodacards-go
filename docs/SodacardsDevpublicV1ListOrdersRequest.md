# SodacardsDevpublicV1ListOrdersRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | Pointer to **int32** | limit is the maximum number of orders to return (1..100). Zero applies the  default page size. | [optional] 
**Cursor** | Pointer to **string** | cursor is the next_cursor of the previous page. Empty for the first page. | [optional] 
**Reference** | Pointer to **string** | reference, when set, filters the list to the orders carrying that client  reference. The cursor is ignored when a reference is given. | [optional] 

## Methods

### NewSodacardsDevpublicV1ListOrdersRequest

`func NewSodacardsDevpublicV1ListOrdersRequest() *SodacardsDevpublicV1ListOrdersRequest`

NewSodacardsDevpublicV1ListOrdersRequest instantiates a new SodacardsDevpublicV1ListOrdersRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1ListOrdersRequestWithDefaults

`func NewSodacardsDevpublicV1ListOrdersRequestWithDefaults() *SodacardsDevpublicV1ListOrdersRequest`

NewSodacardsDevpublicV1ListOrdersRequestWithDefaults instantiates a new SodacardsDevpublicV1ListOrdersRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *SodacardsDevpublicV1ListOrdersRequest) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *SodacardsDevpublicV1ListOrdersRequest) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *SodacardsDevpublicV1ListOrdersRequest) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *SodacardsDevpublicV1ListOrdersRequest) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetCursor

`func (o *SodacardsDevpublicV1ListOrdersRequest) GetCursor() string`

GetCursor returns the Cursor field if non-nil, zero value otherwise.

### GetCursorOk

`func (o *SodacardsDevpublicV1ListOrdersRequest) GetCursorOk() (*string, bool)`

GetCursorOk returns a tuple with the Cursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursor

`func (o *SodacardsDevpublicV1ListOrdersRequest) SetCursor(v string)`

SetCursor sets Cursor field to given value.

### HasCursor

`func (o *SodacardsDevpublicV1ListOrdersRequest) HasCursor() bool`

HasCursor returns a boolean if a field has been set.

### GetReference

`func (o *SodacardsDevpublicV1ListOrdersRequest) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *SodacardsDevpublicV1ListOrdersRequest) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *SodacardsDevpublicV1ListOrdersRequest) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *SodacardsDevpublicV1ListOrdersRequest) HasReference() bool`

HasReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


