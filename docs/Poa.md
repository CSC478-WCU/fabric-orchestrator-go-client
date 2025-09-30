# Poa

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Size** | Pointer to **int32** |  | [optional] [default to 1]
**Status** | Pointer to **int32** |  | [optional] [default to 200]
**Type** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]PoaData**](PoaData.md) |  | [optional] 

## Methods

### NewPoa

`func NewPoa() *Poa`

NewPoa instantiates a new Poa object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPoaWithDefaults

`func NewPoaWithDefaults() *Poa`

NewPoaWithDefaults instantiates a new Poa object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSize

`func (o *Poa) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Poa) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Poa) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *Poa) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetStatus

`func (o *Poa) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Poa) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Poa) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Poa) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *Poa) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Poa) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Poa) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Poa) HasType() bool`

HasType returns a boolean if a field has been set.

### GetData

`func (o *Poa) GetData() []PoaData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Poa) GetDataOk() (*[]PoaData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Poa) SetData(v []PoaData)`

SetData sets Data field to given value.

### HasData

`func (o *Poa) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


