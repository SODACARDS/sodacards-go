# SodacardsDevpublicV1OrderItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductId** | Pointer to **string** | product_id is the product ordered on this line. | [optional] 
**Name** | Pointer to **string** | name is the product name at order time. | [optional] 
**UnitPrice** | Pointer to [**SodacardsDevpublicV1Money**](SodacardsDevpublicV1Money.md) | unit_price is the price of one unit, in FCFA. | [optional] 
**Quantity** | Pointer to **int32** | quantity is how many units were ordered. | [optional] 
**LineTotal** | Pointer to [**SodacardsDevpublicV1Money**](SodacardsDevpublicV1Money.md) | line_total is unit_price times quantity, in FCFA. | [optional] 
**InputFields** | Pointer to **map[string]string** | input_fields are the purchase-form values submitted for this line. | [optional] 

## Methods

### NewSodacardsDevpublicV1OrderItem

`func NewSodacardsDevpublicV1OrderItem() *SodacardsDevpublicV1OrderItem`

NewSodacardsDevpublicV1OrderItem instantiates a new SodacardsDevpublicV1OrderItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1OrderItemWithDefaults

`func NewSodacardsDevpublicV1OrderItemWithDefaults() *SodacardsDevpublicV1OrderItem`

NewSodacardsDevpublicV1OrderItemWithDefaults instantiates a new SodacardsDevpublicV1OrderItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductId

`func (o *SodacardsDevpublicV1OrderItem) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *SodacardsDevpublicV1OrderItem) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *SodacardsDevpublicV1OrderItem) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *SodacardsDevpublicV1OrderItem) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### GetName

`func (o *SodacardsDevpublicV1OrderItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SodacardsDevpublicV1OrderItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SodacardsDevpublicV1OrderItem) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SodacardsDevpublicV1OrderItem) HasName() bool`

HasName returns a boolean if a field has been set.

### GetUnitPrice

`func (o *SodacardsDevpublicV1OrderItem) GetUnitPrice() SodacardsDevpublicV1Money`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *SodacardsDevpublicV1OrderItem) GetUnitPriceOk() (*SodacardsDevpublicV1Money, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *SodacardsDevpublicV1OrderItem) SetUnitPrice(v SodacardsDevpublicV1Money)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *SodacardsDevpublicV1OrderItem) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetQuantity

`func (o *SodacardsDevpublicV1OrderItem) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *SodacardsDevpublicV1OrderItem) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *SodacardsDevpublicV1OrderItem) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *SodacardsDevpublicV1OrderItem) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetLineTotal

`func (o *SodacardsDevpublicV1OrderItem) GetLineTotal() SodacardsDevpublicV1Money`

GetLineTotal returns the LineTotal field if non-nil, zero value otherwise.

### GetLineTotalOk

`func (o *SodacardsDevpublicV1OrderItem) GetLineTotalOk() (*SodacardsDevpublicV1Money, bool)`

GetLineTotalOk returns a tuple with the LineTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineTotal

`func (o *SodacardsDevpublicV1OrderItem) SetLineTotal(v SodacardsDevpublicV1Money)`

SetLineTotal sets LineTotal field to given value.

### HasLineTotal

`func (o *SodacardsDevpublicV1OrderItem) HasLineTotal() bool`

HasLineTotal returns a boolean if a field has been set.

### GetInputFields

`func (o *SodacardsDevpublicV1OrderItem) GetInputFields() map[string]string`

GetInputFields returns the InputFields field if non-nil, zero value otherwise.

### GetInputFieldsOk

`func (o *SodacardsDevpublicV1OrderItem) GetInputFieldsOk() (*map[string]string, bool)`

GetInputFieldsOk returns a tuple with the InputFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputFields

`func (o *SodacardsDevpublicV1OrderItem) SetInputFields(v map[string]string)`

SetInputFields sets InputFields field to given value.

### HasInputFields

`func (o *SodacardsDevpublicV1OrderItem) HasInputFields() bool`

HasInputFields returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


