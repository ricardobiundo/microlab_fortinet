# SwitchControllerCustomCommandCommandNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**command_name** | **str** | Command name called by the FortiGate switch controller in the execute command. | [optional] 
**description** | **str** | Description. | [optional] 
**command** | **str** | String of commands to send to FortiSwitch devices (For example (%0a &#x3D; return key): config switch trunk %0a edit myTrunk %0a set members port1 port2 %0a end %0a). | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_custom_command_command_name_get200_response import SwitchControllerCustomCommandCommandNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerCustomCommandCommandNameGet200Response from a JSON string
switch_controller_custom_command_command_name_get200_response_instance = SwitchControllerCustomCommandCommandNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerCustomCommandCommandNameGet200Response.to_json())

# convert the object into a dict
switch_controller_custom_command_command_name_get200_response_dict = switch_controller_custom_command_command_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerCustomCommandCommandNameGet200Response from a dict
switch_controller_custom_command_command_name_get200_response_from_dict = SwitchControllerCustomCommandCommandNameGet200Response.from_dict(switch_controller_custom_command_command_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


