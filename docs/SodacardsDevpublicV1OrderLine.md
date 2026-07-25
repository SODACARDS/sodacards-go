# SodacardsDevpublicV1OrderLine

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductId** | Pointer to **string** | product_id is the id of the product to buy (a catalog product id). | [optional] 
**Quantity** | Pointer to **int32** | quantity is how many units to buy on this line (at least one). | [optional] 
**InputFields** | Pointer to **map[string]string** | input_fields holds the required purchase-form values, keyed by field name. | [optional] 

## Methods

### NewSodacardsDevpublicV1OrderLine

`func NewSodacardsDevpublicV1OrderLine() *SodacardsDevpublicV1OrderLine`

NewSodacardsDevpublicV1OrderLine instantiates a new SodacardsDevpublicV1OrderLine object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1OrderLineWithDefaults

`func NewSodacardsDevpublicV1OrderLineWithDefaults() *SodacardsDevpublicV1OrderLine`

NewSodacardsDevpublicV1OrderLineWithDefaults instantiates a new SodacardsDevpublicV1OrderLine object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductId

`func (o *SodacardsDevpublicV1OrderLine) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *SodacardsDevpublicV1OrderLine) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *SodacardsDevpublicV1OrderLine) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *SodacardsDevpublicV1OrderLine) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### GetQuantity

`func (o *SodacardsDevpublicV1OrderLine) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *SodacardsDevpublicV1OrderLine) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *SodacardsDevpublicV1OrderLine) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *SodacardsDevpublicV1OrderLine) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetInputFields

`func (o *SodacardsDevpublicV1OrderLine) GetInputFields() map[string]string`

GetInputFields returns the InputFields field if non-nil, zero value otherwise.

### GetInputFieldsOk

`func (o *SodacardsDevpublicV1OrderLine) GetInputFieldsOk() (*map[string]string, bool)`

GetInputFieldsOk returns a tuple with the InputFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputFields

`func (o *SodacardsDevpublicV1OrderLine) SetInputFields(v map[string]string)`

SetInputFields sets InputFields field to given value.

### HasInputFields

`func (o *SodacardsDevpublicV1OrderLine) HasInputFields() bool`

HasInputFields returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


