# GetInviteResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **int32** |  | [optional] 
**InviteUrlCode** | Pointer to **string** | The invitation URL code | [optional] 
**ParentUuid** | Pointer to **string** | The parent identifier UUID | [optional] 
**AppUrl** | Pointer to **string** | The application URL | [optional] 
**ClientId** | Pointer to **string** | The OAuth2 client ID | [optional] 
**ConNid** | Pointer to **string** | The connection NID | [optional] 
**OrgId** | Pointer to **NullableString** | The organization ID | [optional] 
**ProjectId** | Pointer to **NullableString** | The project ID | [optional] 
**ItemId** | Pointer to **NullableString** | The item ID | [optional] 
**Type** | Pointer to **string** | The type of invitation | [optional] 

## Methods

### NewGetInviteResponse

`func NewGetInviteResponse() *GetInviteResponse`

NewGetInviteResponse instantiates a new GetInviteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetInviteResponseWithDefaults

`func NewGetInviteResponseWithDefaults() *GetInviteResponse`

NewGetInviteResponseWithDefaults instantiates a new GetInviteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetInviteResponse) GetSuccess() int32`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetInviteResponse) GetSuccessOk() (*int32, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetInviteResponse) SetSuccess(v int32)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *GetInviteResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetInviteUrlCode

`func (o *GetInviteResponse) GetInviteUrlCode() string`

GetInviteUrlCode returns the InviteUrlCode field if non-nil, zero value otherwise.

### GetInviteUrlCodeOk

`func (o *GetInviteResponse) GetInviteUrlCodeOk() (*string, bool)`

GetInviteUrlCodeOk returns a tuple with the InviteUrlCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInviteUrlCode

`func (o *GetInviteResponse) SetInviteUrlCode(v string)`

SetInviteUrlCode sets InviteUrlCode field to given value.

### HasInviteUrlCode

`func (o *GetInviteResponse) HasInviteUrlCode() bool`

HasInviteUrlCode returns a boolean if a field has been set.

### GetParentUuid

`func (o *GetInviteResponse) GetParentUuid() string`

GetParentUuid returns the ParentUuid field if non-nil, zero value otherwise.

### GetParentUuidOk

`func (o *GetInviteResponse) GetParentUuidOk() (*string, bool)`

GetParentUuidOk returns a tuple with the ParentUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentUuid

`func (o *GetInviteResponse) SetParentUuid(v string)`

SetParentUuid sets ParentUuid field to given value.

### HasParentUuid

`func (o *GetInviteResponse) HasParentUuid() bool`

HasParentUuid returns a boolean if a field has been set.

### GetAppUrl

`func (o *GetInviteResponse) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *GetInviteResponse) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *GetInviteResponse) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *GetInviteResponse) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.

### GetClientId

`func (o *GetInviteResponse) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *GetInviteResponse) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *GetInviteResponse) SetClientId(v string)`

SetClientId sets ClientId field to given value.

### HasClientId

`func (o *GetInviteResponse) HasClientId() bool`

HasClientId returns a boolean if a field has been set.

### GetConNid

`func (o *GetInviteResponse) GetConNid() string`

GetConNid returns the ConNid field if non-nil, zero value otherwise.

### GetConNidOk

`func (o *GetInviteResponse) GetConNidOk() (*string, bool)`

GetConNidOk returns a tuple with the ConNid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConNid

`func (o *GetInviteResponse) SetConNid(v string)`

SetConNid sets ConNid field to given value.

### HasConNid

`func (o *GetInviteResponse) HasConNid() bool`

HasConNid returns a boolean if a field has been set.

### GetOrgId

`func (o *GetInviteResponse) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *GetInviteResponse) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *GetInviteResponse) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.

### HasOrgId

`func (o *GetInviteResponse) HasOrgId() bool`

HasOrgId returns a boolean if a field has been set.

### SetOrgIdNil

`func (o *GetInviteResponse) SetOrgIdNil(b bool)`

 SetOrgIdNil sets the value for OrgId to be an explicit nil

### UnsetOrgId
`func (o *GetInviteResponse) UnsetOrgId()`

UnsetOrgId ensures that no value is present for OrgId, not even an explicit nil
### GetProjectId

`func (o *GetInviteResponse) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GetInviteResponse) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GetInviteResponse) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *GetInviteResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### SetProjectIdNil

`func (o *GetInviteResponse) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *GetInviteResponse) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetItemId

`func (o *GetInviteResponse) GetItemId() string`

GetItemId returns the ItemId field if non-nil, zero value otherwise.

### GetItemIdOk

`func (o *GetInviteResponse) GetItemIdOk() (*string, bool)`

GetItemIdOk returns a tuple with the ItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemId

`func (o *GetInviteResponse) SetItemId(v string)`

SetItemId sets ItemId field to given value.

### HasItemId

`func (o *GetInviteResponse) HasItemId() bool`

HasItemId returns a boolean if a field has been set.

### SetItemIdNil

`func (o *GetInviteResponse) SetItemIdNil(b bool)`

 SetItemIdNil sets the value for ItemId to be an explicit nil

### UnsetItemId
`func (o *GetInviteResponse) UnsetItemId()`

UnsetItemId ensures that no value is present for ItemId, not even an explicit nil
### GetType

`func (o *GetInviteResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *GetInviteResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *GetInviteResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *GetInviteResponse) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


