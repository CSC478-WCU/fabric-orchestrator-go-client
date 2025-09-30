# \MetricsAPI

All URIs are relative to *http://127.0.0.1:8700*

Method | HTTP request | Description
------------- | ------------- | -------------
[**MetricsOverviewGet**](MetricsAPI.md#MetricsOverviewGet) | **Get** /metrics/overview | Control Framework metrics overview



## MetricsOverviewGet

> Metrics MetricsOverviewGet(ctx).ExcludedProjects(excludedProjects).Execute()

Control Framework metrics overview



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
	excludedProjects := []string{"Inner_example"} // []string | List of projects to exclude from the metrics overview (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetricsAPI.MetricsOverviewGet(context.Background()).ExcludedProjects(excludedProjects).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetricsAPI.MetricsOverviewGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetricsOverviewGet`: Metrics
	fmt.Fprintf(os.Stdout, "Response from `MetricsAPI.MetricsOverviewGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMetricsOverviewGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **excludedProjects** | **[]string** | List of projects to exclude from the metrics overview | 

### Return type

[**Metrics**](Metrics.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

