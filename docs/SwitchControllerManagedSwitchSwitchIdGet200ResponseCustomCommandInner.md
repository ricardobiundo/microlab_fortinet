# SwitchControllerManagedSwitchSwitchIdGet200ResponseCustomCommandInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**command_entry** | **str** | List of FortiSwitch commands. | [optional] 
**command_name** | **str** | Names of commands to be pushed to this FortiSwitch device, as configured under config switch-controller custom-command. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_custom_command_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseCustomCommandInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseCustomCommandInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_custom_command_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseCustomCommandInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseCustomCommandInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_custom_command_inner_dict = switch_controller_managed_switch_switch_id_get200_response_custom_command_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseCustomCommandInner from a dict
switch_controller_managed_switch_switch_id_get200_response_custom_command_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseCustomCommandInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_custom_command_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


