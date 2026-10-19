# SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpSysinfoInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable SNMP.    disable:Disable SNMP.    enable:Enable SNMP. | [optional] 
**engine_id** | **str** | Local SNMP engine ID string (max 24 char). | [optional] 
**description** | **str** | System description. | [optional] 
**contact_info** | **str** | Contact information. | [optional] 
**location** | **str** | System location. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_snmp_sysinfo_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpSysinfoInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpSysinfoInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_snmp_sysinfo_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpSysinfoInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpSysinfoInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_snmp_sysinfo_inner_dict = switch_controller_managed_switch_switch_id_get200_response_snmp_sysinfo_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpSysinfoInner from a dict
switch_controller_managed_switch_switch_id_get200_response_snmp_sysinfo_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpSysinfoInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_snmp_sysinfo_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


