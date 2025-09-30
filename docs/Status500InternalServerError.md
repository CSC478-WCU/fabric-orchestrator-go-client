# Status500InternalServerError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Errors** | Pointer to [**[]Status500InternalServerErrorErrors**](Status500InternalServerErrorErrors.md) |  | [optional] 
**Type** | Pointer to **string** |  | [optional] [default to "error"]
**Size** | Pointer to **int32** |  | [optional] [default to 1]
**Status** | Pointer to **int32** |  | [optional] [default to 500]

## Methods

### NewStatus500InternalServerError

`func NewStatus500InternalServerError() *Status500InternalServerError`

NewStatus500InternalServerError instantiates a new Status500InternalServerError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatus500InternalServerErrorWithDefaults

`func NewStatus500InternalServerErrorWithDefaults() *Status500InternalServerError`

NewStatus500InternalServerErrorWithDefaults instantiates a new Status500InternalServerError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrors

`func (o *Status500InternalServerError) GetErrors() []Status500InternalServerErrorErrors`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *Status500InternalServerError) GetErrorsOk() (*[]Status500InternalServerErrorErrors, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *Status500InternalServerError) SetErrors(v []Status500InternalServerErrorErrors)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *Status500InternalServerError) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetType

`func (o *Status500InternalServerError) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Status500InternalServerError) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Status500InternalServerError) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Status500InternalServerError) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSize

`func (o *Status500InternalServerError) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Status500InternalServerError) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Status500InternalServerError) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *Status500InternalServerError) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetStatus

`func (o *Status500InternalServerError) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Status500InternalServerError) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Status500InternalServerError) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Status500InternalServerError) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


