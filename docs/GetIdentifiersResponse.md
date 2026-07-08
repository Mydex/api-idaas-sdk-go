# GetIdentifiersResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **int32** |  | [optional] 
**Identifiers** | Pointer to [**[]IdentifierObject**](IdentifierObject.md) |  | [optional] 

## Methods

### NewGetIdentifiersResponse

`func NewGetIdentifiersResponse() *GetIdentifiersResponse`

NewGetIdentifiersResponse instantiates a new GetIdentifiersResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetIdentifiersResponseWithDefaults

`func NewGetIdentifiersResponseWithDefaults() *GetIdentifiersResponse`

NewGetIdentifiersResponseWithDefaults instantiates a new GetIdentifiersResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetIdentifiersResponse) GetSuccess() int32`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetIdentifiersResponse) GetSuccessOk() (*int32, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetIdentifiersResponse) SetSuccess(v int32)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *GetIdentifiersResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetIdentifiers

`func (o *GetIdentifiersResponse) GetIdentifiers() []IdentifierObject`

GetIdentifiers returns the Identifiers field if non-nil, zero value otherwise.

### GetIdentifiersOk

`func (o *GetIdentifiersResponse) GetIdentifiersOk() (*[]IdentifierObject, bool)`

GetIdentifiersOk returns a tuple with the Identifiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifiers

`func (o *GetIdentifiersResponse) SetIdentifiers(v []IdentifierObject)`

SetIdentifiers sets Identifiers field to given value.

### HasIdentifiers

`func (o *GetIdentifiersResponse) HasIdentifiers() bool`

HasIdentifiers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


