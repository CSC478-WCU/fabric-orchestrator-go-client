# Status404NotFoundErrors

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] [default to "Not Found"]
**Details** | Pointer to **string** |  | [optional] 

## Methods

### NewStatus404NotFoundErrors

`func NewStatus404NotFoundErrors() *Status404NotFoundErrors`

NewStatus404NotFoundErrors instantiates a new Status404NotFoundErrors object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatus404NotFoundErrorsWithDefaults

`func NewStatus404NotFoundErrorsWithDefaults() *Status404NotFoundErrors`

NewStatus404NotFoundErrorsWithDefaults instantiates a new Status404NotFoundErrors object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *Status404NotFoundErrors) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *Status404NotFoundErrors) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *Status404NotFoundErrors) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *Status404NotFoundErrors) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetDetails

`func (o *Status404NotFoundErrors) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *Status404NotFoundErrors) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *Status404NotFoundErrors) SetDetails(v string)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *Status404NotFoundErrors) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


