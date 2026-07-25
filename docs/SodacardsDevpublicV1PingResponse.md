# SodacardsDevpublicV1PingResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** | status is \&quot;ok\&quot; when the key authenticated. | [optional] 
**Environment** | Pointer to **string** | environment is \&quot;live\&quot; or \&quot;test\&quot;, so a developer sees which mode their key is  in. | [optional] 
**ResellerId** | Pointer to **string** | reseller_id is the account the key belongs to. | [optional] 

## Methods

### NewSodacardsDevpublicV1PingResponse

`func NewSodacardsDevpublicV1PingResponse() *SodacardsDevpublicV1PingResponse`

NewSodacardsDevpublicV1PingResponse instantiates a new SodacardsDevpublicV1PingResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1PingResponseWithDefaults

`func NewSodacardsDevpublicV1PingResponseWithDefaults() *SodacardsDevpublicV1PingResponse`

NewSodacardsDevpublicV1PingResponseWithDefaults instantiates a new SodacardsDevpublicV1PingResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *SodacardsDevpublicV1PingResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SodacardsDevpublicV1PingResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SodacardsDevpublicV1PingResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SodacardsDevpublicV1PingResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetEnvironment

`func (o *SodacardsDevpublicV1PingResponse) GetEnvironment() string`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *SodacardsDevpublicV1PingResponse) GetEnvironmentOk() (*string, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *SodacardsDevpublicV1PingResponse) SetEnvironment(v string)`

SetEnvironment sets Environment field to given value.

### HasEnvironment

`func (o *SodacardsDevpublicV1PingResponse) HasEnvironment() bool`

HasEnvironment returns a boolean if a field has been set.

### GetResellerId

`func (o *SodacardsDevpublicV1PingResponse) GetResellerId() string`

GetResellerId returns the ResellerId field if non-nil, zero value otherwise.

### GetResellerIdOk

`func (o *SodacardsDevpublicV1PingResponse) GetResellerIdOk() (*string, bool)`

GetResellerIdOk returns a tuple with the ResellerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResellerId

`func (o *SodacardsDevpublicV1PingResponse) SetResellerId(v string)`

SetResellerId sets ResellerId field to given value.

### HasResellerId

`func (o *SodacardsDevpublicV1PingResponse) HasResellerId() bool`

HasResellerId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


