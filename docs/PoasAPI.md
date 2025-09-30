# \PoasAPI

All URIs are relative to *http://127.0.0.1:8700*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PoasCreateSliverIdPost**](PoasAPI.md#PoasCreateSliverIdPost) | **Post** /poas/create/{sliver_id} | Perform an operational action on a sliver.
[**PoasGet**](PoasAPI.md#PoasGet) | **Get** /poas/ | Request get the status of the POAs.
[**PoasPoaIdGet**](PoasAPI.md#PoasPoaIdGet) | **Get** /poas/{poa_id} | Perform an operational action on a sliver.



## PoasCreateSliverIdPost

> Poa PoasCreateSliverIdPost(ctx, sliverId).PoaPost(poaPost).Execute()

Perform an operational action on a sliver.



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
	sliverId := "sliverId_example" // string | Sliver identified by universally unique identifier
	poaPost := *openapiclient.NewPoaPost("Operation_example") // PoaPost | Perform Operation Action

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PoasAPI.PoasCreateSliverIdPost(context.Background(), sliverId).PoaPost(poaPost).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PoasAPI.PoasCreateSliverIdPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PoasCreateSliverIdPost`: Poa
	fmt.Fprintf(os.Stdout, "Response from `PoasAPI.PoasCreateSliverIdPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sliverId** | **string** | Sliver identified by universally unique identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiPoasCreateSliverIdPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **poaPost** | [**PoaPost**](PoaPost.md) | Perform Operation Action | 

### Return type

[**Poa**](Poa.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PoasGet

> Poa PoasGet(ctx).SliverId(sliverId).States(states).Limit(limit).Offset(offset).Execute()

Request get the status of the POAs.



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
	sliverId := "sliverId_example" // string | Search for POAs for a sliver (optional)
	states := []string{"States_example"} // []string | Search for POAs in the specified states (optional)
	limit := int32(56) // int32 | maximum number of results to return per page (1 or more) (optional) (default to 5)
	offset := int32(56) // int32 | number of items to skip before starting to collect the result set (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PoasAPI.PoasGet(context.Background()).SliverId(sliverId).States(states).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PoasAPI.PoasGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PoasGet`: Poa
	fmt.Fprintf(os.Stdout, "Response from `PoasAPI.PoasGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPoasGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sliverId** | **string** | Search for POAs for a sliver | 
 **states** | **[]string** | Search for POAs in the specified states | 
 **limit** | **int32** | maximum number of results to return per page (1 or more) | [default to 5]
 **offset** | **int32** | number of items to skip before starting to collect the result set | [default to 0]

### Return type

[**Poa**](Poa.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PoasPoaIdGet

> Poa PoasPoaIdGet(ctx, poaId).Execute()

Perform an operational action on a sliver.



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
	poaId := "poaId_example" // string | Poa Id for the POA triggered

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PoasAPI.PoasPoaIdGet(context.Background(), poaId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PoasAPI.PoasPoaIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PoasPoaIdGet`: Poa
	fmt.Fprintf(os.Stdout, "Response from `PoasAPI.PoasPoaIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poaId** | **string** | Poa Id for the POA triggered | 

### Other Parameters

Other parameters are passed through a pointer to a apiPoasPoaIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Poa**](Poa.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

