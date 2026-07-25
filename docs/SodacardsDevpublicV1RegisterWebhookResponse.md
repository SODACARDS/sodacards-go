# SodacardsDevpublicV1RegisterWebhookResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Webhook** | Pointer to [**SodacardsDevpublicV1Webhook**](SodacardsDevpublicV1Webhook.md) | webhook is the registered endpoint. | [optional] 
**Secret** | Pointer to **string** | secret is the signing secret, shown only once. Store it; verify each delivery  with it. It is never returned again. | [optional] 

## Methods

### NewSodacardsDevpublicV1RegisterWebhookResponse

`func NewSodacardsDevpublicV1RegisterWebhookResponse() *SodacardsDevpublicV1RegisterWebhookResponse`

NewSodacardsDevpublicV1RegisterWebhookResponse instantiates a new SodacardsDevpublicV1RegisterWebhookResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1RegisterWebhookResponseWithDefaults

`func NewSodacardsDevpublicV1RegisterWebhookResponseWithDefaults() *SodacardsDevpublicV1RegisterWebhookResponse`

NewSodacardsDevpublicV1RegisterWebhookResponseWithDefaults instantiates a new SodacardsDevpublicV1RegisterWebhookResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWebhook

`func (o *SodacardsDevpublicV1RegisterWebhookResponse) GetWebhook() SodacardsDevpublicV1Webhook`

GetWebhook returns the Webhook field if non-nil, zero value otherwise.

### GetWebhookOk

`func (o *SodacardsDevpublicV1RegisterWebhookResponse) GetWebhookOk() (*SodacardsDevpublicV1Webhook, bool)`

GetWebhookOk returns a tuple with the Webhook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhook

`func (o *SodacardsDevpublicV1RegisterWebhookResponse) SetWebhook(v SodacardsDevpublicV1Webhook)`

SetWebhook sets Webhook field to given value.

### HasWebhook

`func (o *SodacardsDevpublicV1RegisterWebhookResponse) HasWebhook() bool`

HasWebhook returns a boolean if a field has been set.

### GetSecret

`func (o *SodacardsDevpublicV1RegisterWebhookResponse) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *SodacardsDevpublicV1RegisterWebhookResponse) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *SodacardsDevpublicV1RegisterWebhookResponse) SetSecret(v string)`

SetSecret sets Secret field to given value.

### HasSecret

`func (o *SodacardsDevpublicV1RegisterWebhookResponse) HasSecret() bool`

HasSecret returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


