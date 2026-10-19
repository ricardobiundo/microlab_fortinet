# SwitchControllerManagedSwitchSwitchIdGet200ResponseStpSettingsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**local_override** | **str** | Enable to configure local STP settings that override global STP settings.    enable:Override global STP settings.    disable:Use global STP settings. | [optional] 
**name** | **str** | Name of local STP settings configuration. | [optional] 
**revision** | **int** | STP revision number (0 - 65535). | [optional] 
**hello_time** | **int** | Period of time between successive STP frame Bridge Protocol Data Units (BPDUs) sent on a port (1 - 10 sec, default &#x3D; 2). | [optional] 
**forward_time** | **int** | Period of time a port is in listening and learning state (4 - 30 sec, default &#x3D; 15). | [optional] 
**max_age** | **int** | Maximum time before a bridge port saves its configuration BPDU information (6 - 40 sec, default &#x3D; 20). | [optional] 
**max_hops** | **int** | Maximum number of hops between the root bridge and the furthest bridge (1- 40, default &#x3D; 20). | [optional] 
**pending_timer** | **int** | Pending time (1 - 15 sec, default &#x3D; 4). | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_stp_settings_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseStpSettingsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseStpSettingsInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_stp_settings_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseStpSettingsInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseStpSettingsInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_stp_settings_inner_dict = switch_controller_managed_switch_switch_id_get200_response_stp_settings_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseStpSettingsInner from a dict
switch_controller_managed_switch_switch_id_get200_response_stp_settings_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseStpSettingsInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_stp_settings_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


