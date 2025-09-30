# Slivers

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | Pointer to **int32** |  | [optional] 
**Offset** | Pointer to **int32** |  | [optional] 
**Size** | Pointer to **int32** |  | [optional] 
**Status** | Pointer to **int32** |  | [optional] [default to 200]
**Total** | Pointer to **int32** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]Sliver**](Sliver.md) |  | [optional] 

## Methods

### NewSlivers

`func NewSlivers() *Slivers`

NewSlivers instantiates a new Slivers object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSliversWithDefaults

`func NewSliversWithDefaults() *Slivers`

NewSliversWithDefaults instantiates a new Slivers object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *Slivers) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *Slivers) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *Slivers) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *Slivers) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetOffset

`func (o *Slivers) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *Slivers) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *Slivers) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *Slivers) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetSize

`func (o *Slivers) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Slivers) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Slivers) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *Slivers) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetStatus

`func (o *Slivers) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Slivers) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Slivers) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Slivers) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTotal

`func (o *Slivers) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *Slivers) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *Slivers) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *Slivers) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetType

`func (o *Slivers) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Slivers) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Slivers) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Slivers) HasType() bool`

HasType returns a boolean if a field has been set.

### GetData

`func (o *Slivers) GetData() []Sliver`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Slivers) GetDataOk() (*[]Sliver, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Slivers) SetData(v []Sliver)`

SetData sets Data field to given value.

### HasData

`func (o *Slivers) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


