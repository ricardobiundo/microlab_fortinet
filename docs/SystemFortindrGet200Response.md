# SystemFortindrGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable FortiNDR.    disable:Disable FortiNDR.    enable:Enable FortiNDR. | [optional] 
**source_ip** | **str** | Source IP address for communications to FortiNDR. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_fortindr_get200_response import SystemFortindrGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFortindrGet200Response from a JSON string
system_fortindr_get200_response_instance = SystemFortindrGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemFortindrGet200Response.to_json())

# convert the object into a dict
system_fortindr_get200_response_dict = system_fortindr_get200_response_instance.to_dict()
# create an instance of SystemFortindrGet200Response from a dict
system_fortindr_get200_response_from_dict = SystemFortindrGet200Response.from_dict(system_fortindr_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


