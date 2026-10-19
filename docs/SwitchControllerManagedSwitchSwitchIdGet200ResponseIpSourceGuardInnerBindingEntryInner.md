# SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInnerBindingEntryInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**entry_name** | **str** | Configure binding pair. | [optional] 
**ip** | **str** | Source IP for this rule. | [optional] 
**mac** | **str** | MAC address for this rule. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_ip_source_guard_inner_binding_entry_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInnerBindingEntryInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInnerBindingEntryInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_ip_source_guard_inner_binding_entry_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInnerBindingEntryInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInnerBindingEntryInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_ip_source_guard_inner_binding_entry_inner_dict = switch_controller_managed_switch_switch_id_get200_response_ip_source_guard_inner_binding_entry_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInnerBindingEntryInner from a dict
switch_controller_managed_switch_switch_id_get200_response_ip_source_guard_inner_binding_entry_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInnerBindingEntryInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_ip_source_guard_inner_binding_entry_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


