# PoaPost

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Operation** | **string** |  | 
**Data** | Pointer to [**PoaPostData**](PoaPostData.md) |  | [optional] 

## Methods

### NewPoaPost

`func NewPoaPost(operation string, ) *PoaPost`

NewPoaPost instantiates a new PoaPost object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPoaPostWithDefaults

`func NewPoaPostWithDefaults() *PoaPost`

NewPoaPostWithDefaults instantiates a new PoaPost object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOperation

`func (o *PoaPost) GetOperation() string`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *PoaPost) GetOperationOk() (*string, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *PoaPost) SetOperation(v string)`

SetOperation sets Operation field to given value.


### GetData

`func (o *PoaPost) GetData() PoaPostData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PoaPost) GetDataOk() (*PoaPostData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PoaPost) SetData(v PoaPostData)`

SetData sets Data field to given value.

### HasData

`func (o *PoaPost) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


