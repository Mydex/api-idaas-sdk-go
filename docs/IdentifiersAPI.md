# \IdentifiersAPI

All URIs are relative to *https://idp.mydexid.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetIdentifierInvite**](IdentifiersAPI.md#GetIdentifierInvite) | **Get** /members/invite/{invite} | Fetch an invitation code and identifier auth data.
[**PatchNotifyStatus**](IdentifiersAPI.md#PatchNotifyStatus) | **Patch** /members/notify/status | Update the status of a notification.
[**PostInviteStatus**](IdentifiersAPI.md#PostInviteStatus) | **Post** /members/invite/status | Check the status of an invite.
[**PostNotifyMemberViaIdentifier**](IdentifiersAPI.md#PostNotifyMemberViaIdentifier) | **Post** /members/notify | Send a notification to a member via its identifier.
[**PostStoreAndSendIdentifierInvite**](IdentifiersAPI.md#PostStoreAndSendIdentifierInvite) | **Post** /members/invite | Store an invitation code and send notification.



## GetIdentifierInvite

> GetInviteResponse GetIdentifierInvite(ctx, invite).Execute()

Fetch an invitation code and identifier auth data.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	invite := "a1b2c3d4e5f6" // string | The invitation code

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IdentifiersAPI.GetIdentifierInvite(context.Background(), invite).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IdentifiersAPI.GetIdentifierInvite``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetIdentifierInvite`: GetInviteResponse
	fmt.Fprintf(os.Stdout, "Response from `IdentifiersAPI.GetIdentifierInvite`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**invite** | **string** | The invitation code | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetIdentifierInviteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetInviteResponse**](GetInviteResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchNotifyStatus

> CreateIdentifierResponse PatchNotifyStatus(ctx).UpdateNotificationStatusRequestBody(updateNotificationStatusRequestBody).Execute()

Update the status of a notification.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	updateNotificationStatusRequestBody := *openapiclient.NewUpdateNotificationStatusRequestBody("550e8400-e29b-41d4-a716-446655440000") // UpdateNotificationStatusRequestBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IdentifiersAPI.PatchNotifyStatus(context.Background()).UpdateNotificationStatusRequestBody(updateNotificationStatusRequestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IdentifiersAPI.PatchNotifyStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchNotifyStatus`: CreateIdentifierResponse
	fmt.Fprintf(os.Stdout, "Response from `IdentifiersAPI.PatchNotifyStatus`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPatchNotifyStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateNotificationStatusRequestBody** | [**UpdateNotificationStatusRequestBody**](UpdateNotificationStatusRequestBody.md) |  | 

### Return type

[**CreateIdentifierResponse**](CreateIdentifierResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostInviteStatus

> InviteStatusResponse PostInviteStatus(ctx).InviteStatusRequestBody(inviteStatusRequestBody).Execute()

Check the status of an invite.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	inviteStatusRequestBody := *openapiclient.NewInviteStatusRequestBody("550e8400-e29b-41d4-a716-446655440000", "https://example.com", "client123", "456", "org789", "proj123", "item456", "identifier") // InviteStatusRequestBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IdentifiersAPI.PostInviteStatus(context.Background()).InviteStatusRequestBody(inviteStatusRequestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IdentifiersAPI.PostInviteStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostInviteStatus`: InviteStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `IdentifiersAPI.PostInviteStatus`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostInviteStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inviteStatusRequestBody** | [**InviteStatusRequestBody**](InviteStatusRequestBody.md) |  | 

### Return type

[**InviteStatusResponse**](InviteStatusResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostNotifyMemberViaIdentifier

> CreateIdentifierResponse PostNotifyMemberViaIdentifier(ctx).NotifyMemberRequestBody(notifyMemberRequestBody).Execute()

Send a notification to a member via its identifier.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	notifyMemberRequestBody := *openapiclient.NewNotifyMemberRequestBody(*openapiclient.NewIdentifierAuthObject(), "Please verify your identity") // NotifyMemberRequestBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IdentifiersAPI.PostNotifyMemberViaIdentifier(context.Background()).NotifyMemberRequestBody(notifyMemberRequestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IdentifiersAPI.PostNotifyMemberViaIdentifier``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostNotifyMemberViaIdentifier`: CreateIdentifierResponse
	fmt.Fprintf(os.Stdout, "Response from `IdentifiersAPI.PostNotifyMemberViaIdentifier`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostNotifyMemberViaIdentifierRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **notifyMemberRequestBody** | [**NotifyMemberRequestBody**](NotifyMemberRequestBody.md) |  | 

### Return type

[**CreateIdentifierResponse**](CreateIdentifierResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostStoreAndSendIdentifierInvite

> GetInviteResponse PostStoreAndSendIdentifierInvite(ctx).InviteRequestBody(inviteRequestBody).Execute()

Store an invitation code and send notification.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	inviteRequestBody := *openapiclient.NewInviteRequestBody("550e8400-e29b-41d4-a716-446655440000", "https://example.com", "client123", "456", "org789", "proj123", "item456", "identifier", "Please complete your registration") // InviteRequestBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IdentifiersAPI.PostStoreAndSendIdentifierInvite(context.Background()).InviteRequestBody(inviteRequestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IdentifiersAPI.PostStoreAndSendIdentifierInvite``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostStoreAndSendIdentifierInvite`: GetInviteResponse
	fmt.Fprintf(os.Stdout, "Response from `IdentifiersAPI.PostStoreAndSendIdentifierInvite`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostStoreAndSendIdentifierInviteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inviteRequestBody** | [**InviteRequestBody**](InviteRequestBody.md) |  | 

### Return type

[**GetInviteResponse**](GetInviteResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

