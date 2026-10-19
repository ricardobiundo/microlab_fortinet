# SystemInterfaceNameGet200ResponseIpv6InnerIp6RouteListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**route** | **str** | IPv6 route. | [optional] 
**route_pref** | **str** | Set route preference to the interface (default &#x3D; medium).    medium:Medium route preferences in RA packet.    high:High route preferences in RA packet.    low:Low route preferences in RA packet. | [optional] 
**route_life_time** | **int** | Route life time in seconds (0 - 65535, default &#x3D; 1800). | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_ipv6_inner_ip6_route_list_inner import SystemInterfaceNameGet200ResponseIpv6InnerIp6RouteListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerIp6RouteListInner from a JSON string
system_interface_name_get200_response_ipv6_inner_ip6_route_list_inner_instance = SystemInterfaceNameGet200ResponseIpv6InnerIp6RouteListInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseIpv6InnerIp6RouteListInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_ipv6_inner_ip6_route_list_inner_dict = system_interface_name_get200_response_ipv6_inner_ip6_route_list_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerIp6RouteListInner from a dict
system_interface_name_get200_response_ipv6_inner_ip6_route_list_inner_from_dict = SystemInterfaceNameGet200ResponseIpv6InnerIp6RouteListInner.from_dict(system_interface_name_get200_response_ipv6_inner_ip6_route_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


