# SystemHaGet200ResponseVclusterInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vcluster_id** | **int** | ID. | [optional] 
**override** | **str** | Enable and increase the priority of the unit that should always be primary (master).    enable:Enable setting.    disable:Disable setting. | [optional] 
**priority** | **int** | Increase the priority to select the primary unit (0 - 255). | [optional] 
**override_wait_time** | **int** | Delay negotiating if override is enabled (0 - 3600 sec). Reduces how often the cluster negotiates. | [optional] 
**monitor** | **str** | Interfaces to check for port monitoring (or link failure). | [optional] 
**pingserver_monitor_interface** | **str** | Interfaces to check for remote IP monitoring. | [optional] 
**pingserver_failover_threshold** | **int** | Remote IP monitoring failover threshold (0 - 50). | [optional] 
**pingserver_secondary_force_reset** | **str** | Enable to force the cluster to negotiate after a remote IP monitoring failover.    enable:Enable force reset of secondary member after PING server failure.    disable:Disable force reset of secondary member after PING server failure. | [optional] 
**pingserver_flip_timeout** | **int** | Time to wait in minutes before renegotiating after a remote IP monitoring failover. | [optional] 
**vdom** | [**List[SystemAdminNameGet200ResponseVdomInner]**](SystemAdminNameGet200ResponseVdomInner.md) | Virtual domain(s) in the virtual cluster. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ha_get200_response_vcluster_inner import SystemHaGet200ResponseVclusterInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemHaGet200ResponseVclusterInner from a JSON string
system_ha_get200_response_vcluster_inner_instance = SystemHaGet200ResponseVclusterInner.from_json(json)
# print the JSON string representation of the object
print(SystemHaGet200ResponseVclusterInner.to_json())

# convert the object into a dict
system_ha_get200_response_vcluster_inner_dict = system_ha_get200_response_vcluster_inner_instance.to_dict()
# create an instance of SystemHaGet200ResponseVclusterInner from a dict
system_ha_get200_response_vcluster_inner_from_dict = SystemHaGet200ResponseVclusterInner.from_dict(system_ha_get200_response_vcluster_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


