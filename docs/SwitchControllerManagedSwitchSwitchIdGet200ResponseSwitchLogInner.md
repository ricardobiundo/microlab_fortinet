# SwitchControllerManagedSwitchSwitchIdGet200ResponseSwitchLogInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**local_override** | **str** | Enable to configure local logging settings that override global logging settings.    enable:Override global logging settings.    disable:Use global logging settings. | [optional] 
**status** | **str** | Enable/disable adding FortiSwitch logs to the FortiGate event log.    enable:Add FortiSwitch logs to the FortiGate event log.    disable:Do not add FortiSwitch logs to the FortiGate event log. | [optional] 
**severity** | **str** | Severity of FortiSwitch logs that are added to the FortiGate event log.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_switch_log_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseSwitchLogInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSwitchLogInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_switch_log_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseSwitchLogInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseSwitchLogInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_switch_log_inner_dict = switch_controller_managed_switch_switch_id_get200_response_switch_log_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSwitchLogInner from a dict
switch_controller_managed_switch_switch_id_get200_response_switch_log_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseSwitchLogInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_switch_log_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


