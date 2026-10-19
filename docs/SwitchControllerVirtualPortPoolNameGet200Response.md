# SwitchControllerVirtualPortPoolNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Virtual switch pool name. | [optional] 
**description** | **str** | Virtual switch pool description. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_virtual_port_pool_name_get200_response import SwitchControllerVirtualPortPoolNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerVirtualPortPoolNameGet200Response from a JSON string
switch_controller_virtual_port_pool_name_get200_response_instance = SwitchControllerVirtualPortPoolNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerVirtualPortPoolNameGet200Response.to_json())

# convert the object into a dict
switch_controller_virtual_port_pool_name_get200_response_dict = switch_controller_virtual_port_pool_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerVirtualPortPoolNameGet200Response from a dict
switch_controller_virtual_port_pool_name_get200_response_from_dict = SwitchControllerVirtualPortPoolNameGet200Response.from_dict(switch_controller_virtual_port_pool_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


