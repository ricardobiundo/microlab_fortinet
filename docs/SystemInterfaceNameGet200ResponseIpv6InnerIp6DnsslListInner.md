# SystemInterfaceNameGet200ResponseIpv6InnerIp6DnsslListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**domain** | **str** | Domain name. | [optional] 
**dnssl_life_time** | **int** | DNS search list time in seconds (0 - 4294967295, default &#x3D; 1800). | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_ipv6_inner_ip6_dnssl_list_inner import SystemInterfaceNameGet200ResponseIpv6InnerIp6DnsslListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerIp6DnsslListInner from a JSON string
system_interface_name_get200_response_ipv6_inner_ip6_dnssl_list_inner_instance = SystemInterfaceNameGet200ResponseIpv6InnerIp6DnsslListInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseIpv6InnerIp6DnsslListInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_ipv6_inner_ip6_dnssl_list_inner_dict = system_interface_name_get200_response_ipv6_inner_ip6_dnssl_list_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerIp6DnsslListInner from a dict
system_interface_name_get200_response_ipv6_inner_ip6_dnssl_list_inner_from_dict = SystemInterfaceNameGet200ResponseIpv6InnerIp6DnsslListInner.from_dict(system_interface_name_get200_response_ipv6_inner_ip6_dnssl_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


