# PoaPostData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VcpuCpuMap** | Pointer to [**[]PoaPostDataVcpuCpuMap**](PoaPostDataVcpuCpuMap.md) |  | [optional] 
**NodeSet** | Pointer to **[]string** |  | [optional] 
**Bdf** | Pointer to **[]string** |  | [optional] 
**Keys** | Pointer to [**[]PoaPostDataKeys**](PoaPostDataKeys.md) |  | [optional] 

## Methods

### NewPoaPostData

`func NewPoaPostData() *PoaPostData`

NewPoaPostData instantiates a new PoaPostData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPoaPostDataWithDefaults

`func NewPoaPostDataWithDefaults() *PoaPostData`

NewPoaPostDataWithDefaults instantiates a new PoaPostData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVcpuCpuMap

`func (o *PoaPostData) GetVcpuCpuMap() []PoaPostDataVcpuCpuMap`

GetVcpuCpuMap returns the VcpuCpuMap field if non-nil, zero value otherwise.

### GetVcpuCpuMapOk

`func (o *PoaPostData) GetVcpuCpuMapOk() (*[]PoaPostDataVcpuCpuMap, bool)`

GetVcpuCpuMapOk returns a tuple with the VcpuCpuMap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVcpuCpuMap

`func (o *PoaPostData) SetVcpuCpuMap(v []PoaPostDataVcpuCpuMap)`

SetVcpuCpuMap sets VcpuCpuMap field to given value.

### HasVcpuCpuMap

`func (o *PoaPostData) HasVcpuCpuMap() bool`

HasVcpuCpuMap returns a boolean if a field has been set.

### GetNodeSet

`func (o *PoaPostData) GetNodeSet() []string`

GetNodeSet returns the NodeSet field if non-nil, zero value otherwise.

### GetNodeSetOk

`func (o *PoaPostData) GetNodeSetOk() (*[]string, bool)`

GetNodeSetOk returns a tuple with the NodeSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeSet

`func (o *PoaPostData) SetNodeSet(v []string)`

SetNodeSet sets NodeSet field to given value.

### HasNodeSet

`func (o *PoaPostData) HasNodeSet() bool`

HasNodeSet returns a boolean if a field has been set.

### GetBdf

`func (o *PoaPostData) GetBdf() []string`

GetBdf returns the Bdf field if non-nil, zero value otherwise.

### GetBdfOk

`func (o *PoaPostData) GetBdfOk() (*[]string, bool)`

GetBdfOk returns a tuple with the Bdf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBdf

`func (o *PoaPostData) SetBdf(v []string)`

SetBdf sets Bdf field to given value.

### HasBdf

`func (o *PoaPostData) HasBdf() bool`

HasBdf returns a boolean if a field has been set.

### GetKeys

`func (o *PoaPostData) GetKeys() []PoaPostDataKeys`

GetKeys returns the Keys field if non-nil, zero value otherwise.

### GetKeysOk

`func (o *PoaPostData) GetKeysOk() (*[]PoaPostDataKeys, bool)`

GetKeysOk returns a tuple with the Keys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeys

`func (o *PoaPostData) SetKeys(v []PoaPostDataKeys)`

SetKeys sets Keys field to given value.

### HasKeys

`func (o *PoaPostData) HasKeys() bool`

HasKeys returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


