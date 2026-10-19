# SwitchControllerAutoConfigCustomNameGet200ResponseSwitchBindingInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**switch_id** | **str** | Switch name. | [optional] 
**policy** | **str** | Custom auto-config policy. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_auto_config_custom_name_get200_response_switch_binding_inner import SwitchControllerAutoConfigCustomNameGet200ResponseSwitchBindingInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerAutoConfigCustomNameGet200ResponseSwitchBindingInner from a JSON string
switch_controller_auto_config_custom_name_get200_response_switch_binding_inner_instance = SwitchControllerAutoConfigCustomNameGet200ResponseSwitchBindingInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerAutoConfigCustomNameGet200ResponseSwitchBindingInner.to_json())

# convert the object into a dict
switch_controller_auto_config_custom_name_get200_response_switch_binding_inner_dict = switch_controller_auto_config_custom_name_get200_response_switch_binding_inner_instance.to_dict()
# create an instance of SwitchControllerAutoConfigCustomNameGet200ResponseSwitchBindingInner from a dict
switch_controller_auto_config_custom_name_get200_response_switch_binding_inner_from_dict = SwitchControllerAutoConfigCustomNameGet200ResponseSwitchBindingInner.from_dict(switch_controller_auto_config_custom_name_get200_response_switch_binding_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


