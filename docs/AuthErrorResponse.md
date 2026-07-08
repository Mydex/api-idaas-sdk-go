# AuthErrorResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to [**AuthErrorResponseError**](AuthErrorResponseError.md) |  | [optional] 

## Methods

### NewAuthErrorResponse

`func NewAuthErrorResponse() *AuthErrorResponse`

NewAuthErrorResponse instantiates a new AuthErrorResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthErrorResponseWithDefaults

`func NewAuthErrorResponseWithDefaults() *AuthErrorResponse`

NewAuthErrorResponseWithDefaults instantiates a new AuthErrorResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *AuthErrorResponse) GetError() AuthErrorResponseError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AuthErrorResponse) GetErrorOk() (*AuthErrorResponseError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AuthErrorResponse) SetError(v AuthErrorResponseError)`

SetError sets Error field to given value.

### HasError

`func (o *AuthErrorResponse) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


