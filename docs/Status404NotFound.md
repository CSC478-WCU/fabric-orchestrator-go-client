# Status404NotFound

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Errors** | Pointer to [**[]Status404NotFoundErrors**](Status404NotFoundErrors.md) |  | [optional] 
**Type** | Pointer to **string** |  | [optional] [default to "error"]
**Size** | Pointer to **int32** |  | [optional] [default to 1]
**Status** | Pointer to **int32** |  | [optional] [default to 404]

## Methods

### NewStatus404NotFound

`func NewStatus404NotFound() *Status404NotFound`

NewStatus404NotFound instantiates a new Status404NotFound object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatus404NotFoundWithDefaults

`func NewStatus404NotFoundWithDefaults() *Status404NotFound`

NewStatus404NotFoundWithDefaults instantiates a new Status404NotFound object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrors

`func (o *Status404NotFound) GetErrors() []Status404NotFoundErrors`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *Status404NotFound) GetErrorsOk() (*[]Status404NotFoundErrors, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *Status404NotFound) SetErrors(v []Status404NotFoundErrors)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *Status404NotFound) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetType

`func (o *Status404NotFound) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Status404NotFound) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Status404NotFound) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Status404NotFound) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSize

`func (o *Status404NotFound) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Status404NotFound) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Status404NotFound) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *Status404NotFound) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetStatus

`func (o *Status404NotFound) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Status404NotFound) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Status404NotFound) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Status404NotFound) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


