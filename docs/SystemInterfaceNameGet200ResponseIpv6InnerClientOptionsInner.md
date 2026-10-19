# SystemInterfaceNameGet200ResponseIpv6InnerClientOptionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**code** | **int** | DHCPv6 option code. | [optional] 
**type** | **str** | DHCPv6 option type.    hex:DHCPv6 option in hex.    string:DHCPv6 option in string.    ip6:DHCPv6 option in IP6.    fqdn:DHCPv6 option in domain search option format. | [optional] 
**value** | **str** | DHCPv6 option value (hexadecimal value must be even). | [optional] 
**ip6** | **str** | DHCP option IP6s. | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_ipv6_inner_client_options_inner import SystemInterfaceNameGet200ResponseIpv6InnerClientOptionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerClientOptionsInner from a JSON string
system_interface_name_get200_response_ipv6_inner_client_options_inner_instance = SystemInterfaceNameGet200ResponseIpv6InnerClientOptionsInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseIpv6InnerClientOptionsInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_ipv6_inner_client_options_inner_dict = system_interface_name_get200_response_ipv6_inner_client_options_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerClientOptionsInner from a dict
system_interface_name_get200_response_ipv6_inner_client_options_inner_from_dict = SystemInterfaceNameGet200ResponseIpv6InnerClientOptionsInner.from_dict(system_interface_name_get200_response_ipv6_inner_client_options_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


