# SliceDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Size** | Pointer to **int32** |  | [optional] [default to 1]
**Status** | Pointer to **int32** |  | [optional] [default to 200]
**Type** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]Slice**](Slice.md) |  | [optional] 

## Methods

### NewSliceDetails

`func NewSliceDetails() *SliceDetails`

NewSliceDetails instantiates a new SliceDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSliceDetailsWithDefaults

`func NewSliceDetailsWithDefaults() *SliceDetails`

NewSliceDetailsWithDefaults instantiates a new SliceDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSize

`func (o *SliceDetails) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *SliceDetails) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *SliceDetails) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *SliceDetails) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetStatus

`func (o *SliceDetails) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SliceDetails) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SliceDetails) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SliceDetails) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *SliceDetails) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SliceDetails) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SliceDetails) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SliceDetails) HasType() bool`

HasType returns a boolean if a field has been set.

### GetData

`func (o *SliceDetails) GetData() []Slice`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SliceDetails) GetDataOk() (*[]Slice, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SliceDetails) SetData(v []Slice)`

SetData sets Data field to given value.

### HasData

`func (o *SliceDetails) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


