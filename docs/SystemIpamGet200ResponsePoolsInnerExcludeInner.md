# SystemIpamGet200ResponsePoolsInnerExcludeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Exclude ID. | [optional] 
**exclude_subnet** | **str** | Configure subnet to exclude from the IPAM pool. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ipam_get200_response_pools_inner_exclude_inner import SystemIpamGet200ResponsePoolsInnerExcludeInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIpamGet200ResponsePoolsInnerExcludeInner from a JSON string
system_ipam_get200_response_pools_inner_exclude_inner_instance = SystemIpamGet200ResponsePoolsInnerExcludeInner.from_json(json)
# print the JSON string representation of the object
print(SystemIpamGet200ResponsePoolsInnerExcludeInner.to_json())

# convert the object into a dict
system_ipam_get200_response_pools_inner_exclude_inner_dict = system_ipam_get200_response_pools_inner_exclude_inner_instance.to_dict()
# create an instance of SystemIpamGet200ResponsePoolsInnerExcludeInner from a dict
system_ipam_get200_response_pools_inner_exclude_inner_from_dict = SystemIpamGet200ResponsePoolsInnerExcludeInner.from_dict(system_ipam_get200_response_pools_inner_exclude_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


