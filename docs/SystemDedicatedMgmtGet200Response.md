# SystemDedicatedMgmtGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable dedicated management.    enable:Enable setting.    disable:Disable setting. | [optional] 
**interface** | **str** | Dedicated management interface. | [optional] 
**default_gateway** | **str** | Default gateway for dedicated management interface. | [optional] 
**dhcp_server** | **str** | Enable/disable DHCP server on management interface.    enable:Enable DHCP server on management port.    disable:Disable DHCP server on management port. | [optional] 
**dhcp_netmask** | **str** | DHCP netmask. | [optional] 
**dhcp_start_ip** | **str** | DHCP start IP for dedicated management. | [optional] 
**dhcp_end_ip** | **str** | DHCP end IP for dedicated management. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dedicated_mgmt_get200_response import SystemDedicatedMgmtGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDedicatedMgmtGet200Response from a JSON string
system_dedicated_mgmt_get200_response_instance = SystemDedicatedMgmtGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemDedicatedMgmtGet200Response.to_json())

# convert the object into a dict
system_dedicated_mgmt_get200_response_dict = system_dedicated_mgmt_get200_response_instance.to_dict()
# create an instance of SystemDedicatedMgmtGet200Response from a dict
system_dedicated_mgmt_get200_response_from_dict = SystemDedicatedMgmtGet200Response.from_dict(system_dedicated_mgmt_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


