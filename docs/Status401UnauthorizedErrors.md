# Status401UnauthorizedErrors

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] [default to "Unauthorized"]
**Details** | Pointer to **string** |  | [optional] 

## Methods

### NewStatus401UnauthorizedErrors

`func NewStatus401UnauthorizedErrors() *Status401UnauthorizedErrors`

NewStatus401UnauthorizedErrors instantiates a new Status401UnauthorizedErrors object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatus401UnauthorizedErrorsWithDefaults

`func NewStatus401UnauthorizedErrorsWithDefaults() *Status401UnauthorizedErrors`

NewStatus401UnauthorizedErrorsWithDefaults instantiates a new Status401UnauthorizedErrors object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *Status401UnauthorizedErrors) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *Status401UnauthorizedErrors) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *Status401UnauthorizedErrors) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *Status401UnauthorizedErrors) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetDetails

`func (o *Status401UnauthorizedErrors) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *Status401UnauthorizedErrors) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *Status401UnauthorizedErrors) SetDetails(v string)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *Status401UnauthorizedErrors) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


