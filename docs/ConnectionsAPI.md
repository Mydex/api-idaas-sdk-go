# \ConnectionsAPI

All URIs are relative to *https://idp.mydexid.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PostFtcSetup**](ConnectionsAPI.md#PostFtcSetup) | **Post** /ftc/setup | Set up a First Time Connection URL.
[**PostIdentify**](ConnectionsAPI.md#PostIdentify) | **Post** /identify | Set up an identification URL.



## PostFtcSetup

> FtcUrlResponse PostFtcSetup(ctx).FtcSetupRequestBody(ftcSetupRequestBody).Execute()

Set up a First Time Connection URL.



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
	ftcSetupRequestBody := *openapiclient.NewFtcSetupRequestBody("123", "abc123hashed", "https://example.com/callback") // FtcSetupRequestBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConnectionsAPI.PostFtcSetup(context.Background()).FtcSetupRequestBody(ftcSetupRequestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConnectionsAPI.PostFtcSetup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostFtcSetup`: FtcUrlResponse
	fmt.Fprintf(os.Stdout, "Response from `ConnectionsAPI.PostFtcSetup`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostFtcSetupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ftcSetupRequestBody** | [**FtcSetupRequestBody**](FtcSetupRequestBody.md) |  | 

### Return type

[**FtcUrlResponse**](FtcUrlResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostIdentify

> IdentifyUrlResponse PostIdentify(ctx).IdentifyRequestBody(identifyRequestBody).Execute()

Set up an identification URL.



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
	identifyRequestBody := *openapiclient.NewIdentifyRequestBody("123", "abc123hashed", "https://example.com/callback") // IdentifyRequestBody |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConnectionsAPI.PostIdentify(context.Background()).IdentifyRequestBody(identifyRequestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConnectionsAPI.PostIdentify``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostIdentify`: IdentifyUrlResponse
	fmt.Fprintf(os.Stdout, "Response from `ConnectionsAPI.PostIdentify`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostIdentifyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **identifyRequestBody** | [**IdentifyRequestBody**](IdentifyRequestBody.md) |  | 

### Return type

[**IdentifyUrlResponse**](IdentifyUrlResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

