# SystemDhcpServerIdGet200ResponseIpRangeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**start_ip** | **str** | Start of IP range. | [optional] 
**end_ip** | **str** | End of IP range. | [optional] 
**vci_match** | **str** | Enable/disable vendor class identifier (VCI) matching. When enabled only DHCP requests with a matching VCI are served with this range.    disable:Disable VCI matching.    enable:Enable VCI matching. | [optional] 
**vci_string** | [**List[SystemDhcpServerIdGet200ResponseIpRangeInnerVciStringInner]**](SystemDhcpServerIdGet200ResponseIpRangeInnerVciStringInner.md) | One or more VCI strings in quotes separated by spaces. | [optional] 
**uci_match** | **str** | Enable/disable user class identifier (UCI) matching. When enabled only DHCP requests with a matching UCI are served with this range.    disable:Disable UCI matching.    enable:Enable UCI matching. | [optional] 
**uci_string** | [**List[SystemDhcpServerIdGet200ResponseIpRangeInnerUciStringInner]**](SystemDhcpServerIdGet200ResponseIpRangeInnerUciStringInner.md) | One or more UCI strings in quotes separated by spaces. | [optional] 
**lease_time** | **int** | Lease time in seconds, 0 means default lease time. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dhcp_server_id_get200_response_ip_range_inner import SystemDhcpServerIdGet200ResponseIpRangeInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDhcpServerIdGet200ResponseIpRangeInner from a JSON string
system_dhcp_server_id_get200_response_ip_range_inner_instance = SystemDhcpServerIdGet200ResponseIpRangeInner.from_json(json)
# print the JSON string representation of the object
print(SystemDhcpServerIdGet200ResponseIpRangeInner.to_json())

# convert the object into a dict
system_dhcp_server_id_get200_response_ip_range_inner_dict = system_dhcp_server_id_get200_response_ip_range_inner_instance.to_dict()
# create an instance of SystemDhcpServerIdGet200ResponseIpRangeInner from a dict
system_dhcp_server_id_get200_response_ip_range_inner_from_dict = SystemDhcpServerIdGet200ResponseIpRangeInner.from_dict(system_dhcp_server_id_get200_response_ip_range_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


