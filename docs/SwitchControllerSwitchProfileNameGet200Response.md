# SwitchControllerSwitchProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | FortiSwitch Profile name. | [optional] 
**login_passwd_override** | **str** | Enable/disable overriding the admin administrator password for a managed FortiSwitch with the FortiGate admin administrator account password.    enable:Override a managed FortiSwitch&#39;s admin administrator password.    disable:Use the managed FortiSwitch admin administrator account password. | [optional] 
**login_passwd** | **str** | Login password of managed FortiSwitch. | [optional] 
**login** | **str** | Enable/disable FortiSwitch serial console.    enable:Enable FortiSwitch serial console.    disable:Disable FortiSwitch serial console. | [optional] 
**revision_backup_on_logout** | **str** | Enable/disable automatic revision backup upon logout from FortiSwitch.    enable:Enable automatic revision backup upon logout from FortiSwitch.    disable:Disable automatic revision backup upon logout from FortiSwitch. | [optional] 
**revision_backup_on_upgrade** | **str** | Enable/disable automatic revision backup upon FortiSwitch image upgrade.    enable:Enable automatic revision backup upon FortiSwitch image upgrade.    disable:Disable automatic revision backup upon FortiSwitch image upgrade. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_switch_profile_name_get200_response import SwitchControllerSwitchProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerSwitchProfileNameGet200Response from a JSON string
switch_controller_switch_profile_name_get200_response_instance = SwitchControllerSwitchProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerSwitchProfileNameGet200Response.to_json())

# convert the object into a dict
switch_controller_switch_profile_name_get200_response_dict = switch_controller_switch_profile_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerSwitchProfileNameGet200Response from a dict
switch_controller_switch_profile_name_get200_response_from_dict = SwitchControllerSwitchProfileNameGet200Response.from_dict(switch_controller_switch_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


