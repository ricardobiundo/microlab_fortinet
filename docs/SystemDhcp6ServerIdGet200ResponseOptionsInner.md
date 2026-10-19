# SystemDhcp6ServerIdGet200ResponseOptionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**code** | **int** | DHCPv6 option code. | [optional] 
**type** | **str** | DHCPv6 option type.    hex:DHCPv6 option in hex.    string:DHCPv6 option in string.    ip6:DHCPv6 option in IP6.    fqdn:DHCPv6 option in domain search option format. | [optional] 
**value** | **str** | DHCPv6 option value (hexadecimal value must be even). | [optional] 
**ip6** | **str** | DHCP option IP6s. | [optional] 
**vci_match** | **str** | Enable/disable vendor class option matching. When enabled only DHCP requests with a matching VCI are served with this option.    disable:Disable VCI matching.    enable:Enable VCI matching. | [optional] 
**vci_string** | [**List[SystemDhcpServerIdGet200ResponseIpRangeInnerVciStringInner]**](SystemDhcpServerIdGet200ResponseIpRangeInnerVciStringInner.md) | One or more VCI strings in quotes separated by spaces. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dhcp6_server_id_get200_response_options_inner import SystemDhcp6ServerIdGet200ResponseOptionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDhcp6ServerIdGet200ResponseOptionsInner from a JSON string
system_dhcp6_server_id_get200_response_options_inner_instance = SystemDhcp6ServerIdGet200ResponseOptionsInner.from_json(json)
# print the JSON string representation of the object
print(SystemDhcp6ServerIdGet200ResponseOptionsInner.to_json())

# convert the object into a dict
system_dhcp6_server_id_get200_response_options_inner_dict = system_dhcp6_server_id_get200_response_options_inner_instance.to_dict()
# create an instance of SystemDhcp6ServerIdGet200ResponseOptionsInner from a dict
system_dhcp6_server_id_get200_response_options_inner_from_dict = SystemDhcp6ServerIdGet200ResponseOptionsInner.from_dict(system_dhcp6_server_id_get200_response_options_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


