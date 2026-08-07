# Problem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | A stable URI identifying the error kind; it resolves to the docs section for that code. | 
**Title** | **string** | A short, human-readable summary of the error kind. | 
**Status** | **int32** | The HTTP status code, repeated in the body for convenience. | 
**Code** | **string** | The machine-readable reason (e.g. \&quot;insufficient_balance\&quot;): switch on this, never on the human text. | 
**Detail** | Pointer to **string** | A human-readable explanation of this specific occurrence. May be absent. | [optional] 
**RequestId** | Pointer to **string** | Identifies this request in support conversations. May be absent. | [optional] 

## Methods

### NewProblem

`func NewProblem(type_ string, title string, status int32, code string, ) *Problem`

NewProblem instantiates a new Problem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProblemWithDefaults

`func NewProblemWithDefaults() *Problem`

NewProblemWithDefaults instantiates a new Problem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *Problem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Problem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Problem) SetType(v string)`

SetType sets Type field to given value.


### GetTitle

`func (o *Problem) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Problem) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Problem) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetStatus

`func (o *Problem) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Problem) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Problem) SetStatus(v int32)`

SetStatus sets Status field to given value.


### GetCode

`func (o *Problem) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *Problem) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *Problem) SetCode(v string)`

SetCode sets Code field to given value.


### GetDetail

`func (o *Problem) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *Problem) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *Problem) SetDetail(v string)`

SetDetail sets Detail field to given value.

### HasDetail

`func (o *Problem) HasDetail() bool`

HasDetail returns a boolean if a field has been set.

### GetRequestId

`func (o *Problem) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *Problem) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *Problem) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *Problem) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


