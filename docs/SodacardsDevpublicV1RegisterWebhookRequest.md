# SodacardsDevpublicV1RegisterWebhookRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | Pointer to **string** | url is the HTTPS endpoint to deliver events to. | [optional] 
**Events** | Pointer to **[]string** | events are the event types to subscribe to (at least one), e.g.  \&quot;order.fulfilled\&quot;, \&quot;order.needs_attention\&quot;, \&quot;order.refunded\&quot;, \&quot;wallet.low_balance\&quot;,  \&quot;wallet.credited\&quot;. | [optional] 

## Methods

### NewSodacardsDevpublicV1RegisterWebhookRequest

`func NewSodacardsDevpublicV1RegisterWebhookRequest() *SodacardsDevpublicV1RegisterWebhookRequest`

NewSodacardsDevpublicV1RegisterWebhookRequest instantiates a new SodacardsDevpublicV1RegisterWebhookRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1RegisterWebhookRequestWithDefaults

`func NewSodacardsDevpublicV1RegisterWebhookRequestWithDefaults() *SodacardsDevpublicV1RegisterWebhookRequest`

NewSodacardsDevpublicV1RegisterWebhookRequestWithDefaults instantiates a new SodacardsDevpublicV1RegisterWebhookRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *SodacardsDevpublicV1RegisterWebhookRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *SodacardsDevpublicV1RegisterWebhookRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *SodacardsDevpublicV1RegisterWebhookRequest) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *SodacardsDevpublicV1RegisterWebhookRequest) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetEvents

`func (o *SodacardsDevpublicV1RegisterWebhookRequest) GetEvents() []string`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *SodacardsDevpublicV1RegisterWebhookRequest) GetEventsOk() (*[]string, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *SodacardsDevpublicV1RegisterWebhookRequest) SetEvents(v []string)`

SetEvents sets Events field to given value.

### HasEvents

`func (o *SodacardsDevpublicV1RegisterWebhookRequest) HasEvents() bool`

HasEvents returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


