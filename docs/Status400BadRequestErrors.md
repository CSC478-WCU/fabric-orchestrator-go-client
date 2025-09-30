# Status400BadRequestErrors

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] [default to "Bad Request"]
**Details** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] [default to "error"]
**Size** | Pointer to **int32** |  | [optional] [default to 1]
**Status** | Pointer to **int32** |  | [optional] [default to 400]

## Methods

### NewStatus400BadRequestErrors

`func NewStatus400BadRequestErrors() *Status400BadRequestErrors`

NewStatus400BadRequestErrors instantiates a new Status400BadRequestErrors object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatus400BadRequestErrorsWithDefaults

`func NewStatus400BadRequestErrorsWithDefaults() *Status400BadRequestErrors`

NewStatus400BadRequestErrorsWithDefaults instantiates a new Status400BadRequestErrors object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *Status400BadRequestErrors) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *Status400BadRequestErrors) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *Status400BadRequestErrors) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *Status400BadRequestErrors) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetDetails

`func (o *Status400BadRequestErrors) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *Status400BadRequestErrors) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *Status400BadRequestErrors) SetDetails(v string)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *Status400BadRequestErrors) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetType

`func (o *Status400BadRequestErrors) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Status400BadRequestErrors) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Status400BadRequestErrors) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Status400BadRequestErrors) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSize

`func (o *Status400BadRequestErrors) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Status400BadRequestErrors) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Status400BadRequestErrors) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *Status400BadRequestErrors) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetStatus

`func (o *Status400BadRequestErrors) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Status400BadRequestErrors) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Status400BadRequestErrors) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Status400BadRequestErrors) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


