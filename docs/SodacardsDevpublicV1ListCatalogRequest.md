# SodacardsDevpublicV1ListCatalogRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | Pointer to **int32** | limit is the maximum number of products to return (1..100). Zero applies the  default page size. | [optional] 
**Cursor** | Pointer to **string** | cursor is the next_cursor of the previous page. Empty for the first page. | [optional] 

## Methods

### NewSodacardsDevpublicV1ListCatalogRequest

`func NewSodacardsDevpublicV1ListCatalogRequest() *SodacardsDevpublicV1ListCatalogRequest`

NewSodacardsDevpublicV1ListCatalogRequest instantiates a new SodacardsDevpublicV1ListCatalogRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1ListCatalogRequestWithDefaults

`func NewSodacardsDevpublicV1ListCatalogRequestWithDefaults() *SodacardsDevpublicV1ListCatalogRequest`

NewSodacardsDevpublicV1ListCatalogRequestWithDefaults instantiates a new SodacardsDevpublicV1ListCatalogRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *SodacardsDevpublicV1ListCatalogRequest) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *SodacardsDevpublicV1ListCatalogRequest) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *SodacardsDevpublicV1ListCatalogRequest) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *SodacardsDevpublicV1ListCatalogRequest) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetCursor

`func (o *SodacardsDevpublicV1ListCatalogRequest) GetCursor() string`

GetCursor returns the Cursor field if non-nil, zero value otherwise.

### GetCursorOk

`func (o *SodacardsDevpublicV1ListCatalogRequest) GetCursorOk() (*string, bool)`

GetCursorOk returns a tuple with the Cursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursor

`func (o *SodacardsDevpublicV1ListCatalogRequest) SetCursor(v string)`

SetCursor sets Cursor field to given value.

### HasCursor

`func (o *SodacardsDevpublicV1ListCatalogRequest) HasCursor() bool`

HasCursor returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


