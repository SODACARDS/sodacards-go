# SodacardsDevpublicV1Webhook

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | id identifies the endpoint. | [optional] 
**Url** | Pointer to **string** | url is the HTTPS endpoint events are delivered to. | [optional] 
**Events** | Pointer to **[]string** | events are the subscribed event types. | [optional] 
**Active** | Pointer to **bool** | active is whether deliveries are currently sent to this endpoint. | [optional] 
**CreatedAt** | Pointer to **string** | created_at is when the endpoint was registered (RFC 3339). | [optional] 

## Methods

### NewSodacardsDevpublicV1Webhook

`func NewSodacardsDevpublicV1Webhook() *SodacardsDevpublicV1Webhook`

NewSodacardsDevpublicV1Webhook instantiates a new SodacardsDevpublicV1Webhook object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1WebhookWithDefaults

`func NewSodacardsDevpublicV1WebhookWithDefaults() *SodacardsDevpublicV1Webhook`

NewSodacardsDevpublicV1WebhookWithDefaults instantiates a new SodacardsDevpublicV1Webhook object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SodacardsDevpublicV1Webhook) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SodacardsDevpublicV1Webhook) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SodacardsDevpublicV1Webhook) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SodacardsDevpublicV1Webhook) HasId() bool`

HasId returns a boolean if a field has been set.

### GetUrl

`func (o *SodacardsDevpublicV1Webhook) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *SodacardsDevpublicV1Webhook) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *SodacardsDevpublicV1Webhook) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *SodacardsDevpublicV1Webhook) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetEvents

`func (o *SodacardsDevpublicV1Webhook) GetEvents() []string`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *SodacardsDevpublicV1Webhook) GetEventsOk() (*[]string, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *SodacardsDevpublicV1Webhook) SetEvents(v []string)`

SetEvents sets Events field to given value.

### HasEvents

`func (o *SodacardsDevpublicV1Webhook) HasEvents() bool`

HasEvents returns a boolean if a field has been set.

### GetActive

`func (o *SodacardsDevpublicV1Webhook) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *SodacardsDevpublicV1Webhook) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *SodacardsDevpublicV1Webhook) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *SodacardsDevpublicV1Webhook) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCreatedAt

`func (o *SodacardsDevpublicV1Webhook) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SodacardsDevpublicV1Webhook) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SodacardsDevpublicV1Webhook) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *SodacardsDevpublicV1Webhook) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


