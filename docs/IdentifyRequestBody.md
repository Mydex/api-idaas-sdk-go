# IdentifyRequestBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectionNid** | **string** | The connection NID | 
**ConnectionTokenHash** | **string** | The hashed connection token | 
**ReturnTo** | **string** | The URL to return to after identification | 
**LinkingToken** | Pointer to **NullableString** | A unique ID representing the member in the subscriber&#39;s backend | [optional] 

## Methods

### NewIdentifyRequestBody

`func NewIdentifyRequestBody(connectionNid string, connectionTokenHash string, returnTo string, ) *IdentifyRequestBody`

NewIdentifyRequestBody instantiates a new IdentifyRequestBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdentifyRequestBodyWithDefaults

`func NewIdentifyRequestBodyWithDefaults() *IdentifyRequestBody`

NewIdentifyRequestBodyWithDefaults instantiates a new IdentifyRequestBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectionNid

`func (o *IdentifyRequestBody) GetConnectionNid() string`

GetConnectionNid returns the ConnectionNid field if non-nil, zero value otherwise.

### GetConnectionNidOk

`func (o *IdentifyRequestBody) GetConnectionNidOk() (*string, bool)`

GetConnectionNidOk returns a tuple with the ConnectionNid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionNid

`func (o *IdentifyRequestBody) SetConnectionNid(v string)`

SetConnectionNid sets ConnectionNid field to given value.


### GetConnectionTokenHash

`func (o *IdentifyRequestBody) GetConnectionTokenHash() string`

GetConnectionTokenHash returns the ConnectionTokenHash field if non-nil, zero value otherwise.

### GetConnectionTokenHashOk

`func (o *IdentifyRequestBody) GetConnectionTokenHashOk() (*string, bool)`

GetConnectionTokenHashOk returns a tuple with the ConnectionTokenHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionTokenHash

`func (o *IdentifyRequestBody) SetConnectionTokenHash(v string)`

SetConnectionTokenHash sets ConnectionTokenHash field to given value.


### GetReturnTo

`func (o *IdentifyRequestBody) GetReturnTo() string`

GetReturnTo returns the ReturnTo field if non-nil, zero value otherwise.

### GetReturnToOk

`func (o *IdentifyRequestBody) GetReturnToOk() (*string, bool)`

GetReturnToOk returns a tuple with the ReturnTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnTo

`func (o *IdentifyRequestBody) SetReturnTo(v string)`

SetReturnTo sets ReturnTo field to given value.


### GetLinkingToken

`func (o *IdentifyRequestBody) GetLinkingToken() string`

GetLinkingToken returns the LinkingToken field if non-nil, zero value otherwise.

### GetLinkingTokenOk

`func (o *IdentifyRequestBody) GetLinkingTokenOk() (*string, bool)`

GetLinkingTokenOk returns a tuple with the LinkingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkingToken

`func (o *IdentifyRequestBody) SetLinkingToken(v string)`

SetLinkingToken sets LinkingToken field to given value.

### HasLinkingToken

`func (o *IdentifyRequestBody) HasLinkingToken() bool`

HasLinkingToken returns a boolean if a field has been set.

### SetLinkingTokenNil

`func (o *IdentifyRequestBody) SetLinkingTokenNil(b bool)`

 SetLinkingTokenNil sets the value for LinkingToken to be an explicit nil

### UnsetLinkingToken
`func (o *IdentifyRequestBody) UnsetLinkingToken()`

UnsetLinkingToken ensures that no value is present for LinkingToken, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


