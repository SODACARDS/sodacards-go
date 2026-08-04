# SodacardsDevpublicV1RotateWebhookSecretResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Secret** | Pointer to **string** | secret is the new signing secret, shown only once, like at registration. | [optional] 
**PrevSecretExpiresAt** | Pointer to **string** | prev_secret_expires_at is when the previous secret stops being accepted  (RFC 3339). Until then both secrets validate a delivery. | [optional] 

## Methods

### NewSodacardsDevpublicV1RotateWebhookSecretResponse

`func NewSodacardsDevpublicV1RotateWebhookSecretResponse() *SodacardsDevpublicV1RotateWebhookSecretResponse`

NewSodacardsDevpublicV1RotateWebhookSecretResponse instantiates a new SodacardsDevpublicV1RotateWebhookSecretResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1RotateWebhookSecretResponseWithDefaults

`func NewSodacardsDevpublicV1RotateWebhookSecretResponseWithDefaults() *SodacardsDevpublicV1RotateWebhookSecretResponse`

NewSodacardsDevpublicV1RotateWebhookSecretResponseWithDefaults instantiates a new SodacardsDevpublicV1RotateWebhookSecretResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSecret

`func (o *SodacardsDevpublicV1RotateWebhookSecretResponse) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *SodacardsDevpublicV1RotateWebhookSecretResponse) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *SodacardsDevpublicV1RotateWebhookSecretResponse) SetSecret(v string)`

SetSecret sets Secret field to given value.

### HasSecret

`func (o *SodacardsDevpublicV1RotateWebhookSecretResponse) HasSecret() bool`

HasSecret returns a boolean if a field has been set.

### GetPrevSecretExpiresAt

`func (o *SodacardsDevpublicV1RotateWebhookSecretResponse) GetPrevSecretExpiresAt() string`

GetPrevSecretExpiresAt returns the PrevSecretExpiresAt field if non-nil, zero value otherwise.

### GetPrevSecretExpiresAtOk

`func (o *SodacardsDevpublicV1RotateWebhookSecretResponse) GetPrevSecretExpiresAtOk() (*string, bool)`

GetPrevSecretExpiresAtOk returns a tuple with the PrevSecretExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevSecretExpiresAt

`func (o *SodacardsDevpublicV1RotateWebhookSecretResponse) SetPrevSecretExpiresAt(v string)`

SetPrevSecretExpiresAt sets PrevSecretExpiresAt field to given value.

### HasPrevSecretExpiresAt

`func (o *SodacardsDevpublicV1RotateWebhookSecretResponse) HasPrevSecretExpiresAt() bool`

HasPrevSecretExpiresAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


