# SodacardsDevpublicV1Money

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | Pointer to [**Amount**](Amount.md) |  | [optional] 
**Currency** | Pointer to **string** | currency is the ISO-4217 code, e.g. \&quot;XOF\&quot;. | [optional] 
**MinorUnitExponent** | Pointer to **int32** | minor_unit_exponent is the currency&#39;s number of decimal places (0 for XOF,  2 for USD): amount divided by 10^minor_unit_exponent is the major-unit value. | [optional] 

## Methods

### NewSodacardsDevpublicV1Money

`func NewSodacardsDevpublicV1Money() *SodacardsDevpublicV1Money`

NewSodacardsDevpublicV1Money instantiates a new SodacardsDevpublicV1Money object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1MoneyWithDefaults

`func NewSodacardsDevpublicV1MoneyWithDefaults() *SodacardsDevpublicV1Money`

NewSodacardsDevpublicV1MoneyWithDefaults instantiates a new SodacardsDevpublicV1Money object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *SodacardsDevpublicV1Money) GetAmount() Amount`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *SodacardsDevpublicV1Money) GetAmountOk() (*Amount, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *SodacardsDevpublicV1Money) SetAmount(v Amount)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *SodacardsDevpublicV1Money) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCurrency

`func (o *SodacardsDevpublicV1Money) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SodacardsDevpublicV1Money) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SodacardsDevpublicV1Money) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *SodacardsDevpublicV1Money) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetMinorUnitExponent

`func (o *SodacardsDevpublicV1Money) GetMinorUnitExponent() int32`

GetMinorUnitExponent returns the MinorUnitExponent field if non-nil, zero value otherwise.

### GetMinorUnitExponentOk

`func (o *SodacardsDevpublicV1Money) GetMinorUnitExponentOk() (*int32, bool)`

GetMinorUnitExponentOk returns a tuple with the MinorUnitExponent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinorUnitExponent

`func (o *SodacardsDevpublicV1Money) SetMinorUnitExponent(v int32)`

SetMinorUnitExponent sets MinorUnitExponent field to given value.

### HasMinorUnitExponent

`func (o *SodacardsDevpublicV1Money) HasMinorUnitExponent() bool`

HasMinorUnitExponent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


