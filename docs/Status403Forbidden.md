# Status403Forbidden

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Errors** | Pointer to [**[]Status403ForbiddenErrors**](Status403ForbiddenErrors.md) |  | [optional] 
**Type** | Pointer to **string** |  | [optional] [default to "error"]
**Size** | Pointer to **int32** |  | [optional] [default to 1]
**Status** | Pointer to **int32** |  | [optional] [default to 403]

## Methods

### NewStatus403Forbidden

`func NewStatus403Forbidden() *Status403Forbidden`

NewStatus403Forbidden instantiates a new Status403Forbidden object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatus403ForbiddenWithDefaults

`func NewStatus403ForbiddenWithDefaults() *Status403Forbidden`

NewStatus403ForbiddenWithDefaults instantiates a new Status403Forbidden object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrors

`func (o *Status403Forbidden) GetErrors() []Status403ForbiddenErrors`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *Status403Forbidden) GetErrorsOk() (*[]Status403ForbiddenErrors, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *Status403Forbidden) SetErrors(v []Status403ForbiddenErrors)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *Status403Forbidden) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetType

`func (o *Status403Forbidden) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Status403Forbidden) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Status403Forbidden) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Status403Forbidden) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSize

`func (o *Status403Forbidden) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Status403Forbidden) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Status403Forbidden) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *Status403Forbidden) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetStatus

`func (o *Status403Forbidden) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Status403Forbidden) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Status403Forbidden) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Status403Forbidden) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


