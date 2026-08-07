# SodacardsDevpublicV1PlaceOrderResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to [**SodacardsDevpublicV1PlacedOrder**](SodacardsDevpublicV1PlacedOrder.md) | order is the accepted order. It is settled from the wallet at placement, so it  is born already paid: its status is \&quot;processing\&quot; while it is being fulfilled,  or \&quot;completed\&quot; when fulfillment is immediate. It is never \&quot;pending\&quot; -- the  developer API charges synchronously, so an order awaiting payment is not a  state it produces. Poll the order to follow it to \&quot;completed\&quot;. | [optional] 

## Methods

### NewSodacardsDevpublicV1PlaceOrderResponse

`func NewSodacardsDevpublicV1PlaceOrderResponse() *SodacardsDevpublicV1PlaceOrderResponse`

NewSodacardsDevpublicV1PlaceOrderResponse instantiates a new SodacardsDevpublicV1PlaceOrderResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1PlaceOrderResponseWithDefaults

`func NewSodacardsDevpublicV1PlaceOrderResponseWithDefaults() *SodacardsDevpublicV1PlaceOrderResponse`

NewSodacardsDevpublicV1PlaceOrderResponseWithDefaults instantiates a new SodacardsDevpublicV1PlaceOrderResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *SodacardsDevpublicV1PlaceOrderResponse) GetOrder() SodacardsDevpublicV1PlacedOrder`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *SodacardsDevpublicV1PlaceOrderResponse) GetOrderOk() (*SodacardsDevpublicV1PlacedOrder, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *SodacardsDevpublicV1PlaceOrderResponse) SetOrder(v SodacardsDevpublicV1PlacedOrder)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *SodacardsDevpublicV1PlaceOrderResponse) HasOrder() bool`

HasOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


