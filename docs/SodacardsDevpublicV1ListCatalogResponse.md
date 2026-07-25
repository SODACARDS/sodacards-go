# SodacardsDevpublicV1ListCatalogResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]SodacardsDevpublicV1Product**](SodacardsDevpublicV1Product.md) | data is the page of products, priced for the calling reseller. | [optional] 
**HasMore** | Pointer to **bool** | has_more is true when another page follows this one. | [optional] 
**NextCursor** | Pointer to **string** | next_cursor fetches the next page. Empty on the last page. | [optional] 

## Methods

### NewSodacardsDevpublicV1ListCatalogResponse

`func NewSodacardsDevpublicV1ListCatalogResponse() *SodacardsDevpublicV1ListCatalogResponse`

NewSodacardsDevpublicV1ListCatalogResponse instantiates a new SodacardsDevpublicV1ListCatalogResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1ListCatalogResponseWithDefaults

`func NewSodacardsDevpublicV1ListCatalogResponseWithDefaults() *SodacardsDevpublicV1ListCatalogResponse`

NewSodacardsDevpublicV1ListCatalogResponseWithDefaults instantiates a new SodacardsDevpublicV1ListCatalogResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *SodacardsDevpublicV1ListCatalogResponse) GetData() []SodacardsDevpublicV1Product`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SodacardsDevpublicV1ListCatalogResponse) GetDataOk() (*[]SodacardsDevpublicV1Product, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SodacardsDevpublicV1ListCatalogResponse) SetData(v []SodacardsDevpublicV1Product)`

SetData sets Data field to given value.

### HasData

`func (o *SodacardsDevpublicV1ListCatalogResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetHasMore

`func (o *SodacardsDevpublicV1ListCatalogResponse) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *SodacardsDevpublicV1ListCatalogResponse) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *SodacardsDevpublicV1ListCatalogResponse) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.

### HasHasMore

`func (o *SodacardsDevpublicV1ListCatalogResponse) HasHasMore() bool`

HasHasMore returns a boolean if a field has been set.

### GetNextCursor

`func (o *SodacardsDevpublicV1ListCatalogResponse) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *SodacardsDevpublicV1ListCatalogResponse) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *SodacardsDevpublicV1ListCatalogResponse) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.

### HasNextCursor

`func (o *SodacardsDevpublicV1ListCatalogResponse) HasNextCursor() bool`

HasNextCursor returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


