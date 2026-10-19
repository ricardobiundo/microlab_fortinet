# SwitchControllerManagedSwitchSwitchIdGet200ResponseVlanInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vlan_name** | **str** | VLAN name. | [optional] 
**assignment_priority** | **int** | 802.1x Radius (Tunnel-Private-Group-Id) VLANID assign-by-name priority. A smaller value has a higher priority. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_vlan_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseVlanInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseVlanInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_vlan_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseVlanInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseVlanInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_vlan_inner_dict = switch_controller_managed_switch_switch_id_get200_response_vlan_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseVlanInner from a dict
switch_controller_managed_switch_switch_id_get200_response_vlan_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseVlanInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_vlan_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


