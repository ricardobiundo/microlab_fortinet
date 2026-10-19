# SwitchControllerManagedSwitchSwitchIdGet200ResponseStaticMacInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**type** | **str** | Type.    static:Static MAC.    sticky:Sticky MAC. | [optional] 
**vlan** | **str** | Vlan. | [optional] 
**mac** | **str** | MAC address. | [optional] 
**interface** | **str** | Interface name. | [optional] 
**description** | **str** | Description. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_static_mac_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseStaticMacInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseStaticMacInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_static_mac_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseStaticMacInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseStaticMacInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_static_mac_inner_dict = switch_controller_managed_switch_switch_id_get200_response_static_mac_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseStaticMacInner from a dict
switch_controller_managed_switch_switch_id_get200_response_static_mac_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseStaticMacInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_static_mac_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


