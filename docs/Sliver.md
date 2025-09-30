# Sliver

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Notice** | Pointer to **string** |  | [optional] 
**SliverType** | Pointer to **string** |  | [optional] 
**Sliver** | Pointer to **map[string]interface{}** |  | [optional] 
**LeaseStartTime** | Pointer to **string** |  | [optional] 
**LeaseEndTime** | Pointer to **string** |  | [optional] 
**State** | Pointer to **string** |  | [optional] 
**PendingState** | Pointer to **string** |  | [optional] 
**JoinState** | Pointer to **string** |  | [optional] 
**GraphNodeId** | **string** |  | 
**SliceId** | **string** |  | 
**SliverId** | **string** |  | 
**OwnerUserId** | Pointer to **string** |  | [optional] 
**OwnerEmail** | Pointer to **string** |  | [optional] 

## Methods

### NewSliver

`func NewSliver(graphNodeId string, sliceId string, sliverId string, ) *Sliver`

NewSliver instantiates a new Sliver object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSliverWithDefaults

`func NewSliverWithDefaults() *Sliver`

NewSliverWithDefaults instantiates a new Sliver object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotice

`func (o *Sliver) GetNotice() string`

GetNotice returns the Notice field if non-nil, zero value otherwise.

### GetNoticeOk

`func (o *Sliver) GetNoticeOk() (*string, bool)`

GetNoticeOk returns a tuple with the Notice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotice

`func (o *Sliver) SetNotice(v string)`

SetNotice sets Notice field to given value.

### HasNotice

`func (o *Sliver) HasNotice() bool`

HasNotice returns a boolean if a field has been set.

### GetSliverType

`func (o *Sliver) GetSliverType() string`

GetSliverType returns the SliverType field if non-nil, zero value otherwise.

### GetSliverTypeOk

`func (o *Sliver) GetSliverTypeOk() (*string, bool)`

GetSliverTypeOk returns a tuple with the SliverType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSliverType

`func (o *Sliver) SetSliverType(v string)`

SetSliverType sets SliverType field to given value.

### HasSliverType

`func (o *Sliver) HasSliverType() bool`

HasSliverType returns a boolean if a field has been set.

### GetSliver

`func (o *Sliver) GetSliver() map[string]interface{}`

GetSliver returns the Sliver field if non-nil, zero value otherwise.

### GetSliverOk

`func (o *Sliver) GetSliverOk() (*map[string]interface{}, bool)`

GetSliverOk returns a tuple with the Sliver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSliver

`func (o *Sliver) SetSliver(v map[string]interface{})`

SetSliver sets Sliver field to given value.

### HasSliver

`func (o *Sliver) HasSliver() bool`

HasSliver returns a boolean if a field has been set.

### GetLeaseStartTime

`func (o *Sliver) GetLeaseStartTime() string`

GetLeaseStartTime returns the LeaseStartTime field if non-nil, zero value otherwise.

### GetLeaseStartTimeOk

`func (o *Sliver) GetLeaseStartTimeOk() (*string, bool)`

GetLeaseStartTimeOk returns a tuple with the LeaseStartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseStartTime

`func (o *Sliver) SetLeaseStartTime(v string)`

SetLeaseStartTime sets LeaseStartTime field to given value.

### HasLeaseStartTime

`func (o *Sliver) HasLeaseStartTime() bool`

HasLeaseStartTime returns a boolean if a field has been set.

### GetLeaseEndTime

`func (o *Sliver) GetLeaseEndTime() string`

GetLeaseEndTime returns the LeaseEndTime field if non-nil, zero value otherwise.

### GetLeaseEndTimeOk

`func (o *Sliver) GetLeaseEndTimeOk() (*string, bool)`

GetLeaseEndTimeOk returns a tuple with the LeaseEndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseEndTime

`func (o *Sliver) SetLeaseEndTime(v string)`

SetLeaseEndTime sets LeaseEndTime field to given value.

### HasLeaseEndTime

`func (o *Sliver) HasLeaseEndTime() bool`

HasLeaseEndTime returns a boolean if a field has been set.

### GetState

`func (o *Sliver) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *Sliver) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *Sliver) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *Sliver) HasState() bool`

HasState returns a boolean if a field has been set.

### GetPendingState

`func (o *Sliver) GetPendingState() string`

GetPendingState returns the PendingState field if non-nil, zero value otherwise.

### GetPendingStateOk

`func (o *Sliver) GetPendingStateOk() (*string, bool)`

GetPendingStateOk returns a tuple with the PendingState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingState

`func (o *Sliver) SetPendingState(v string)`

SetPendingState sets PendingState field to given value.

### HasPendingState

`func (o *Sliver) HasPendingState() bool`

HasPendingState returns a boolean if a field has been set.

### GetJoinState

`func (o *Sliver) GetJoinState() string`

GetJoinState returns the JoinState field if non-nil, zero value otherwise.

### GetJoinStateOk

`func (o *Sliver) GetJoinStateOk() (*string, bool)`

GetJoinStateOk returns a tuple with the JoinState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJoinState

`func (o *Sliver) SetJoinState(v string)`

SetJoinState sets JoinState field to given value.

### HasJoinState

`func (o *Sliver) HasJoinState() bool`

HasJoinState returns a boolean if a field has been set.

### GetGraphNodeId

`func (o *Sliver) GetGraphNodeId() string`

GetGraphNodeId returns the GraphNodeId field if non-nil, zero value otherwise.

### GetGraphNodeIdOk

`func (o *Sliver) GetGraphNodeIdOk() (*string, bool)`

GetGraphNodeIdOk returns a tuple with the GraphNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraphNodeId

`func (o *Sliver) SetGraphNodeId(v string)`

SetGraphNodeId sets GraphNodeId field to given value.


### GetSliceId

`func (o *Sliver) GetSliceId() string`

GetSliceId returns the SliceId field if non-nil, zero value otherwise.

### GetSliceIdOk

`func (o *Sliver) GetSliceIdOk() (*string, bool)`

GetSliceIdOk returns a tuple with the SliceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSliceId

`func (o *Sliver) SetSliceId(v string)`

SetSliceId sets SliceId field to given value.


### GetSliverId

`func (o *Sliver) GetSliverId() string`

GetSliverId returns the SliverId field if non-nil, zero value otherwise.

### GetSliverIdOk

`func (o *Sliver) GetSliverIdOk() (*string, bool)`

GetSliverIdOk returns a tuple with the SliverId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSliverId

`func (o *Sliver) SetSliverId(v string)`

SetSliverId sets SliverId field to given value.


### GetOwnerUserId

`func (o *Sliver) GetOwnerUserId() string`

GetOwnerUserId returns the OwnerUserId field if non-nil, zero value otherwise.

### GetOwnerUserIdOk

`func (o *Sliver) GetOwnerUserIdOk() (*string, bool)`

GetOwnerUserIdOk returns a tuple with the OwnerUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerUserId

`func (o *Sliver) SetOwnerUserId(v string)`

SetOwnerUserId sets OwnerUserId field to given value.

### HasOwnerUserId

`func (o *Sliver) HasOwnerUserId() bool`

HasOwnerUserId returns a boolean if a field has been set.

### GetOwnerEmail

`func (o *Sliver) GetOwnerEmail() string`

GetOwnerEmail returns the OwnerEmail field if non-nil, zero value otherwise.

### GetOwnerEmailOk

`func (o *Sliver) GetOwnerEmailOk() (*string, bool)`

GetOwnerEmailOk returns a tuple with the OwnerEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerEmail

`func (o *Sliver) SetOwnerEmail(v string)`

SetOwnerEmail sets OwnerEmail field to given value.

### HasOwnerEmail

`func (o *Sliver) HasOwnerEmail() bool`

HasOwnerEmail returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


