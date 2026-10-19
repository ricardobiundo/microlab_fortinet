# SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemInterfaceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Interface name. | [optional] 
**switch_id** | **str** | Switch ID. | [optional] 
**mode** | **str** | Interface addressing mode.    static:static addressing mode.    dhcp:DHCP addressing mode. | [optional] 
**ip** | **str** | IP and mask for this interface. | [optional] 
**status** | **str** | Enable/disable interface status.    disable:Disable interface.    enable:Enable interface. | [optional] 
**allowaccess** | **str** | Permitted types of management access to this interface.    ping:PING.    https:HTTPS.    http:HTTP.    ssh:SSH.    snmp:SNMP.    telnet:TELNET.    radius-acct:RADIUS ACCOUNTING. | [optional] 
**vlan** | **str** | VLAN name. | [optional] 
**type** | **str** | Interface type.    vlan:VLAN interface.    physical:Physical interface. | [optional] 
**interface** | **str** | Interface name. | [optional] 
**vrf** | **str** | VRF for this route. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_system_interface_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemInterfaceInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemInterfaceInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_system_interface_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemInterfaceInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemInterfaceInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_system_interface_inner_dict = switch_controller_managed_switch_switch_id_get200_response_system_interface_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemInterfaceInner from a dict
switch_controller_managed_switch_switch_id_get200_response_system_interface_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemInterfaceInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_system_interface_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


