# SodacardsDevpublicV1InputFieldOption

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | Pointer to **string** | value is what to submit on OrderLine.input_fields for this option. | [optional] 
**Label** | Pointer to **string** | label is the human-readable display for the option. | [optional] 
**ParentValue** | Pointer to **string** | parent_value gates a cascading option: the value of the parent field&#39;s option  that must be selected for this option to apply (e.g. a server option gated by  the chosen region). Empty when the option is not part of a cascade. | [optional] 

## Methods

### NewSodacardsDevpublicV1InputFieldOption

`func NewSodacardsDevpublicV1InputFieldOption() *SodacardsDevpublicV1InputFieldOption`

NewSodacardsDevpublicV1InputFieldOption instantiates a new SodacardsDevpublicV1InputFieldOption object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSodacardsDevpublicV1InputFieldOptionWithDefaults

`func NewSodacardsDevpublicV1InputFieldOptionWithDefaults() *SodacardsDevpublicV1InputFieldOption`

NewSodacardsDevpublicV1InputFieldOptionWithDefaults instantiates a new SodacardsDevpublicV1InputFieldOption object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValue

`func (o *SodacardsDevpublicV1InputFieldOption) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *SodacardsDevpublicV1InputFieldOption) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *SodacardsDevpublicV1InputFieldOption) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *SodacardsDevpublicV1InputFieldOption) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetLabel

`func (o *SodacardsDevpublicV1InputFieldOption) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *SodacardsDevpublicV1InputFieldOption) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *SodacardsDevpublicV1InputFieldOption) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *SodacardsDevpublicV1InputFieldOption) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetParentValue

`func (o *SodacardsDevpublicV1InputFieldOption) GetParentValue() string`

GetParentValue returns the ParentValue field if non-nil, zero value otherwise.

### GetParentValueOk

`func (o *SodacardsDevpublicV1InputFieldOption) GetParentValueOk() (*string, bool)`

GetParentValueOk returns a tuple with the ParentValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentValue

`func (o *SodacardsDevpublicV1InputFieldOption) SetParentValue(v string)`

SetParentValue sets ParentValue field to given value.

### HasParentValue

`func (o *SodacardsDevpublicV1InputFieldOption) HasParentValue() bool`

HasParentValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


