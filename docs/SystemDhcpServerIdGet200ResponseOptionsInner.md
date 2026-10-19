# SystemDhcpServerIdGet200ResponseOptionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**code** | **int** | DHCP option code. | [optional] 
**type** | **str** | DHCP option type.    hex:DHCP option in hex.    string:DHCP option in string.    ip:DHCP option in IP.    fqdn:DHCP option in domain search option format. | [optional] 
**value** | **str** | DHCP option value. | [optional] 
**ip** | **str** | DHCP option IPs. | [optional] 
**vci_match** | **str** | Enable/disable vendor class identifier (VCI) matching. When enabled only DHCP requests with a matching VCI are served with this option.    disable:Disable VCI matching.    enable:Enable VCI matching. | [optional] 
**vci_string** | [**List[SystemDhcpServerIdGet200ResponseIpRangeInnerVciStringInner]**](SystemDhcpServerIdGet200ResponseIpRangeInnerVciStringInner.md) | One or more VCI strings in quotes separated by spaces. | [optional] 
**uci_match** | **str** | Enable/disable user class identifier (UCI) matching. When enabled only DHCP requests with a matching UCI are served with this option.    disable:Disable UCI matching.    enable:Enable UCI matching. | [optional] 
**uci_string** | [**List[SystemDhcpServerIdGet200ResponseIpRangeInnerUciStringInner]**](SystemDhcpServerIdGet200ResponseIpRangeInnerUciStringInner.md) | One or more UCI strings in quotes separated by spaces. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dhcp_server_id_get200_response_options_inner import SystemDhcpServerIdGet200ResponseOptionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDhcpServerIdGet200ResponseOptionsInner from a JSON string
system_dhcp_server_id_get200_response_options_inner_instance = SystemDhcpServerIdGet200ResponseOptionsInner.from_json(json)
# print the JSON string representation of the object
print(SystemDhcpServerIdGet200ResponseOptionsInner.to_json())

# convert the object into a dict
system_dhcp_server_id_get200_response_options_inner_dict = system_dhcp_server_id_get200_response_options_inner_instance.to_dict()
# create an instance of SystemDhcpServerIdGet200ResponseOptionsInner from a dict
system_dhcp_server_id_get200_response_options_inner_from_dict = SystemDhcpServerIdGet200ResponseOptionsInner.from_dict(system_dhcp_server_id_get200_response_options_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


