# TopologyRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **string** | Optional. DNS code to return if rule matches. Must be set if _destination_ is set to _code_.  Allowed values: - nodata - nxdomain  Defaults to _nodata_. | [optional] 
**Destination** | Pointer to **string** | Destination of __TopologyRule__.  Allowed values: - code - pool  Defaults to _code_. | [optional] 
**Name** | **string** | Display name of __TopologyRule__. | 
**PoolId** | Pointer to **string** | The resource identifier. | [optional] 
**Source** | Pointer to **string** | Type of source.  Allowed values: - subnet - tags - default  Defaults to _default_. | [optional] 
**Subnets** | Pointer to **[]string** | Optional. List of subnets in CIDR format.  Must be set if _source_ is _subnet_, otherwise must be empty. | [optional] 
**Tags** | Pointer to [**[]TagRule**](TagRule.md) | Optional. List of tag rules to match against a source object&#39;s effective tags. Effective tags &#x3D; direct tags plus tags inherited from the IPAM parent chain (IPSpace → Address Block → Subnet); the closer level wins on key conflicts. All rules use AND semantics: an object must satisfy every __TagRule__ to match.  Must be set if _source_ is _tags_, otherwise must be empty. | [optional] 

## Methods

### NewTopologyRule

`func NewTopologyRule(name string, ) *TopologyRule`

NewTopologyRule instantiates a new TopologyRule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTopologyRuleWithDefaults

`func NewTopologyRuleWithDefaults() *TopologyRule`

NewTopologyRuleWithDefaults instantiates a new TopologyRule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *TopologyRule) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *TopologyRule) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *TopologyRule) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *TopologyRule) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetDestination

`func (o *TopologyRule) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *TopologyRule) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *TopologyRule) SetDestination(v string)`

SetDestination sets Destination field to given value.

### HasDestination

`func (o *TopologyRule) HasDestination() bool`

HasDestination returns a boolean if a field has been set.

### GetName

`func (o *TopologyRule) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TopologyRule) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TopologyRule) SetName(v string)`

SetName sets Name field to given value.


### GetPoolId

`func (o *TopologyRule) GetPoolId() string`

GetPoolId returns the PoolId field if non-nil, zero value otherwise.

### GetPoolIdOk

`func (o *TopologyRule) GetPoolIdOk() (*string, bool)`

GetPoolIdOk returns a tuple with the PoolId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolId

`func (o *TopologyRule) SetPoolId(v string)`

SetPoolId sets PoolId field to given value.

### HasPoolId

`func (o *TopologyRule) HasPoolId() bool`

HasPoolId returns a boolean if a field has been set.

### GetSource

`func (o *TopologyRule) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *TopologyRule) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *TopologyRule) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *TopologyRule) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetSubnets

`func (o *TopologyRule) GetSubnets() []string`

GetSubnets returns the Subnets field if non-nil, zero value otherwise.

### GetSubnetsOk

`func (o *TopologyRule) GetSubnetsOk() (*[]string, bool)`

GetSubnetsOk returns a tuple with the Subnets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubnets

`func (o *TopologyRule) SetSubnets(v []string)`

SetSubnets sets Subnets field to given value.

### HasSubnets

`func (o *TopologyRule) HasSubnets() bool`

HasSubnets returns a boolean if a field has been set.

### GetTags

`func (o *TopologyRule) GetTags() []TagRule`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *TopologyRule) GetTagsOk() (*[]TagRule, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *TopologyRule) SetTags(v []TagRule)`

SetTags sets Tags field to given value.

### HasTags

`func (o *TopologyRule) HasTags() bool`

HasTags returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


