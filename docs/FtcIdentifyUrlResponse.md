# FtcIdentifyUrlResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | Pointer to **string** | The one-time URL for FTC or identification | [optional] 
**Qr** | Pointer to **string** | QR code representation of the URL | [optional] 

## Methods

### NewFtcIdentifyUrlResponse

`func NewFtcIdentifyUrlResponse() *FtcIdentifyUrlResponse`

NewFtcIdentifyUrlResponse instantiates a new FtcIdentifyUrlResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFtcIdentifyUrlResponseWithDefaults

`func NewFtcIdentifyUrlResponseWithDefaults() *FtcIdentifyUrlResponse`

NewFtcIdentifyUrlResponseWithDefaults instantiates a new FtcIdentifyUrlResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *FtcIdentifyUrlResponse) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *FtcIdentifyUrlResponse) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *FtcIdentifyUrlResponse) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *FtcIdentifyUrlResponse) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetQr

`func (o *FtcIdentifyUrlResponse) GetQr() string`

GetQr returns the Qr field if non-nil, zero value otherwise.

### GetQrOk

`func (o *FtcIdentifyUrlResponse) GetQrOk() (*string, bool)`

GetQrOk returns a tuple with the Qr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQr

`func (o *FtcIdentifyUrlResponse) SetQr(v string)`

SetQr sets Qr field to given value.

### HasQr

`func (o *FtcIdentifyUrlResponse) HasQr() bool`

HasQr returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


