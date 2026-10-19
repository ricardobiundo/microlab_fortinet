# SystemDhcp6ServerIdGet200ResponseIpRangeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**start_ip** | **str** | Start of IP range. | [optional] 
**end_ip** | **str** | End of IP range. | [optional] 
**vci_match** | **str** | Enable/disable vendor class option matching. When enabled only DHCP requests with a matching VC are served with this range.    disable:Disable VCI matching.    enable:Enable VCI matching. | [optional] 
**vci_string** | [**List[SystemDhcpServerIdGet200ResponseIpRangeInnerVciStringInner]**](SystemDhcpServerIdGet200ResponseIpRangeInnerVciStringInner.md) | One or more VCI strings in quotes separated by spaces. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dhcp6_server_id_get200_response_ip_range_inner import SystemDhcp6ServerIdGet200ResponseIpRangeInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDhcp6ServerIdGet200ResponseIpRangeInner from a JSON string
system_dhcp6_server_id_get200_response_ip_range_inner_instance = SystemDhcp6ServerIdGet200ResponseIpRangeInner.from_json(json)
# print the JSON string representation of the object
print(SystemDhcp6ServerIdGet200ResponseIpRangeInner.to_json())

# convert the object into a dict
system_dhcp6_server_id_get200_response_ip_range_inner_dict = system_dhcp6_server_id_get200_response_ip_range_inner_instance.to_dict()
# create an instance of SystemDhcp6ServerIdGet200ResponseIpRangeInner from a dict
system_dhcp6_server_id_get200_response_ip_range_inner_from_dict = SystemDhcp6ServerIdGet200ResponseIpRangeInner.from_dict(system_dhcp6_server_id_get200_response_ip_range_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


