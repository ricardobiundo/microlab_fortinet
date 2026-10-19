# SwitchControllerManagedSwitchSwitchIdGet200ResponseDhcpSnoopingStaticClientInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Client name. | [optional] 
**vlan** | **str** | VLAN name. | [optional] 
**ip** | **str** | Client static IP address. | [optional] 
**mac** | **str** | Client MAC address. | [optional] 
**port** | **str** | Interface name. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_dhcp_snooping_static_client_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseDhcpSnoopingStaticClientInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseDhcpSnoopingStaticClientInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_dhcp_snooping_static_client_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseDhcpSnoopingStaticClientInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseDhcpSnoopingStaticClientInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_dhcp_snooping_static_client_inner_dict = switch_controller_managed_switch_switch_id_get200_response_dhcp_snooping_static_client_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseDhcpSnoopingStaticClientInner from a dict
switch_controller_managed_switch_switch_id_get200_response_dhcp_snooping_static_client_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseDhcpSnoopingStaticClientInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_dhcp_snooping_static_client_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


