# \SlicesAPI

All URIs are relative to *http://127.0.0.1:8700*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SlicesCreatePost**](SlicesAPI.md#SlicesCreatePost) | **Post** /slices/create | Create slice
[**SlicesCreatesPost**](SlicesAPI.md#SlicesCreatesPost) | **Post** /slices/creates | Create slice
[**SlicesDeleteDelete**](SlicesAPI.md#SlicesDeleteDelete) | **Delete** /slices/delete | Delete all slices for a User within a project.
[**SlicesDeleteSliceIdDelete**](SlicesAPI.md#SlicesDeleteSliceIdDelete) | **Delete** /slices/delete/{slice_id} | Delete slice.
[**SlicesGet**](SlicesAPI.md#SlicesGet) | **Get** /slices | Retrieve a listing of user slices
[**SlicesModifySliceIdAcceptPost**](SlicesAPI.md#SlicesModifySliceIdAcceptPost) | **Post** /slices/modify/{slice_id}/accept | Accept the last modify an existing slice
[**SlicesModifySliceIdPut**](SlicesAPI.md#SlicesModifySliceIdPut) | **Put** /slices/modify/{slice_id} | Modify an existing slice
[**SlicesRenewSliceIdPost**](SlicesAPI.md#SlicesRenewSliceIdPost) | **Post** /slices/renew/{slice_id} | Renew slice
[**SlicesSliceIdGet**](SlicesAPI.md#SlicesSliceIdGet) | **Get** /slices/{slice_id} | slice properties



## SlicesCreatePost

> Slivers SlicesCreatePost(ctx).Name(name).SshKey(sshKey).Body(body).LeaseEndTime(leaseEndTime).Execute()

Create slice



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/CSC478-WCU/fabric-orchestrator-go-client"
)

func main() {
	name := "name_example" // string | Slice Name
	sshKey := "sshKey_example" // string | User SSH Key
	body := "body_example" // string | 
	leaseEndTime := "leaseEndTime_example" // string | Lease End Time for the Slice (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SlicesAPI.SlicesCreatePost(context.Background()).Name(name).SshKey(sshKey).Body(body).LeaseEndTime(leaseEndTime).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SlicesAPI.SlicesCreatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SlicesCreatePost`: Slivers
	fmt.Fprintf(os.Stdout, "Response from `SlicesAPI.SlicesCreatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSlicesCreatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | Slice Name | 
 **sshKey** | **string** | User SSH Key | 
 **body** | **string** |  | 
 **leaseEndTime** | **string** | Lease End Time for the Slice | 

### Return type

[**Slivers**](Slivers.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SlicesCreatesPost

> Slivers SlicesCreatesPost(ctx).Name(name).SlicesPost(slicesPost).Lifetime(lifetime).LeaseStartTime(leaseStartTime).LeaseEndTime(leaseEndTime).Execute()

Create slice



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/CSC478-WCU/fabric-orchestrator-go-client"
)

func main() {
	name := "name_example" // string | Slice Name
	slicesPost := *openapiclient.NewSlicesPost("GraphModel_example", []string{"SshKeys_example"}) // SlicesPost | Create new Slice
	lifetime := int32(56) // int32 | Lifetime of the slice requested in hours. (optional) (default to 24)
	leaseStartTime := "2023-01-01 16:20:15 +00:00" // string | Lease End Time for the Slice (optional)
	leaseEndTime := "2023-01-01 16:20:15 +00:00" // string | Lease End Time for the Slice (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SlicesAPI.SlicesCreatesPost(context.Background()).Name(name).SlicesPost(slicesPost).Lifetime(lifetime).LeaseStartTime(leaseStartTime).LeaseEndTime(leaseEndTime).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SlicesAPI.SlicesCreatesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SlicesCreatesPost`: Slivers
	fmt.Fprintf(os.Stdout, "Response from `SlicesAPI.SlicesCreatesPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSlicesCreatesPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | Slice Name | 
 **slicesPost** | [**SlicesPost**](SlicesPost.md) | Create new Slice | 
 **lifetime** | **int32** | Lifetime of the slice requested in hours. | [default to 24]
 **leaseStartTime** | **string** | Lease End Time for the Slice | 
 **leaseEndTime** | **string** | Lease End Time for the Slice | 

### Return type

[**Slivers**](Slivers.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SlicesDeleteDelete

> Status200OkNoContent SlicesDeleteDelete(ctx).Execute()

Delete all slices for a User within a project.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/CSC478-WCU/fabric-orchestrator-go-client"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SlicesAPI.SlicesDeleteDelete(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SlicesAPI.SlicesDeleteDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SlicesDeleteDelete`: Status200OkNoContent
	fmt.Fprintf(os.Stdout, "Response from `SlicesAPI.SlicesDeleteDelete`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSlicesDeleteDeleteRequest struct via the builder pattern


### Return type

[**Status200OkNoContent**](Status200OkNoContent.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SlicesDeleteSliceIdDelete

> Status200OkNoContent SlicesDeleteSliceIdDelete(ctx, sliceId).Execute()

Delete slice.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/CSC478-WCU/fabric-orchestrator-go-client"
)

func main() {
	sliceId := "sliceId_example" // string | Slice identified by universally unique identifier

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SlicesAPI.SlicesDeleteSliceIdDelete(context.Background(), sliceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SlicesAPI.SlicesDeleteSliceIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SlicesDeleteSliceIdDelete`: Status200OkNoContent
	fmt.Fprintf(os.Stdout, "Response from `SlicesAPI.SlicesDeleteSliceIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sliceId** | **string** | Slice identified by universally unique identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiSlicesDeleteSliceIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Status200OkNoContent**](Status200OkNoContent.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SlicesGet

> Slices SlicesGet(ctx).Name(name).Search(search).ExactMatch(exactMatch).AsSelf(asSelf).States(states).Limit(limit).Offset(offset).Execute()

Retrieve a listing of user slices



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/CSC478-WCU/fabric-orchestrator-go-client"
)

func main() {
	name := "name_example" // string | Search for Slices with the name (optional)
	search := "search_example" // string | search term applied (optional)
	exactMatch := true // bool | Exact Match for Search term (optional) (default to false)
	asSelf := true // bool | GET object as Self (optional) (default to true)
	states := []string{"States_example"} // []string | Search for Slices in the specified states (optional)
	limit := int32(56) // int32 | maximum number of results to return per page (1 or more) (optional) (default to 5)
	offset := int32(56) // int32 | number of items to skip before starting to collect the result set (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SlicesAPI.SlicesGet(context.Background()).Name(name).Search(search).ExactMatch(exactMatch).AsSelf(asSelf).States(states).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SlicesAPI.SlicesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SlicesGet`: Slices
	fmt.Fprintf(os.Stdout, "Response from `SlicesAPI.SlicesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSlicesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | Search for Slices with the name | 
 **search** | **string** | search term applied | 
 **exactMatch** | **bool** | Exact Match for Search term | [default to false]
 **asSelf** | **bool** | GET object as Self | [default to true]
 **states** | **[]string** | Search for Slices in the specified states | 
 **limit** | **int32** | maximum number of results to return per page (1 or more) | [default to 5]
 **offset** | **int32** | number of items to skip before starting to collect the result set | [default to 0]

### Return type

[**Slices**](Slices.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SlicesModifySliceIdAcceptPost

> SliceDetails SlicesModifySliceIdAcceptPost(ctx, sliceId).Execute()

Accept the last modify an existing slice



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/CSC478-WCU/fabric-orchestrator-go-client"
)

func main() {
	sliceId := "sliceId_example" // string | Slice identified by universally unique identifier

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SlicesAPI.SlicesModifySliceIdAcceptPost(context.Background(), sliceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SlicesAPI.SlicesModifySliceIdAcceptPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SlicesModifySliceIdAcceptPost`: SliceDetails
	fmt.Fprintf(os.Stdout, "Response from `SlicesAPI.SlicesModifySliceIdAcceptPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sliceId** | **string** | Slice identified by universally unique identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiSlicesModifySliceIdAcceptPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SliceDetails**](SliceDetails.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SlicesModifySliceIdPut

> Slivers SlicesModifySliceIdPut(ctx, sliceId).Body(body).Execute()

Modify an existing slice



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/CSC478-WCU/fabric-orchestrator-go-client"
)

func main() {
	sliceId := "sliceId_example" // string | Slice identified by universally unique identifier
	body := "body_example" // string | Modify a Slice

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SlicesAPI.SlicesModifySliceIdPut(context.Background(), sliceId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SlicesAPI.SlicesModifySliceIdPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SlicesModifySliceIdPut`: Slivers
	fmt.Fprintf(os.Stdout, "Response from `SlicesAPI.SlicesModifySliceIdPut`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sliceId** | **string** | Slice identified by universally unique identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiSlicesModifySliceIdPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **string** | Modify a Slice | 

### Return type

[**Slivers**](Slivers.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: text/plain
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SlicesRenewSliceIdPost

> Status200OkNoContent SlicesRenewSliceIdPost(ctx, sliceId).LeaseEndTime(leaseEndTime).Execute()

Renew slice



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/CSC478-WCU/fabric-orchestrator-go-client"
)

func main() {
	sliceId := "sliceId_example" // string | Slice identified by universally unique identifier
	leaseEndTime := "leaseEndTime_example" // string | New Lease End Time for the Slice

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SlicesAPI.SlicesRenewSliceIdPost(context.Background(), sliceId).LeaseEndTime(leaseEndTime).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SlicesAPI.SlicesRenewSliceIdPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SlicesRenewSliceIdPost`: Status200OkNoContent
	fmt.Fprintf(os.Stdout, "Response from `SlicesAPI.SlicesRenewSliceIdPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sliceId** | **string** | Slice identified by universally unique identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiSlicesRenewSliceIdPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **leaseEndTime** | **string** | New Lease End Time for the Slice | 

### Return type

[**Status200OkNoContent**](Status200OkNoContent.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SlicesSliceIdGet

> SliceDetails SlicesSliceIdGet(ctx, sliceId).GraphFormat(graphFormat).AsSelf(asSelf).Execute()

slice properties



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/CSC478-WCU/fabric-orchestrator-go-client"
)

func main() {
	sliceId := "sliceId_example" // string | Slice identified by universally unique identifier
	graphFormat := "graphFormat_example" // string | graph format (default to "GRAPHML")
	asSelf := true // bool | GET object as Self (optional) (default to true)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SlicesAPI.SlicesSliceIdGet(context.Background(), sliceId).GraphFormat(graphFormat).AsSelf(asSelf).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SlicesAPI.SlicesSliceIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SlicesSliceIdGet`: SliceDetails
	fmt.Fprintf(os.Stdout, "Response from `SlicesAPI.SlicesSliceIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sliceId** | **string** | Slice identified by universally unique identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiSlicesSliceIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **graphFormat** | **string** | graph format | [default to &quot;GRAPHML&quot;]
 **asSelf** | **bool** | GET object as Self | [default to true]

### Return type

[**SliceDetails**](SliceDetails.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

