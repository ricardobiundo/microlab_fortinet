# SwitchControllerGlobalGet200ResponseCustomCommandInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**command_entry** | **str** | List of FortiSwitch commands. | [optional] 
**command_name** | **str** | Name of custom command to push to all FortiSwitches in VDOM. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_global_get200_response_custom_command_inner import SwitchControllerGlobalGet200ResponseCustomCommandInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerGlobalGet200ResponseCustomCommandInner from a JSON string
switch_controller_global_get200_response_custom_command_inner_instance = SwitchControllerGlobalGet200ResponseCustomCommandInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerGlobalGet200ResponseCustomCommandInner.to_json())

# convert the object into a dict
switch_controller_global_get200_response_custom_command_inner_dict = switch_controller_global_get200_response_custom_command_inner_instance.to_dict()
# create an instance of SwitchControllerGlobalGet200ResponseCustomCommandInner from a dict
switch_controller_global_get200_response_custom_command_inner_from_dict = SwitchControllerGlobalGet200ResponseCustomCommandInner.from_dict(switch_controller_global_get200_response_custom_command_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


