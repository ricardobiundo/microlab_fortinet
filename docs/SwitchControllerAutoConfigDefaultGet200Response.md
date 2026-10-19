# SwitchControllerAutoConfigDefaultGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**fgt_policy** | **str** | Default FortiLink auto-config policy. | [optional] 
**isl_policy** | **str** | Default ISL auto-config policy. | [optional] 
**icl_policy** | **str** | Default ICL auto-config policy. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_auto_config_default_get200_response import SwitchControllerAutoConfigDefaultGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerAutoConfigDefaultGet200Response from a JSON string
switch_controller_auto_config_default_get200_response_instance = SwitchControllerAutoConfigDefaultGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerAutoConfigDefaultGet200Response.to_json())

# convert the object into a dict
switch_controller_auto_config_default_get200_response_dict = switch_controller_auto_config_default_get200_response_instance.to_dict()
# create an instance of SwitchControllerAutoConfigDefaultGet200Response from a dict
switch_controller_auto_config_default_get200_response_from_dict = SwitchControllerAutoConfigDefaultGet200Response.from_dict(switch_controller_auto_config_default_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


