# SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInnerVlansInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vlan_name** | **str** | List of FortiSwitch VLANs. | [optional] 
**proxy** | **str** | IGMP snooping proxy for the VLAN interface.    disable:Disable IGMP snooping proxy on VLAN interface.    enable:Enable IGMP snooping proxy on VLAN interface.    global:Use global setting for IGMP snooping proxy on VLAN interface. | [optional] 
**querier** | **str** | Enable/disable IGMP snooping querier for the VLAN interface.    disable:Disable IGMP snooping querier on VLAN interface.    enable:Enable IGMP snooping querier on VLAN interface. | [optional] 
**querier_addr** | **str** | IGMP snooping querier address. | [optional] 
**version** | **int** | IGMP snooping querying version. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_igmp_snooping_inner_vlans_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInnerVlansInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInnerVlansInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_igmp_snooping_inner_vlans_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInnerVlansInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInnerVlansInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_igmp_snooping_inner_vlans_inner_dict = switch_controller_managed_switch_switch_id_get200_response_igmp_snooping_inner_vlans_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInnerVlansInner from a dict
switch_controller_managed_switch_switch_id_get200_response_igmp_snooping_inner_vlans_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInnerVlansInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_igmp_snooping_inner_vlans_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


