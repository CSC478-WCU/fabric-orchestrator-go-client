# Status200OkNoContent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]Status200OkNoContentData**](Status200OkNoContentData.md) |  | [optional] 
**Type** | Pointer to **string** |  | [optional] [default to "no_content"]
**Size** | Pointer to **int32** |  | [optional] [default to 1]
**Status** | Pointer to **int32** |  | [optional] [default to 200]

## Methods

### NewStatus200OkNoContent

`func NewStatus200OkNoContent() *Status200OkNoContent`

NewStatus200OkNoContent instantiates a new Status200OkNoContent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatus200OkNoContentWithDefaults

`func NewStatus200OkNoContentWithDefaults() *Status200OkNoContent`

NewStatus200OkNoContentWithDefaults instantiates a new Status200OkNoContent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *Status200OkNoContent) GetData() []Status200OkNoContentData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Status200OkNoContent) GetDataOk() (*[]Status200OkNoContentData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Status200OkNoContent) SetData(v []Status200OkNoContentData)`

SetData sets Data field to given value.

### HasData

`func (o *Status200OkNoContent) HasData() bool`

HasData returns a boolean if a field has been set.

### GetType

`func (o *Status200OkNoContent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Status200OkNoContent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Status200OkNoContent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Status200OkNoContent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSize

`func (o *Status200OkNoContent) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Status200OkNoContent) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Status200OkNoContent) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *Status200OkNoContent) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetStatus

`func (o *Status200OkNoContent) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Status200OkNoContent) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Status200OkNoContent) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Status200OkNoContent) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


