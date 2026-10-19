# SystemNetworkVisibilityGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_visibility** | **str** | Enable/disable logging of destination visibility.    disable:Disable logging of destination visibility.    enable:Enable logging of destination visibility. | [optional] 
**source_location** | **str** | Enable/disable logging of source geographical location visibility.    disable:Disable logging of source geographical location visibility.    enable:Enable logging of source geographical location visibility. | [optional] 
**destination_hostname_visibility** | **str** | Enable/disable logging of destination hostname visibility.    disable:Disable logging of destination hostname visibility.    enable:Enable logging of destination hostname visibility. | [optional] 
**destination_location** | **str** | Enable/disable logging of destination geographical location visibility.    disable:Disable logging of destination geographical location visibility.    enable:Enable logging of destination geographical location visibility. | [optional] 

## Example

```python
from microlab_fortinet.models.system_network_visibility_get200_response import SystemNetworkVisibilityGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetworkVisibilityGet200Response from a JSON string
system_network_visibility_get200_response_instance = SystemNetworkVisibilityGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemNetworkVisibilityGet200Response.to_json())

# convert the object into a dict
system_network_visibility_get200_response_dict = system_network_visibility_get200_response_instance.to_dict()
# create an instance of SystemNetworkVisibilityGet200Response from a dict
system_network_visibility_get200_response_from_dict = SystemNetworkVisibilityGet200Response.from_dict(system_network_visibility_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


