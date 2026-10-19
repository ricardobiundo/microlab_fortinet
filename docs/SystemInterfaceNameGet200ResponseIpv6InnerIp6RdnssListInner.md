# SystemInterfaceNameGet200ResponseIpv6InnerIp6RdnssListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rdnss** | **str** | Recursive DNS server option. | [optional] 
**rdnss_life_time** | **int** | Recursive DNS server life time in seconds (0 - 4294967295, default &#x3D; 1800). | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_ipv6_inner_ip6_rdnss_list_inner import SystemInterfaceNameGet200ResponseIpv6InnerIp6RdnssListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerIp6RdnssListInner from a JSON string
system_interface_name_get200_response_ipv6_inner_ip6_rdnss_list_inner_instance = SystemInterfaceNameGet200ResponseIpv6InnerIp6RdnssListInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseIpv6InnerIp6RdnssListInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_ipv6_inner_ip6_rdnss_list_inner_dict = system_interface_name_get200_response_ipv6_inner_ip6_rdnss_list_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerIp6RdnssListInner from a dict
system_interface_name_get200_response_ipv6_inner_ip6_rdnss_list_inner_from_dict = SystemInterfaceNameGet200ResponseIpv6InnerIp6RdnssListInner.from_dict(system_interface_name_get200_response_ipv6_inner_ip6_rdnss_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


