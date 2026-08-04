# SodacardsDevpublicV1GetBalanceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Balance** | Pointer to [**SodacardsDevpublicV1Money**](SodacardsDevpublicV1Money.md) | balance is the reseller&#39;s prepaid wallet balance. For a test key it is a  fixed sandbox value, clearly not the production wallet. | [optional] 

## Methods

### NewSodacardsDevpublicV1GetBalanceResponse

`func NewSodacardsDevpublicV1GetBalanceResponse() *SodacardsDevpublicV1GetBalanceResponse`

NewSodacardsDevpublicV1GetBalanceResponse instantiates a new SodacardsDevpublicV1GetBalanceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1GetBalanceResponseWithDefaults

`func NewSodacardsDevpublicV1GetBalanceResponseWithDefaults() *SodacardsDevpublicV1GetBalanceResponse`

NewSodacardsDevpublicV1GetBalanceResponseWithDefaults instantiates a new SodacardsDevpublicV1GetBalanceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBalance

`func (o *SodacardsDevpublicV1GetBalanceResponse) GetBalance() SodacardsDevpublicV1Money`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *SodacardsDevpublicV1GetBalanceResponse) GetBalanceOk() (*SodacardsDevpublicV1Money, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *SodacardsDevpublicV1GetBalanceResponse) SetBalance(v SodacardsDevpublicV1Money)`

SetBalance sets Balance field to given value.

### HasBalance

`func (o *SodacardsDevpublicV1GetBalanceResponse) HasBalance() bool`

HasBalance returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


