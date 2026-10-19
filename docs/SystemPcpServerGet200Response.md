# SystemPcpServerGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable PCP server.    enable:Enable PCP Server.    disable:Disable PCP Server. | [optional] 
**pools** | [**List[SystemPcpServerGet200ResponsePoolsInner]**](SystemPcpServerGet200ResponsePoolsInner.md) | Configure PCP pools. | [optional] 

## Example

```python
from microlab_fortinet.models.system_pcp_server_get200_response import SystemPcpServerGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPcpServerGet200Response from a JSON string
system_pcp_server_get200_response_instance = SystemPcpServerGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemPcpServerGet200Response.to_json())

# convert the object into a dict
system_pcp_server_get200_response_dict = system_pcp_server_get200_response_instance.to_dict()
# create an instance of SystemPcpServerGet200Response from a dict
system_pcp_server_get200_response_from_dict = SystemPcpServerGet200Response.from_dict(system_pcp_server_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


