# IdentifierObject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Database ID of the identifier | [optional] 
**Identifier** | Pointer to **string** | The UUID identifier | [optional] 
**ParentUuid** | Pointer to **NullableString** | The parent identifier UUID if this is a child | [optional] 
**Type** | Pointer to **string** | The type of identifier | [optional] 
**Created** | Pointer to **string** | Creation timestamp | [optional] 

## Methods

### NewIdentifierObject

`func NewIdentifierObject() *IdentifierObject`

NewIdentifierObject instantiates a new IdentifierObject object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdentifierObjectWithDefaults

`func NewIdentifierObjectWithDefaults() *IdentifierObject`

NewIdentifierObjectWithDefaults instantiates a new IdentifierObject object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *IdentifierObject) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *IdentifierObject) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *IdentifierObject) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *IdentifierObject) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIdentifier

`func (o *IdentifierObject) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *IdentifierObject) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *IdentifierObject) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *IdentifierObject) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### GetParentUuid

`func (o *IdentifierObject) GetParentUuid() string`

GetParentUuid returns the ParentUuid field if non-nil, zero value otherwise.

### GetParentUuidOk

`func (o *IdentifierObject) GetParentUuidOk() (*string, bool)`

GetParentUuidOk returns a tuple with the ParentUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentUuid

`func (o *IdentifierObject) SetParentUuid(v string)`

SetParentUuid sets ParentUuid field to given value.

### HasParentUuid

`func (o *IdentifierObject) HasParentUuid() bool`

HasParentUuid returns a boolean if a field has been set.

### SetParentUuidNil

`func (o *IdentifierObject) SetParentUuidNil(b bool)`

 SetParentUuidNil sets the value for ParentUuid to be an explicit nil

### UnsetParentUuid
`func (o *IdentifierObject) UnsetParentUuid()`

UnsetParentUuid ensures that no value is present for ParentUuid, not even an explicit nil
### GetType

`func (o *IdentifierObject) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *IdentifierObject) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *IdentifierObject) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *IdentifierObject) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCreated

`func (o *IdentifierObject) GetCreated() string`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *IdentifierObject) GetCreatedOk() (*string, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *IdentifierObject) SetCreated(v string)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *IdentifierObject) HasCreated() bool`

HasCreated returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


