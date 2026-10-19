# SystemVirtualSwitchNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the virtual switch. | [optional] 
**physical_switch** | **str** | Physical switch parent. | [optional] 
**vlan** | **int** | VLAN. | [optional] 
**port** | [**List[SystemVirtualSwitchNameGet200ResponsePortInner]**](SystemVirtualSwitchNameGet200ResponsePortInner.md) | Configure member ports. | [optional] 
**span** | **str** | Enable/disable SPAN.    disable:Disable SPAN.    enable:Enable SPAN. | [optional] 
**span_source_port** | **str** | SPAN source port. | [optional] 
**span_dest_port** | **str** | SPAN destination port. | [optional] 
**span_direction** | **str** | SPAN direction.    rx:SPAN receive direction only.    tx:SPAN transmit direction only.    both:SPAN both directions. | [optional] 

## Example

```python
from microlab_fortinet.models.system_virtual_switch_name_get200_response import SystemVirtualSwitchNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVirtualSwitchNameGet200Response from a JSON string
system_virtual_switch_name_get200_response_instance = SystemVirtualSwitchNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemVirtualSwitchNameGet200Response.to_json())

# convert the object into a dict
system_virtual_switch_name_get200_response_dict = system_virtual_switch_name_get200_response_instance.to_dict()
# create an instance of SystemVirtualSwitchNameGet200Response from a dict
system_virtual_switch_name_get200_response_from_dict = SystemVirtualSwitchNameGet200Response.from_dict(system_virtual_switch_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


