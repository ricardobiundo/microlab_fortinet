# SystemFortidataGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable FortiData.    disable:Disable FortiData.    enable:Enable FortiData. | [optional] 
**source_ip** | **str** | Source IPv4 address used to communicate with FortiData. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_fortidata_get200_response import SystemFortidataGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFortidataGet200Response from a JSON string
system_fortidata_get200_response_instance = SystemFortidataGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemFortidataGet200Response.to_json())

# convert the object into a dict
system_fortidata_get200_response_dict = system_fortidata_get200_response_instance.to_dict()
# create an instance of SystemFortidataGet200Response from a dict
system_fortidata_get200_response_from_dict = SystemFortidataGet200Response.from_dict(system_fortidata_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


