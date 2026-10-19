# SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**port** | **str** | Ingress interface to which source guard is bound. | [optional] 
**description** | **str** | Description. | [optional] 
**binding_entry** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInnerBindingEntryInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInnerBindingEntryInner.md) | IP and MAC address configuration. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_ip_source_guard_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_ip_source_guard_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_ip_source_guard_inner_dict = switch_controller_managed_switch_switch_id_get200_response_ip_source_guard_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInner from a dict
switch_controller_managed_switch_switch_id_get200_response_ip_source_guard_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_ip_source_guard_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


