# SodacardsDevpublicV1InputFieldSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | Pointer to **string** | key is the field&#39;s machine name and the key to use in  OrderLine.input_fields, e.g. \&quot;player_id\&quot;. | [optional] 
**Type** | Pointer to **string** | type is how to render and validate the value: \&quot;text\&quot;, \&quot;number\&quot; or \&quot;select\&quot;. | [optional] 
**Required** | Pointer to **bool** | required is true when an order line for this product must carry this field. | [optional] 
**Regex** | Pointer to **string** | regex, when present, is a regular expression the submitted value must match  (text and number fields). Empty when there is no pattern constraint. | [optional] 
**Options** | Pointer to [**[]SodacardsDevpublicV1InputFieldOption**](SodacardsDevpublicV1InputFieldOption.md) | options are the allowed values of a \&quot;select\&quot; field, in display order. Empty  for text and number fields. | [optional] 

## Methods

### NewSodacardsDevpublicV1InputFieldSpec

`func NewSodacardsDevpublicV1InputFieldSpec() *SodacardsDevpublicV1InputFieldSpec`

NewSodacardsDevpublicV1InputFieldSpec instantiates a new SodacardsDevpublicV1InputFieldSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1InputFieldSpecWithDefaults

`func NewSodacardsDevpublicV1InputFieldSpecWithDefaults() *SodacardsDevpublicV1InputFieldSpec`

NewSodacardsDevpublicV1InputFieldSpecWithDefaults instantiates a new SodacardsDevpublicV1InputFieldSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *SodacardsDevpublicV1InputFieldSpec) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *SodacardsDevpublicV1InputFieldSpec) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *SodacardsDevpublicV1InputFieldSpec) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *SodacardsDevpublicV1InputFieldSpec) HasKey() bool`

HasKey returns a boolean if a field has been set.

### GetType

`func (o *SodacardsDevpublicV1InputFieldSpec) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SodacardsDevpublicV1InputFieldSpec) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SodacardsDevpublicV1InputFieldSpec) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SodacardsDevpublicV1InputFieldSpec) HasType() bool`

HasType returns a boolean if a field has been set.

### GetRequired

`func (o *SodacardsDevpublicV1InputFieldSpec) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *SodacardsDevpublicV1InputFieldSpec) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *SodacardsDevpublicV1InputFieldSpec) SetRequired(v bool)`

SetRequired sets Required field to given value.

### HasRequired

`func (o *SodacardsDevpublicV1InputFieldSpec) HasRequired() bool`

HasRequired returns a boolean if a field has been set.

### GetRegex

`func (o *SodacardsDevpublicV1InputFieldSpec) GetRegex() string`

GetRegex returns the Regex field if non-nil, zero value otherwise.

### GetRegexOk

`func (o *SodacardsDevpublicV1InputFieldSpec) GetRegexOk() (*string, bool)`

GetRegexOk returns a tuple with the Regex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegex

`func (o *SodacardsDevpublicV1InputFieldSpec) SetRegex(v string)`

SetRegex sets Regex field to given value.

### HasRegex

`func (o *SodacardsDevpublicV1InputFieldSpec) HasRegex() bool`

HasRegex returns a boolean if a field has been set.

### GetOptions

`func (o *SodacardsDevpublicV1InputFieldSpec) GetOptions() []SodacardsDevpublicV1InputFieldOption`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *SodacardsDevpublicV1InputFieldSpec) GetOptionsOk() (*[]SodacardsDevpublicV1InputFieldOption, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *SodacardsDevpublicV1InputFieldSpec) SetOptions(v []SodacardsDevpublicV1InputFieldOption)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *SodacardsDevpublicV1InputFieldSpec) HasOptions() bool`

HasOptions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


