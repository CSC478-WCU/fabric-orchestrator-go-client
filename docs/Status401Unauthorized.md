# Status401Unauthorized

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Errors** | Pointer to [**[]Status401UnauthorizedErrors**](Status401UnauthorizedErrors.md) |  | [optional] 
**Type** | Pointer to **string** |  | [optional] [default to "error"]
**Size** | Pointer to **int32** |  | [optional] [default to 1]
**Status** | Pointer to **int32** |  | [optional] [default to 401]

## Methods

### NewStatus401Unauthorized

`func NewStatus401Unauthorized() *Status401Unauthorized`

NewStatus401Unauthorized instantiates a new Status401Unauthorized object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatus401UnauthorizedWithDefaults

`func NewStatus401UnauthorizedWithDefaults() *Status401Unauthorized`

NewStatus401UnauthorizedWithDefaults instantiates a new Status401Unauthorized object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrors

`func (o *Status401Unauthorized) GetErrors() []Status401UnauthorizedErrors`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *Status401Unauthorized) GetErrorsOk() (*[]Status401UnauthorizedErrors, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *Status401Unauthorized) SetErrors(v []Status401UnauthorizedErrors)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *Status401Unauthorized) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetType

`func (o *Status401Unauthorized) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Status401Unauthorized) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Status401Unauthorized) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Status401Unauthorized) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSize

`func (o *Status401Unauthorized) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Status401Unauthorized) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Status401Unauthorized) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *Status401Unauthorized) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetStatus

`func (o *Status401Unauthorized) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Status401Unauthorized) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Status401Unauthorized) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Status401Unauthorized) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


