# SystemInterfaceNameGet200ResponseIpv6InnerDhcp6IapdListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**iaid** | **int** | Identity association identifier. | [optional] 
**prefix_hint** | **str** | DHCPv6 prefix that will be used as a hint to the upstream DHCPv6 server. | [optional] 
**prefix_hint_plt** | **int** | DHCPv6 prefix hint preferred life time (sec), 0 means unlimited lease time. | [optional] 
**prefix_hint_vlt** | **int** | DHCPv6 prefix hint valid life time (sec). | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_ipv6_inner_dhcp6_iapd_list_inner import SystemInterfaceNameGet200ResponseIpv6InnerDhcp6IapdListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerDhcp6IapdListInner from a JSON string
system_interface_name_get200_response_ipv6_inner_dhcp6_iapd_list_inner_instance = SystemInterfaceNameGet200ResponseIpv6InnerDhcp6IapdListInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseIpv6InnerDhcp6IapdListInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_ipv6_inner_dhcp6_iapd_list_inner_dict = system_interface_name_get200_response_ipv6_inner_dhcp6_iapd_list_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerDhcp6IapdListInner from a dict
system_interface_name_get200_response_ipv6_inner_dhcp6_iapd_list_inner_from_dict = SystemInterfaceNameGet200ResponseIpv6InnerDhcp6IapdListInner.from_dict(system_interface_name_get200_response_ipv6_inner_dhcp6_iapd_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


