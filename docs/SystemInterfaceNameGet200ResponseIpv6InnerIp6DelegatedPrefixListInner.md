# SystemInterfaceNameGet200ResponseIpv6InnerIp6DelegatedPrefixListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prefix_id** | **int** | Prefix ID. | [optional] 
**upstream_interface** | **str** | Name of the interface that provides delegated information. | [optional] 
**delegated_prefix_iaid** | **int** | IAID of obtained delegated-prefix from the upstream interface. | [optional] 
**autonomous_flag** | **str** | Enable/disable the autonomous flag.    enable:Enable the autonomous flag.    disable:Disable the autonomous flag. | [optional] 
**onlink_flag** | **str** | Enable/disable the onlink flag.    enable:Enable the onlink flag.    disable:Disable the onlink flag. | [optional] 
**subnet** | **str** | Add subnet ID to routing prefix. | [optional] 
**rdnss_service** | **str** | Recursive DNS service option.    delegated:Delegated RDNSS settings.    default:System RDNSS settings.    specify:Specify recursive DNS servers. | [optional] 
**rdnss** | **str** | Recursive DNS server option. | [optional] 
**dnssl_service** | **str** | Enable/disable use of domain from delegated prefix for DNSSL.    enable:Enable use of domain from delegated prefix for DNSSL.    disable:Disable use of domain from delegated prefix for DNSSL. | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_ipv6_inner_ip6_delegated_prefix_list_inner import SystemInterfaceNameGet200ResponseIpv6InnerIp6DelegatedPrefixListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerIp6DelegatedPrefixListInner from a JSON string
system_interface_name_get200_response_ipv6_inner_ip6_delegated_prefix_list_inner_instance = SystemInterfaceNameGet200ResponseIpv6InnerIp6DelegatedPrefixListInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseIpv6InnerIp6DelegatedPrefixListInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_ipv6_inner_ip6_delegated_prefix_list_inner_dict = system_interface_name_get200_response_ipv6_inner_ip6_delegated_prefix_list_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerIp6DelegatedPrefixListInner from a dict
system_interface_name_get200_response_ipv6_inner_ip6_delegated_prefix_list_inner_from_dict = SystemInterfaceNameGet200ResponseIpv6InnerIp6DelegatedPrefixListInner.from_dict(system_interface_name_get200_response_ipv6_inner_ip6_delegated_prefix_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


