# \MyAccountAPI

All URIs are relative to *https://idp.mydexid.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetMydexIdFromMyAccountSvt**](MyAccountAPI.md#GetMydexIdFromMyAccountSvt) | **Get** /members/myaccount/{svt} | Check if a MyAccount SVT has an associated MydexID.



## GetMydexIdFromMyAccountSvt

> string GetMydexIdFromMyAccountSvt(ctx, svt).Execute()

Check if a MyAccount SVT has an associated MydexID.



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
	svt := "abc123xyz456" // string | The MyAccount security verification token

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MyAccountAPI.GetMydexIdFromMyAccountSvt(context.Background(), svt).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MyAccountAPI.GetMydexIdFromMyAccountSvt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMydexIdFromMyAccountSvt`: string
	fmt.Fprintf(os.Stdout, "Response from `MyAccountAPI.GetMydexIdFromMyAccountSvt`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**svt** | **string** | The MyAccount security verification token | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMydexIdFromMyAccountSvtRequest struct via the builder pattern


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

