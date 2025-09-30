# Resources

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Size** | Pointer to **int32** |  | [optional] [default to 1]
**Status** | Pointer to **int32** |  | [optional] [default to 200]
**Type** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]Resource**](Resource.md) |  | [optional] 

## Methods

### NewResources

`func NewResources() *Resources`

NewResources instantiates a new Resources object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResourcesWithDefaults

`func NewResourcesWithDefaults() *Resources`

NewResourcesWithDefaults instantiates a new Resources object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSize

`func (o *Resources) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Resources) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Resources) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *Resources) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetStatus

`func (o *Resources) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Resources) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Resources) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Resources) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *Resources) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Resources) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Resources) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Resources) HasType() bool`

HasType returns a boolean if a field has been set.

### GetData

`func (o *Resources) GetData() []Resource`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Resources) GetDataOk() (*[]Resource, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Resources) SetData(v []Resource)`

SetData sets Data field to given value.

### HasData

`func (o *Resources) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


