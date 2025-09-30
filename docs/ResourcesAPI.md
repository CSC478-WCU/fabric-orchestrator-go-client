# \ResourcesAPI

All URIs are relative to *http://127.0.0.1:8700*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PortalresourcesGet**](ResourcesAPI.md#PortalresourcesGet) | **Get** /portalresources | Retrieve a listing and description of available resources for portal
[**ResourcesGet**](ResourcesAPI.md#ResourcesGet) | **Get** /resources | Retrieve a listing and description of available resources. By default, a cached available resource information is returned. User can force to request the current available resources.



## PortalresourcesGet

> Resources PortalresourcesGet(ctx).GraphFormat(graphFormat).Level(level).ForceRefresh(forceRefresh).StartDate(startDate).EndDate(endDate).Includes(includes).Excludes(excludes).Execute()

Retrieve a listing and description of available resources for portal



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
	graphFormat := "graphFormat_example" // string | graph format (default to "GRAPHML")
	level := int32(56) // int32 | Level of details (optional) (default to 1)
	forceRefresh := true // bool | Force to retrieve current available resource information. (optional) (default to false)
	startDate := "2023-01-01 16:20:15 +00:00" // string | starting date to check availability from (optional)
	endDate := "2023-01-01 16:20:15 +00:00" // string | end date to check availability until (optional)
	includes := "RENC,UKY" // string | comma separated lists of sites to include (optional)
	excludes := "SRI,LBNL" // string | comma separated lists of sites to exclude (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResourcesAPI.PortalresourcesGet(context.Background()).GraphFormat(graphFormat).Level(level).ForceRefresh(forceRefresh).StartDate(startDate).EndDate(endDate).Includes(includes).Excludes(excludes).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResourcesAPI.PortalresourcesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PortalresourcesGet`: Resources
	fmt.Fprintf(os.Stdout, "Response from `ResourcesAPI.PortalresourcesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPortalresourcesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **graphFormat** | **string** | graph format | [default to &quot;GRAPHML&quot;]
 **level** | **int32** | Level of details | [default to 1]
 **forceRefresh** | **bool** | Force to retrieve current available resource information. | [default to false]
 **startDate** | **string** | starting date to check availability from | 
 **endDate** | **string** | end date to check availability until | 
 **includes** | **string** | comma separated lists of sites to include | 
 **excludes** | **string** | comma separated lists of sites to exclude | 

### Return type

[**Resources**](Resources.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResourcesGet

> Resources ResourcesGet(ctx).Level(level).ForceRefresh(forceRefresh).StartDate(startDate).EndDate(endDate).Includes(includes).Excludes(excludes).Execute()

Retrieve a listing and description of available resources. By default, a cached available resource information is returned. User can force to request the current available resources.



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
	level := int32(56) // int32 | Level of details (default to 1)
	forceRefresh := true // bool | Force to retrieve current available resource information. (default to false)
	startDate := "2023-01-01 16:20:15 +00:00" // string | starting date to check availability from (optional)
	endDate := "2023-01-01 16:20:15 +00:00" // string | end date to check availability until (optional)
	includes := "RENC,UKY" // string | comma separated lists of sites to include (optional)
	excludes := "SRI,LBNL" // string | comma separated lists of sites to exclude (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResourcesAPI.ResourcesGet(context.Background()).Level(level).ForceRefresh(forceRefresh).StartDate(startDate).EndDate(endDate).Includes(includes).Excludes(excludes).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResourcesAPI.ResourcesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResourcesGet`: Resources
	fmt.Fprintf(os.Stdout, "Response from `ResourcesAPI.ResourcesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiResourcesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **level** | **int32** | Level of details | [default to 1]
 **forceRefresh** | **bool** | Force to retrieve current available resource information. | [default to false]
 **startDate** | **string** | starting date to check availability from | 
 **endDate** | **string** | end date to check availability until | 
 **includes** | **string** | comma separated lists of sites to include | 
 **excludes** | **string** | comma separated lists of sites to exclude | 

### Return type

[**Resources**](Resources.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

