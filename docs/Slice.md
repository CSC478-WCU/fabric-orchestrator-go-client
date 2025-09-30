# Slice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | Pointer to **string** |  | [optional] 
**LeaseStartTime** | Pointer to **string** |  | [optional] 
**LeaseEndTime** | Pointer to **string** |  | [optional] 
**State** | Pointer to **string** |  | [optional] 
**ProjectId** | Pointer to **string** |  | [optional] 
**ProjectName** | Pointer to **string** |  | [optional] 
**GraphId** | **string** |  | 
**Name** | **string** |  | 
**SliceId** | **string** |  | 
**OwnerUserId** | Pointer to **string** |  | [optional] 
**OwnerEmail** | Pointer to **string** |  | [optional] 

## Methods

### NewSlice

`func NewSlice(graphId string, name string, sliceId string, ) *Slice`

NewSlice instantiates a new Slice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSliceWithDefaults

`func NewSliceWithDefaults() *Slice`

NewSliceWithDefaults instantiates a new Slice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *Slice) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *Slice) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *Slice) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *Slice) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetLeaseStartTime

`func (o *Slice) GetLeaseStartTime() string`

GetLeaseStartTime returns the LeaseStartTime field if non-nil, zero value otherwise.

### GetLeaseStartTimeOk

`func (o *Slice) GetLeaseStartTimeOk() (*string, bool)`

GetLeaseStartTimeOk returns a tuple with the LeaseStartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseStartTime

`func (o *Slice) SetLeaseStartTime(v string)`

SetLeaseStartTime sets LeaseStartTime field to given value.

### HasLeaseStartTime

`func (o *Slice) HasLeaseStartTime() bool`

HasLeaseStartTime returns a boolean if a field has been set.

### GetLeaseEndTime

`func (o *Slice) GetLeaseEndTime() string`

GetLeaseEndTime returns the LeaseEndTime field if non-nil, zero value otherwise.

### GetLeaseEndTimeOk

`func (o *Slice) GetLeaseEndTimeOk() (*string, bool)`

GetLeaseEndTimeOk returns a tuple with the LeaseEndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseEndTime

`func (o *Slice) SetLeaseEndTime(v string)`

SetLeaseEndTime sets LeaseEndTime field to given value.

### HasLeaseEndTime

`func (o *Slice) HasLeaseEndTime() bool`

HasLeaseEndTime returns a boolean if a field has been set.

### GetState

`func (o *Slice) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *Slice) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *Slice) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *Slice) HasState() bool`

HasState returns a boolean if a field has been set.

### GetProjectId

`func (o *Slice) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *Slice) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *Slice) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *Slice) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProjectName

`func (o *Slice) GetProjectName() string`

GetProjectName returns the ProjectName field if non-nil, zero value otherwise.

### GetProjectNameOk

`func (o *Slice) GetProjectNameOk() (*string, bool)`

GetProjectNameOk returns a tuple with the ProjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectName

`func (o *Slice) SetProjectName(v string)`

SetProjectName sets ProjectName field to given value.

### HasProjectName

`func (o *Slice) HasProjectName() bool`

HasProjectName returns a boolean if a field has been set.

### GetGraphId

`func (o *Slice) GetGraphId() string`

GetGraphId returns the GraphId field if non-nil, zero value otherwise.

### GetGraphIdOk

`func (o *Slice) GetGraphIdOk() (*string, bool)`

GetGraphIdOk returns a tuple with the GraphId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraphId

`func (o *Slice) SetGraphId(v string)`

SetGraphId sets GraphId field to given value.


### GetName

`func (o *Slice) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Slice) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Slice) SetName(v string)`

SetName sets Name field to given value.


### GetSliceId

`func (o *Slice) GetSliceId() string`

GetSliceId returns the SliceId field if non-nil, zero value otherwise.

### GetSliceIdOk

`func (o *Slice) GetSliceIdOk() (*string, bool)`

GetSliceIdOk returns a tuple with the SliceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSliceId

`func (o *Slice) SetSliceId(v string)`

SetSliceId sets SliceId field to given value.


### GetOwnerUserId

`func (o *Slice) GetOwnerUserId() string`

GetOwnerUserId returns the OwnerUserId field if non-nil, zero value otherwise.

### GetOwnerUserIdOk

`func (o *Slice) GetOwnerUserIdOk() (*string, bool)`

GetOwnerUserIdOk returns a tuple with the OwnerUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerUserId

`func (o *Slice) SetOwnerUserId(v string)`

SetOwnerUserId sets OwnerUserId field to given value.

### HasOwnerUserId

`func (o *Slice) HasOwnerUserId() bool`

HasOwnerUserId returns a boolean if a field has been set.

### GetOwnerEmail

`func (o *Slice) GetOwnerEmail() string`

GetOwnerEmail returns the OwnerEmail field if non-nil, zero value otherwise.

### GetOwnerEmailOk

`func (o *Slice) GetOwnerEmailOk() (*string, bool)`

GetOwnerEmailOk returns a tuple with the OwnerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerEmail

`func (o *Slice) SetOwnerEmail(v string)`

SetOwnerEmail sets OwnerEmail field to given value.

### HasOwnerEmail

`func (o *Slice) HasOwnerEmail() bool`

HasOwnerEmail returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


