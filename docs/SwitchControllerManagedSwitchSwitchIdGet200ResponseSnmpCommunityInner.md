# SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | SNMP community ID. | [optional] 
**name** | **str** | SNMP community name. | [optional] 
**status** | **str** | Enable/disable this SNMP community.    disable:Disable SNMP community.    enable:Enable SNMP community. | [optional] 
**hosts** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInnerHostsInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInnerHostsInner.md) | Configure IPv4 SNMP managers (hosts). | [optional] 
**query_v1_status** | **str** | Enable/disable SNMP v1 queries.    disable:Disable SNMP v1 queries.    enable:Enable SNMP v1 queries. | [optional] 
**query_v1_port** | **int** | SNMP v1 query port (default &#x3D; 161). | [optional] 
**query_v2c_status** | **str** | Enable/disable SNMP v2c queries.    disable:Disable SNMP v2c queries.    enable:Enable SNMP v2c queries. | [optional] 
**query_v2c_port** | **int** | SNMP v2c query port (default &#x3D; 161). | [optional] 
**trap_v1_status** | **str** | Enable/disable SNMP v1 traps.    disable:Disable SNMP v1 traps.    enable:Enable SNMP v1 traps. | [optional] 
**trap_v1_lport** | **int** | SNMP v2c trap local port (default &#x3D; 162). | [optional] 
**trap_v1_rport** | **int** | SNMP v2c trap remote port (default &#x3D; 162). | [optional] 
**trap_v2c_status** | **str** | Enable/disable SNMP v2c traps.    disable:Disable SNMP v2c traps.    enable:Enable SNMP v2c traps. | [optional] 
**trap_v2c_lport** | **int** | SNMP v2c trap local port (default &#x3D; 162). | [optional] 
**trap_v2c_rport** | **int** | SNMP v2c trap remote port (default &#x3D; 162). | [optional] 
**events** | **str** | SNMP notifications (traps) to send.    cpu-high:Send a trap when CPU usage too high.    mem-low:Send a trap when available memory is low.    log-full:Send a trap when log disk space becomes low.    intf-ip:Send a trap when an interface IP address is changed.    ent-conf-change:Send a trap when an entity MIB change occurs (RFC4133).    l2mac:Send a trap for Learning event (add/delete/movefrom/moveto). | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_snmp_community_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_snmp_community_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_snmp_community_inner_dict = switch_controller_managed_switch_switch_id_get200_response_snmp_community_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInner from a dict
switch_controller_managed_switch_switch_id_get200_response_snmp_community_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_snmp_community_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


