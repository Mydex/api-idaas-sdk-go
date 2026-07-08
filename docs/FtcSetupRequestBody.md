# FtcSetupRequestBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectionNid** | **string** | The connection NID | 
**ConnectionTokenHash** | **string** | The hashed connection token | 
**ReturnTo** | **string** | The URL to return to after connection | 
**Mydexid** | Pointer to **NullableString** | The MydexID if already known (required if version &gt; 1) | [optional] 
**Version** | Pointer to **int32** | The connection version (default 1, must be &gt;&#x3D; 1) | [optional] 
**LinkingToken** | Pointer to **NullableString** | A unique ID representing the member in the subscriber&#39;s backend | [optional] 

## Methods

### NewFtcSetupRequestBody

`func NewFtcSetupRequestBody(connectionNid string, connectionTokenHash string, returnTo string, ) *FtcSetupRequestBody`

NewFtcSetupRequestBody instantiates a new FtcSetupRequestBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFtcSetupRequestBodyWithDefaults

`func NewFtcSetupRequestBodyWithDefaults() *FtcSetupRequestBody`

NewFtcSetupRequestBodyWithDefaults instantiates a new FtcSetupRequestBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectionNid

`func (o *FtcSetupRequestBody) GetConnectionNid() string`

GetConnectionNid returns the ConnectionNid field if non-nil, zero value otherwise.

### GetConnectionNidOk

`func (o *FtcSetupRequestBody) GetConnectionNidOk() (*string, bool)`

GetConnectionNidOk returns a tuple with the ConnectionNid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionNid

`func (o *FtcSetupRequestBody) SetConnectionNid(v string)`

SetConnectionNid sets ConnectionNid field to given value.


### GetConnectionTokenHash

`func (o *FtcSetupRequestBody) GetConnectionTokenHash() string`

GetConnectionTokenHash returns the ConnectionTokenHash field if non-nil, zero value otherwise.

### GetConnectionTokenHashOk

`func (o *FtcSetupRequestBody) GetConnectionTokenHashOk() (*string, bool)`

GetConnectionTokenHashOk returns a tuple with the ConnectionTokenHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionTokenHash

`func (o *FtcSetupRequestBody) SetConnectionTokenHash(v string)`

SetConnectionTokenHash sets ConnectionTokenHash field to given value.


### GetReturnTo

`func (o *FtcSetupRequestBody) GetReturnTo() string`

GetReturnTo returns the ReturnTo field if non-nil, zero value otherwise.

### GetReturnToOk

`func (o *FtcSetupRequestBody) GetReturnToOk() (*string, bool)`

GetReturnToOk returns a tuple with the ReturnTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnTo

`func (o *FtcSetupRequestBody) SetReturnTo(v string)`

SetReturnTo sets ReturnTo field to given value.


### GetMydexid

`func (o *FtcSetupRequestBody) GetMydexid() string`

GetMydexid returns the Mydexid field if non-nil, zero value otherwise.

### GetMydexidOk

`func (o *FtcSetupRequestBody) GetMydexidOk() (*string, bool)`

GetMydexidOk returns a tuple with the Mydexid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMydexid

`func (o *FtcSetupRequestBody) SetMydexid(v string)`

SetMydexid sets Mydexid field to given value.

### HasMydexid

`func (o *FtcSetupRequestBody) HasMydexid() bool`

HasMydexid returns a boolean if a field has been set.

### SetMydexidNil

`func (o *FtcSetupRequestBody) SetMydexidNil(b bool)`

 SetMydexidNil sets the value for Mydexid to be an explicit nil

### UnsetMydexid
`func (o *FtcSetupRequestBody) UnsetMydexid()`

UnsetMydexid ensures that no value is present for Mydexid, not even an explicit nil
### GetVersion

`func (o *FtcSetupRequestBody) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *FtcSetupRequestBody) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *FtcSetupRequestBody) SetVersion(v int32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *FtcSetupRequestBody) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetLinkingToken

`func (o *FtcSetupRequestBody) GetLinkingToken() string`

GetLinkingToken returns the LinkingToken field if non-nil, zero value otherwise.

### GetLinkingTokenOk

`func (o *FtcSetupRequestBody) GetLinkingTokenOk() (*string, bool)`

GetLinkingTokenOk returns a tuple with the LinkingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkingToken

`func (o *FtcSetupRequestBody) SetLinkingToken(v string)`

SetLinkingToken sets LinkingToken field to given value.

### HasLinkingToken

`func (o *FtcSetupRequestBody) HasLinkingToken() bool`

HasLinkingToken returns a boolean if a field has been set.

### SetLinkingTokenNil

`func (o *FtcSetupRequestBody) SetLinkingTokenNil(b bool)`

 SetLinkingTokenNil sets the value for LinkingToken to be an explicit nil

### UnsetLinkingToken
`func (o *FtcSetupRequestBody) UnsetLinkingToken()`

UnsetLinkingToken ensures that no value is present for LinkingToken, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


