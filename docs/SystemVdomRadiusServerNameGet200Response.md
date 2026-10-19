# SystemVdomRadiusServerNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the VDOM that you are adding the RADIUS server to. | [optional] 
**status** | **str** | Enable/disable the RSSO RADIUS server for this VDOM.    enable:Enable the RSSO RADIUS server for this VDOM.    disable:Disable the RSSO RADIUS server for this VDOM. | [optional] 
**radius_server_vdom** | **str** | Use this option to select another VDOM containing a VDOM RSSO RADIUS server to use for the current VDOM. | [optional] 

## Example

```python
from microlab_fortinet.models.system_vdom_radius_server_name_get200_response import SystemVdomRadiusServerNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVdomRadiusServerNameGet200Response from a JSON string
system_vdom_radius_server_name_get200_response_instance = SystemVdomRadiusServerNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemVdomRadiusServerNameGet200Response.to_json())

# convert the object into a dict
system_vdom_radius_server_name_get200_response_dict = system_vdom_radius_server_name_get200_response_instance.to_dict()
# create an instance of SystemVdomRadiusServerNameGet200Response from a dict
system_vdom_radius_server_name_get200_response_from_dict = SystemVdomRadiusServerNameGet200Response.from_dict(system_vdom_radius_server_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


