# SystemVirtualSwitchNameGet200ResponsePortInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Physical interface name. | [optional] 
**alias** | **str** | Alias. | [optional] 

## Example

```python
from microlab_fortinet.models.system_virtual_switch_name_get200_response_port_inner import SystemVirtualSwitchNameGet200ResponsePortInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVirtualSwitchNameGet200ResponsePortInner from a JSON string
system_virtual_switch_name_get200_response_port_inner_instance = SystemVirtualSwitchNameGet200ResponsePortInner.from_json(json)
# print the JSON string representation of the object
print(SystemVirtualSwitchNameGet200ResponsePortInner.to_json())

# convert the object into a dict
system_virtual_switch_name_get200_response_port_inner_dict = system_virtual_switch_name_get200_response_port_inner_instance.to_dict()
# create an instance of SystemVirtualSwitchNameGet200ResponsePortInner from a dict
system_virtual_switch_name_get200_response_port_inner_from_dict = SystemVirtualSwitchNameGet200ResponsePortInner.from_dict(system_virtual_switch_name_get200_response_port_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


