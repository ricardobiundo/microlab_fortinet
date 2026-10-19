# SystemIpamGet200ResponsePoolsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | IPAM pool name. | [optional] 
**description** | **str** | Description. | [optional] 
**subnet** | **str** | Configure IPAM pool subnet, Class A - Class B subnet. | [optional] 
**exclude** | [**List[SystemIpamGet200ResponsePoolsInnerExcludeInner]**](SystemIpamGet200ResponsePoolsInnerExcludeInner.md) | Configure pool exclude subnets. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ipam_get200_response_pools_inner import SystemIpamGet200ResponsePoolsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIpamGet200ResponsePoolsInner from a JSON string
system_ipam_get200_response_pools_inner_instance = SystemIpamGet200ResponsePoolsInner.from_json(json)
# print the JSON string representation of the object
print(SystemIpamGet200ResponsePoolsInner.to_json())

# convert the object into a dict
system_ipam_get200_response_pools_inner_dict = system_ipam_get200_response_pools_inner_instance.to_dict()
# create an instance of SystemIpamGet200ResponsePoolsInner from a dict
system_ipam_get200_response_pools_inner_from_dict = SystemIpamGet200ResponsePoolsInner.from_dict(system_ipam_get200_response_pools_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


