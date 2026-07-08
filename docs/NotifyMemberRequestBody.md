# NotifyMemberRequestBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IdentifierAuth** | [**IdentifierAuthObject**](IdentifierAuthObject.md) |  | 
**MessageEmail** | **string** | Email message content | 
**MessageSms** | Pointer to **NullableString** | SMS message content | [optional] 

## Methods

### NewNotifyMemberRequestBody

`func NewNotifyMemberRequestBody(identifierAuth IdentifierAuthObject, messageEmail string, ) *NotifyMemberRequestBody`

NewNotifyMemberRequestBody instantiates a new NotifyMemberRequestBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNotifyMemberRequestBodyWithDefaults

`func NewNotifyMemberRequestBodyWithDefaults() *NotifyMemberRequestBody`

NewNotifyMemberRequestBodyWithDefaults instantiates a new NotifyMemberRequestBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifierAuth

`func (o *NotifyMemberRequestBody) GetIdentifierAuth() IdentifierAuthObject`

GetIdentifierAuth returns the IdentifierAuth field if non-nil, zero value otherwise.

### GetIdentifierAuthOk

`func (o *NotifyMemberRequestBody) GetIdentifierAuthOk() (*IdentifierAuthObject, bool)`

GetIdentifierAuthOk returns a tuple with the IdentifierAuth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifierAuth

`func (o *NotifyMemberRequestBody) SetIdentifierAuth(v IdentifierAuthObject)`

SetIdentifierAuth sets IdentifierAuth field to given value.


### GetMessageEmail

`func (o *NotifyMemberRequestBody) GetMessageEmail() string`

GetMessageEmail returns the MessageEmail field if non-nil, zero value otherwise.

### GetMessageEmailOk

`func (o *NotifyMemberRequestBody) GetMessageEmailOk() (*string, bool)`

GetMessageEmailOk returns a tuple with the MessageEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageEmail

`func (o *NotifyMemberRequestBody) SetMessageEmail(v string)`

SetMessageEmail sets MessageEmail field to given value.


### GetMessageSms

`func (o *NotifyMemberRequestBody) GetMessageSms() string`

GetMessageSms returns the MessageSms field if non-nil, zero value otherwise.

### GetMessageSmsOk

`func (o *NotifyMemberRequestBody) GetMessageSmsOk() (*string, bool)`

GetMessageSmsOk returns a tuple with the MessageSms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageSms

`func (o *NotifyMemberRequestBody) SetMessageSms(v string)`

SetMessageSms sets MessageSms field to given value.

### HasMessageSms

`func (o *NotifyMemberRequestBody) HasMessageSms() bool`

HasMessageSms returns a boolean if a field has been set.

### SetMessageSmsNil

`func (o *NotifyMemberRequestBody) SetMessageSmsNil(b bool)`

 SetMessageSmsNil sets the value for MessageSms to be an explicit nil

### UnsetMessageSms
`func (o *NotifyMemberRequestBody) UnsetMessageSms()`

UnsetMessageSms ensures that no value is present for MessageSms, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


