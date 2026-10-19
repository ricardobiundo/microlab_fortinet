# SystemHaMonitorGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**monitor_vlan** | **str** | Enable/disable monitor VLAN interfaces.    enable:Enable monitor VLAN interfaces.    disable:Disable monitor VLAN interfaces. | [optional] 
**vlan_hb_interval** | **int** | Configure heartbeat interval (seconds). | [optional] 
**vlan_hb_lost_threshold** | **int** | VLAN lost heartbeat threshold (1 - 60). | [optional] 

## Example

```python
from microlab_fortinet.models.system_ha_monitor_get200_response import SystemHaMonitorGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemHaMonitorGet200Response from a JSON string
system_ha_monitor_get200_response_instance = SystemHaMonitorGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemHaMonitorGet200Response.to_json())

# convert the object into a dict
system_ha_monitor_get200_response_dict = system_ha_monitor_get200_response_instance.to_dict()
# create an instance of SystemHaMonitorGet200Response from a dict
system_ha_monitor_get200_response_from_dict = SystemHaMonitorGet200Response.from_dict(system_ha_monitor_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


