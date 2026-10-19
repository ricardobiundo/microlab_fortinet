# SystemInterfaceNameGet200ResponseIpv6InnerIp6PrefixListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prefix** | **str** | IPv6 prefix. | [optional] 
**autonomous_flag** | **str** | Enable/disable the autonomous flag.    enable:Enable the autonomous flag.    disable:Disable the autonomous flag. | [optional] 
**onlink_flag** | **str** | Enable/disable the onlink flag.    enable:Enable the onlink flag.    disable:Disable the onlink flag. | [optional] 
**valid_life_time** | **int** | Valid life time (sec). | [optional] 
**preferred_life_time** | **int** | Preferred life time (sec). | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_ipv6_inner_ip6_prefix_list_inner import SystemInterfaceNameGet200ResponseIpv6InnerIp6PrefixListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerIp6PrefixListInner from a JSON string
system_interface_name_get200_response_ipv6_inner_ip6_prefix_list_inner_instance = SystemInterfaceNameGet200ResponseIpv6InnerIp6PrefixListInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseIpv6InnerIp6PrefixListInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_ipv6_inner_ip6_prefix_list_inner_dict = system_interface_name_get200_response_ipv6_inner_ip6_prefix_list_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerIp6PrefixListInner from a dict
system_interface_name_get200_response_ipv6_inner_ip6_prefix_list_inner_from_dict = SystemInterfaceNameGet200ResponseIpv6InnerIp6PrefixListInner.from_dict(system_interface_name_get200_response_ipv6_inner_ip6_prefix_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


