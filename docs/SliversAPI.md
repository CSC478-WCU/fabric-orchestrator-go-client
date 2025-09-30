# \SliversAPI

All URIs are relative to *http://127.0.0.1:8700*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SliversGet**](SliversAPI.md#SliversGet) | **Get** /slivers | Retrieve a listing of user slivers
[**SliversSliverIdGet**](SliversAPI.md#SliversSliverIdGet) | **Get** /slivers/{sliver_id} | slivers properties



## SliversGet

> Slivers SliversGet(ctx).SliceId(sliceId).AsSelf(asSelf).Execute()

Retrieve a listing of user slivers



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
	sliceId := "sliceId_example" // string | Slice identifier as UUID
	asSelf := true // bool | GET object as Self (optional) (default to true)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SliversAPI.SliversGet(context.Background()).SliceId(sliceId).AsSelf(asSelf).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SliversAPI.SliversGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SliversGet`: Slivers
	fmt.Fprintf(os.Stdout, "Response from `SliversAPI.SliversGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSliversGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sliceId** | **string** | Slice identifier as UUID | 
 **asSelf** | **bool** | GET object as Self | [default to true]

### Return type

[**Slivers**](Slivers.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SliversSliverIdGet

> Slivers SliversSliverIdGet(ctx, sliverId).SliceId(sliceId).AsSelf(asSelf).Execute()

slivers properties



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
	sliverId := "sliverId_example" // string | Sliver identified by universally unique identifier
	asSelf := true // bool | GET object as Self (optional) (default to true)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SliversAPI.SliversSliverIdGet(context.Background(), sliverId).SliceId(sliceId).AsSelf(asSelf).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SliversAPI.SliversSliverIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SliversSliverIdGet`: Slivers
	fmt.Fprintf(os.Stdout, "Response from `SliversAPI.SliversSliverIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sliverId** | **string** | Sliver identified by universally unique identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiSliversSliverIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sliceId** | **string** | Slice identified by universally unique identifier | 

 **asSelf** | **bool** | GET object as Self | [default to true]

### Return type

[**Slivers**](Slivers.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

