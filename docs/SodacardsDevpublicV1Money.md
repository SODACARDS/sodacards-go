# SodacardsDevpublicV1Money

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | Pointer to [**Amount**](Amount.md) |  | [optional] 
**Currency** | Pointer to **string** | currency is the ISO-4217 code, e.g. \&quot;XOF\&quot;. | [optional] 

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


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


