# SwitchControllerSwitchLogGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable adding FortiSwitch logs to FortiGate event log.    enable:Add FortiSwitch logs to FortiGate event log.    disable:Do not add  FortiSwitch logs to FortiGate event log. | [optional] 
**severity** | **str** | Severity of FortiSwitch logs that are added to the FortiGate event log.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_switch_log_get200_response import SwitchControllerSwitchLogGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerSwitchLogGet200Response from a JSON string
switch_controller_switch_log_get200_response_instance = SwitchControllerSwitchLogGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerSwitchLogGet200Response.to_json())

# convert the object into a dict
switch_controller_switch_log_get200_response_dict = switch_controller_switch_log_get200_response_instance.to_dict()
# create an instance of SwitchControllerSwitchLogGet200Response from a dict
switch_controller_switch_log_get200_response_from_dict = SwitchControllerSwitchLogGet200Response.from_dict(switch_controller_switch_log_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


