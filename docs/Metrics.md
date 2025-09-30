# Metrics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Size** | Pointer to **int32** |  | [optional] [default to 1]
**Status** | Pointer to **int32** |  | [optional] [default to 200]
**Type** | Pointer to **string** |  | [optional] 
**Results** | Pointer to **[]map[string]interface{}** |  | [optional] 

## Methods

### NewMetrics

`func NewMetrics() *Metrics`

NewMetrics instantiates a new Metrics object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMetricsWithDefaults

`func NewMetricsWithDefaults() *Metrics`

NewMetricsWithDefaults instantiates a new Metrics object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSize

`func (o *Metrics) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Metrics) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Metrics) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *Metrics) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetStatus

`func (o *Metrics) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Metrics) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Metrics) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Metrics) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *Metrics) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Metrics) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Metrics) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Metrics) HasType() bool`

HasType returns a boolean if a field has been set.

### GetResults

`func (o *Metrics) GetResults() []map[string]interface{}`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *Metrics) GetResultsOk() (*[]map[string]interface{}, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *Metrics) SetResults(v []map[string]interface{})`

SetResults sets Results field to given value.

### HasResults

`func (o *Metrics) HasResults() bool`

HasResults returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


