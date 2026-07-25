# SodacardsDevpublicV1PlacedOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | id identifies the order; use it to poll the order and reveal its codes. | [optional] 
**Status** | Pointer to **string** | status is the order&#39;s current state, e.g. \&quot;pending\&quot;, \&quot;processing\&quot;,  \&quot;completed\&quot;, \&quot;partially_completed\&quot;, \&quot;failed\&quot; or \&quot;refunded\&quot;. | [optional] 
**Total** | Pointer to [**SodacardsDevpublicV1Money**](SodacardsDevpublicV1Money.md) | total is the amount charged to the reseller&#39;s wallet, in FCFA. | [optional] 

## Methods

### NewSodacardsDevpublicV1PlacedOrder

`func NewSodacardsDevpublicV1PlacedOrder() *SodacardsDevpublicV1PlacedOrder`

NewSodacardsDevpublicV1PlacedOrder instantiates a new SodacardsDevpublicV1PlacedOrder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1PlacedOrderWithDefaults

`func NewSodacardsDevpublicV1PlacedOrderWithDefaults() *SodacardsDevpublicV1PlacedOrder`

NewSodacardsDevpublicV1PlacedOrderWithDefaults instantiates a new SodacardsDevpublicV1PlacedOrder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SodacardsDevpublicV1PlacedOrder) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SodacardsDevpublicV1PlacedOrder) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SodacardsDevpublicV1PlacedOrder) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SodacardsDevpublicV1PlacedOrder) HasId() bool`

HasId returns a boolean if a field has been set.

### GetStatus

`func (o *SodacardsDevpublicV1PlacedOrder) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SodacardsDevpublicV1PlacedOrder) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SodacardsDevpublicV1PlacedOrder) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SodacardsDevpublicV1PlacedOrder) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTotal

`func (o *SodacardsDevpublicV1PlacedOrder) GetTotal() SodacardsDevpublicV1Money`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *SodacardsDevpublicV1PlacedOrder) GetTotalOk() (*SodacardsDevpublicV1Money, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *SodacardsDevpublicV1PlacedOrder) SetTotal(v SodacardsDevpublicV1Money)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *SodacardsDevpublicV1PlacedOrder) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


