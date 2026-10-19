# SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**local_override** | **str** | Enable/disable overriding the global IGMP snooping configuration.    enable:Override the global IGMP snooping configuration.    disable:Use the global IGMP snooping configuration. | [optional] 
**aging_time** | **int** | Maximum time to retain a multicast snooping entry for which no packets have been seen (15 - 3600 sec, default &#x3D; 300). | [optional] 
**flood_unknown_multicast** | **str** | Enable/disable unknown multicast flooding.    enable:Enable unknown multicast flooding.    disable:Disable unknown multicast flooding. | [optional] 
**vlans** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInnerVlansInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInnerVlansInner.md) | Configure IGMP snooping VLAN. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_igmp_snooping_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_igmp_snooping_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_igmp_snooping_inner_dict = switch_controller_managed_switch_switch_id_get200_response_igmp_snooping_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInner from a dict
switch_controller_managed_switch_switch_id_get200_response_igmp_snooping_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_igmp_snooping_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


