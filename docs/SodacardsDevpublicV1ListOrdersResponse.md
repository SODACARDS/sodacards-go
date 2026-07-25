# SodacardsDevpublicV1ListOrdersResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]SodacardsDevpublicV1Order**](SodacardsDevpublicV1Order.md) | data is the page of orders, newest first. | [optional] 
**HasMore** | Pointer to **bool** | has_more is true when another page follows this one. | [optional] 
**NextCursor** | Pointer to **string** | next_cursor fetches the next page. Empty on the last page. | [optional] 

## Methods

### NewSodacardsDevpublicV1ListOrdersResponse

`func NewSodacardsDevpublicV1ListOrdersResponse() *SodacardsDevpublicV1ListOrdersResponse`

NewSodacardsDevpublicV1ListOrdersResponse instantiates a new SodacardsDevpublicV1ListOrdersResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1ListOrdersResponseWithDefaults

`func NewSodacardsDevpublicV1ListOrdersResponseWithDefaults() *SodacardsDevpublicV1ListOrdersResponse`

NewSodacardsDevpublicV1ListOrdersResponseWithDefaults instantiates a new SodacardsDevpublicV1ListOrdersResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *SodacardsDevpublicV1ListOrdersResponse) GetData() []SodacardsDevpublicV1Order`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SodacardsDevpublicV1ListOrdersResponse) GetDataOk() (*[]SodacardsDevpublicV1Order, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SodacardsDevpublicV1ListOrdersResponse) SetData(v []SodacardsDevpublicV1Order)`

SetData sets Data field to given value.

### HasData

`func (o *SodacardsDevpublicV1ListOrdersResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetHasMore

`func (o *SodacardsDevpublicV1ListOrdersResponse) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *SodacardsDevpublicV1ListOrdersResponse) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *SodacardsDevpublicV1ListOrdersResponse) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.

### HasHasMore

`func (o *SodacardsDevpublicV1ListOrdersResponse) HasHasMore() bool`

HasHasMore returns a boolean if a field has been set.

### GetNextCursor

`func (o *SodacardsDevpublicV1ListOrdersResponse) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *SodacardsDevpublicV1ListOrdersResponse) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *SodacardsDevpublicV1ListOrdersResponse) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.

### HasNextCursor

`func (o *SodacardsDevpublicV1ListOrdersResponse) HasNextCursor() bool`

HasNextCursor returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


