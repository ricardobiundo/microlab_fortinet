# SwitchControllerNetworkMonitorSettingsGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**network_monitoring** | **str** | Enable/disable passive gathering of information by FortiSwitch units concerning other network devices.    enable:Enable network monitoring on FortiSwitch.    disable:Disable network monitoring on FortiSwitch. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_network_monitor_settings_get200_response import SwitchControllerNetworkMonitorSettingsGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerNetworkMonitorSettingsGet200Response from a JSON string
switch_controller_network_monitor_settings_get200_response_instance = SwitchControllerNetworkMonitorSettingsGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerNetworkMonitorSettingsGet200Response.to_json())

# convert the object into a dict
switch_controller_network_monitor_settings_get200_response_dict = switch_controller_network_monitor_settings_get200_response_instance.to_dict()
# create an instance of SwitchControllerNetworkMonitorSettingsGet200Response from a dict
switch_controller_network_monitor_settings_get200_response_from_dict = SwitchControllerNetworkMonitorSettingsGet200Response.from_dict(switch_controller_network_monitor_settings_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


