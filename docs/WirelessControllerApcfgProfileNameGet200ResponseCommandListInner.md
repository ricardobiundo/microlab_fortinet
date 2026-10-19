# WirelessControllerApcfgProfileNameGet200ResponseCommandListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Command ID. | [optional] 
**type** | **str** | The command type (default &#x3D; non-password).    non-password:Non-password command.    password:Password command. | [optional] 
**name** | **str** | AP local configuration command name. | [optional] 
**value** | **str** | AP local configuration command value. | [optional] 
**passwd_value** | **str** | AP local configuration command password value. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_apcfg_profile_name_get200_response_command_list_inner import WirelessControllerApcfgProfileNameGet200ResponseCommandListInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerApcfgProfileNameGet200ResponseCommandListInner from a JSON string
wireless_controller_apcfg_profile_name_get200_response_command_list_inner_instance = WirelessControllerApcfgProfileNameGet200ResponseCommandListInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerApcfgProfileNameGet200ResponseCommandListInner.to_json())

# convert the object into a dict
wireless_controller_apcfg_profile_name_get200_response_command_list_inner_dict = wireless_controller_apcfg_profile_name_get200_response_command_list_inner_instance.to_dict()
# create an instance of WirelessControllerApcfgProfileNameGet200ResponseCommandListInner from a dict
wireless_controller_apcfg_profile_name_get200_response_command_list_inner_from_dict = WirelessControllerApcfgProfileNameGet200ResponseCommandListInner.from_dict(wireless_controller_apcfg_profile_name_get200_response_command_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


