# SystemStandaloneClusterGet200ResponseMonitorPrefixInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**vdom** | **str** | VDOM name. | [optional] 
**vrf** | **int** | VRF ID. | [optional] 
**prefix** | **str** | Prefix. | [optional] 

## Example

```python
from microlab_fortinet.models.system_standalone_cluster_get200_response_monitor_prefix_inner import SystemStandaloneClusterGet200ResponseMonitorPrefixInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStandaloneClusterGet200ResponseMonitorPrefixInner from a JSON string
system_standalone_cluster_get200_response_monitor_prefix_inner_instance = SystemStandaloneClusterGet200ResponseMonitorPrefixInner.from_json(json)
# print the JSON string representation of the object
print(SystemStandaloneClusterGet200ResponseMonitorPrefixInner.to_json())

# convert the object into a dict
system_standalone_cluster_get200_response_monitor_prefix_inner_dict = system_standalone_cluster_get200_response_monitor_prefix_inner_instance.to_dict()
# create an instance of SystemStandaloneClusterGet200ResponseMonitorPrefixInner from a dict
system_standalone_cluster_get200_response_monitor_prefix_inner_from_dict = SystemStandaloneClusterGet200ResponseMonitorPrefixInner.from_dict(system_standalone_cluster_get200_response_monitor_prefix_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


