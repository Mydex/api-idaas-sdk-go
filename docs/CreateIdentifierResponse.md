# CreateIdentifierResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **int32** | Whether the operation succeeded | [optional] 
**Identifier** | Pointer to **string** | The newly created identifier UUID | [optional] 

## Methods

### NewCreateIdentifierResponse

`func NewCreateIdentifierResponse() *CreateIdentifierResponse`

NewCreateIdentifierResponse instantiates a new CreateIdentifierResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateIdentifierResponseWithDefaults

`func NewCreateIdentifierResponseWithDefaults() *CreateIdentifierResponse`

NewCreateIdentifierResponseWithDefaults instantiates a new CreateIdentifierResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *CreateIdentifierResponse) GetSuccess() int32`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateIdentifierResponse) GetSuccessOk() (*int32, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateIdentifierResponse) SetSuccess(v int32)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *CreateIdentifierResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetIdentifier

`func (o *CreateIdentifierResponse) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *CreateIdentifierResponse) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *CreateIdentifierResponse) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *CreateIdentifierResponse) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


