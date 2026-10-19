# SwitchControllerAutoConfigCustomNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Auto-Config FortiLink or ISL/ICL interface name. | [optional] 
**switch_binding** | [**List[SwitchControllerAutoConfigCustomNameGet200ResponseSwitchBindingInner]**](SwitchControllerAutoConfigCustomNameGet200ResponseSwitchBindingInner.md) | Switch binding list. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_auto_config_custom_name_get200_response import SwitchControllerAutoConfigCustomNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerAutoConfigCustomNameGet200Response from a JSON string
switch_controller_auto_config_custom_name_get200_response_instance = SwitchControllerAutoConfigCustomNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerAutoConfigCustomNameGet200Response.to_json())

# convert the object into a dict
switch_controller_auto_config_custom_name_get200_response_dict = switch_controller_auto_config_custom_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerAutoConfigCustomNameGet200Response from a dict
switch_controller_auto_config_custom_name_get200_response_from_dict = SwitchControllerAutoConfigCustomNameGet200Response.from_dict(switch_controller_auto_config_custom_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


