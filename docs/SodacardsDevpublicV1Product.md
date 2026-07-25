# SodacardsDevpublicV1Product

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | id identifies the product; use it to place an order for this item. | [optional] 
**Name** | Pointer to **string** | name is the human-readable product name. | [optional] 
**FaceValue** | Pointer to [**SodacardsDevpublicV1ProductFaceValue**](SodacardsDevpublicV1ProductFaceValue.md) | face_value is the nominal value printed on the item (e.g. a 10 USD card),  which may differ from the currency the reseller pays in. | [optional] 
**Price** | Pointer to [**SodacardsDevpublicV1Money**](SodacardsDevpublicV1Money.md) | price is what the reseller pays, in FCFA. It is absent when the item is not  yet priced (listed but not purchasable). | [optional] 
**StrikePrice** | Pointer to [**SodacardsDevpublicV1Money**](SodacardsDevpublicV1Money.md) | strike_price is an optional reference (pre-discount) price, in FCFA, for  display. Absent when there is none. | [optional] 
**Bonus** | Pointer to **string** | bonus describes any extra value granted with the item, e.g. \&quot;+10%\&quot;. Empty  when there is none. | [optional] 
**MinQuantity** | Pointer to **int32** | min_quantity and max_quantity bound how many units an order line may buy. | [optional] 
**MaxQuantity** | Pointer to **int32** |  | [optional] 
**Purchasable** | Pointer to **bool** | purchasable is true when the item has a price and can be ordered now. | [optional] 

## Methods

### NewSodacardsDevpublicV1Product

`func NewSodacardsDevpublicV1Product() *SodacardsDevpublicV1Product`

NewSodacardsDevpublicV1Product instantiates a new SodacardsDevpublicV1Product object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1ProductWithDefaults

`func NewSodacardsDevpublicV1ProductWithDefaults() *SodacardsDevpublicV1Product`

NewSodacardsDevpublicV1ProductWithDefaults instantiates a new SodacardsDevpublicV1Product object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SodacardsDevpublicV1Product) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SodacardsDevpublicV1Product) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SodacardsDevpublicV1Product) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SodacardsDevpublicV1Product) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *SodacardsDevpublicV1Product) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SodacardsDevpublicV1Product) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SodacardsDevpublicV1Product) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SodacardsDevpublicV1Product) HasName() bool`

HasName returns a boolean if a field has been set.

### GetFaceValue

`func (o *SodacardsDevpublicV1Product) GetFaceValue() SodacardsDevpublicV1ProductFaceValue`

GetFaceValue returns the FaceValue field if non-nil, zero value otherwise.

### GetFaceValueOk

`func (o *SodacardsDevpublicV1Product) GetFaceValueOk() (*SodacardsDevpublicV1ProductFaceValue, bool)`

GetFaceValueOk returns a tuple with the FaceValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFaceValue

`func (o *SodacardsDevpublicV1Product) SetFaceValue(v SodacardsDevpublicV1ProductFaceValue)`

SetFaceValue sets FaceValue field to given value.

### HasFaceValue

`func (o *SodacardsDevpublicV1Product) HasFaceValue() bool`

HasFaceValue returns a boolean if a field has been set.

### GetPrice

`func (o *SodacardsDevpublicV1Product) GetPrice() SodacardsDevpublicV1Money`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *SodacardsDevpublicV1Product) GetPriceOk() (*SodacardsDevpublicV1Money, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *SodacardsDevpublicV1Product) SetPrice(v SodacardsDevpublicV1Money)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *SodacardsDevpublicV1Product) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetStrikePrice

`func (o *SodacardsDevpublicV1Product) GetStrikePrice() SodacardsDevpublicV1Money`

GetStrikePrice returns the StrikePrice field if non-nil, zero value otherwise.

### GetStrikePriceOk

`func (o *SodacardsDevpublicV1Product) GetStrikePriceOk() (*SodacardsDevpublicV1Money, bool)`

GetStrikePriceOk returns a tuple with the StrikePrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStrikePrice

`func (o *SodacardsDevpublicV1Product) SetStrikePrice(v SodacardsDevpublicV1Money)`

SetStrikePrice sets StrikePrice field to given value.

### HasStrikePrice

`func (o *SodacardsDevpublicV1Product) HasStrikePrice() bool`

HasStrikePrice returns a boolean if a field has been set.

### GetBonus

`func (o *SodacardsDevpublicV1Product) GetBonus() string`

GetBonus returns the Bonus field if non-nil, zero value otherwise.

### GetBonusOk

`func (o *SodacardsDevpublicV1Product) GetBonusOk() (*string, bool)`

GetBonusOk returns a tuple with the Bonus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBonus

`func (o *SodacardsDevpublicV1Product) SetBonus(v string)`

SetBonus sets Bonus field to given value.

### HasBonus

`func (o *SodacardsDevpublicV1Product) HasBonus() bool`

HasBonus returns a boolean if a field has been set.

### GetMinQuantity

`func (o *SodacardsDevpublicV1Product) GetMinQuantity() int32`

GetMinQuantity returns the MinQuantity field if non-nil, zero value otherwise.

### GetMinQuantityOk

`func (o *SodacardsDevpublicV1Product) GetMinQuantityOk() (*int32, bool)`

GetMinQuantityOk returns a tuple with the MinQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinQuantity

`func (o *SodacardsDevpublicV1Product) SetMinQuantity(v int32)`

SetMinQuantity sets MinQuantity field to given value.

### HasMinQuantity

`func (o *SodacardsDevpublicV1Product) HasMinQuantity() bool`

HasMinQuantity returns a boolean if a field has been set.

### GetMaxQuantity

`func (o *SodacardsDevpublicV1Product) GetMaxQuantity() int32`

GetMaxQuantity returns the MaxQuantity field if non-nil, zero value otherwise.

### GetMaxQuantityOk

`func (o *SodacardsDevpublicV1Product) GetMaxQuantityOk() (*int32, bool)`

GetMaxQuantityOk returns a tuple with the MaxQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxQuantity

`func (o *SodacardsDevpublicV1Product) SetMaxQuantity(v int32)`

SetMaxQuantity sets MaxQuantity field to given value.

### HasMaxQuantity

`func (o *SodacardsDevpublicV1Product) HasMaxQuantity() bool`

HasMaxQuantity returns a boolean if a field has been set.

### GetPurchasable

`func (o *SodacardsDevpublicV1Product) GetPurchasable() bool`

GetPurchasable returns the Purchasable field if non-nil, zero value otherwise.

### GetPurchasableOk

`func (o *SodacardsDevpublicV1Product) GetPurchasableOk() (*bool, bool)`

GetPurchasableOk returns a tuple with the Purchasable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchasable

`func (o *SodacardsDevpublicV1Product) SetPurchasable(v bool)`

SetPurchasable sets Purchasable field to given value.

### HasPurchasable

`func (o *SodacardsDevpublicV1Product) HasPurchasable() bool`

HasPurchasable returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


