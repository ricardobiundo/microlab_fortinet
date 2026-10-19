# SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInnerOptionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**code** | **int** | DHCP option code. | [optional] 
**type** | **str** | DHCP option type.    hex:DHCP option in hex.    string:DHCP option in string.    ip:DHCP option in IP.    fqdn:DHCP option in domain search option format. | [optional] 
**value** | **str** | DHCP option value. | [optional] 
**ip** | **str** | DHCP option IPs. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_system_dhcp_server_inner_options_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInnerOptionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInnerOptionsInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_system_dhcp_server_inner_options_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInnerOptionsInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInnerOptionsInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_system_dhcp_server_inner_options_inner_dict = switch_controller_managed_switch_switch_id_get200_response_system_dhcp_server_inner_options_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInnerOptionsInner from a dict
switch_controller_managed_switch_switch_id_get200_response_system_dhcp_server_inner_options_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInnerOptionsInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_system_dhcp_server_inner_options_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


