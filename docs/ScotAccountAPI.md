# \ScotAccountAPI

All URIs are relative to *https://idp.mydexid.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetMydexIdFromScotAccountSub**](ScotAccountAPI.md#GetMydexIdFromScotAccountSub) | **Get** /members/scotaccount/{sub} | Check if a ScotAccount sub GUID has an associated MydexID.



## GetMydexIdFromScotAccountSub

> string GetMydexIdFromScotAccountSub(ctx, sub).Execute()

Check if a ScotAccount sub GUID has an associated MydexID.



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
	sub := "123e4567-e89b-12d3-a456-426614174000" // string | The ScotAccount GUID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ScotAccountAPI.GetMydexIdFromScotAccountSub(context.Background(), sub).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ScotAccountAPI.GetMydexIdFromScotAccountSub``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMydexIdFromScotAccountSub`: string
	fmt.Fprintf(os.Stdout, "Response from `ScotAccountAPI.GetMydexIdFromScotAccountSub`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sub** | **string** | The ScotAccount GUID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMydexIdFromScotAccountSubRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

