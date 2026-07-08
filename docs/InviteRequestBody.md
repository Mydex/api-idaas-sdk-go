# InviteRequestBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | The parent identifier | 
**AppUrl** | **string** | The application URL | 
**ClientId** | **string** | The OAuth2 client ID | 
**ConNid** | **string** | The connection NID | 
**OrgId** | **string** | The organization ID | 
**ProjectId** | **string** | The project ID | 
**ItemId** | **string** | The item ID | 
**Type** | **string** | The type of invitation | 
**MessageEmail** | **string** | Email message content | 
**MessageSms** | Pointer to **NullableString** | SMS message content | [optional] 

## Methods

### NewInviteRequestBody

`func NewInviteRequestBody(identifier string, appUrl string, clientId string, conNid string, orgId string, projectId string, itemId string, type_ string, messageEmail string, ) *InviteRequestBody`

NewInviteRequestBody instantiates a new InviteRequestBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInviteRequestBodyWithDefaults

`func NewInviteRequestBodyWithDefaults() *InviteRequestBody`

NewInviteRequestBodyWithDefaults instantiates a new InviteRequestBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *InviteRequestBody) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *InviteRequestBody) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *InviteRequestBody) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetAppUrl

`func (o *InviteRequestBody) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *InviteRequestBody) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *InviteRequestBody) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.


### GetClientId

`func (o *InviteRequestBody) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *InviteRequestBody) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *InviteRequestBody) SetClientId(v string)`

SetClientId sets ClientId field to given value.


### GetConNid

`func (o *InviteRequestBody) GetConNid() string`

GetConNid returns the ConNid field if non-nil, zero value otherwise.

### GetConNidOk

`func (o *InviteRequestBody) GetConNidOk() (*string, bool)`

GetConNidOk returns a tuple with the ConNid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConNid

`func (o *InviteRequestBody) SetConNid(v string)`

SetConNid sets ConNid field to given value.


### GetOrgId

`func (o *InviteRequestBody) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *InviteRequestBody) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *InviteRequestBody) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.


### GetProjectId

`func (o *InviteRequestBody) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *InviteRequestBody) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *InviteRequestBody) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetItemId

`func (o *InviteRequestBody) GetItemId() string`

GetItemId returns the ItemId field if non-nil, zero value otherwise.

### GetItemIdOk

`func (o *InviteRequestBody) GetItemIdOk() (*string, bool)`

GetItemIdOk returns a tuple with the ItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemId

`func (o *InviteRequestBody) SetItemId(v string)`

SetItemId sets ItemId field to given value.


### GetType

`func (o *InviteRequestBody) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InviteRequestBody) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InviteRequestBody) SetType(v string)`

SetType sets Type field to given value.


### GetMessageEmail

`func (o *InviteRequestBody) GetMessageEmail() string`

GetMessageEmail returns the MessageEmail field if non-nil, zero value otherwise.

### GetMessageEmailOk

`func (o *InviteRequestBody) GetMessageEmailOk() (*string, bool)`

GetMessageEmailOk returns a tuple with the MessageEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageEmail

`func (o *InviteRequestBody) SetMessageEmail(v string)`

SetMessageEmail sets MessageEmail field to given value.


### GetMessageSms

`func (o *InviteRequestBody) GetMessageSms() string`

GetMessageSms returns the MessageSms field if non-nil, zero value otherwise.

### GetMessageSmsOk

`func (o *InviteRequestBody) GetMessageSmsOk() (*string, bool)`

GetMessageSmsOk returns a tuple with the MessageSms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageSms

`func (o *InviteRequestBody) SetMessageSms(v string)`

SetMessageSms sets MessageSms field to given value.

### HasMessageSms

`func (o *InviteRequestBody) HasMessageSms() bool`

HasMessageSms returns a boolean if a field has been set.

### SetMessageSmsNil

`func (o *InviteRequestBody) SetMessageSmsNil(b bool)`

 SetMessageSmsNil sets the value for MessageSms to be an explicit nil

### UnsetMessageSms
`func (o *InviteRequestBody) UnsetMessageSms()`

UnsetMessageSms ensures that no value is present for MessageSms, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


