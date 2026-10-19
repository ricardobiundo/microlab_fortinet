# SystemVdomPropertyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | VDOM name. | [optional] 
**description** | **str** | Description. | [optional] 
**snmp_index** | **int** | Permanent SNMP Index of the virtual domain (1 - 2147483647). | [optional] 
**session** | **str** | Maximum guaranteed number of sessions. | [optional] 
**ipsec_phase1** | **str** | Maximum guaranteed number of VPN IPsec phase 1 tunnels. | [optional] 
**ipsec_phase2** | **str** | Maximum guaranteed number of VPN IPsec phase 2 tunnels. | [optional] 
**ipsec_phase1_interface** | **str** | Maximum guaranteed number of VPN IPsec phase1 interface tunnels. | [optional] 
**ipsec_phase2_interface** | **str** | Maximum guaranteed number of VPN IPsec phase2 interface tunnels. | [optional] 
**dialup_tunnel** | **str** | Maximum guaranteed number of dial-up tunnels. | [optional] 
**firewall_policy** | **str** | Maximum guaranteed number of firewall policies (policy, DoS-policy4, DoS-policy6, multicast). | [optional] 
**firewall_address** | **str** | Maximum guaranteed number of firewall addresses (IPv4, IPv6, multicast). | [optional] 
**firewall_addrgrp** | **str** | Maximum guaranteed number of firewall address groups (IPv4, IPv6). | [optional] 
**custom_service** | **str** | Maximum guaranteed number of firewall custom services. | [optional] 
**service_group** | **str** | Maximum guaranteed number of firewall service groups. | [optional] 
**onetime_schedule** | **str** | Maximum guaranteed number of firewall one-time schedules.. | [optional] 
**recurring_schedule** | **str** | Maximum guaranteed number of firewall recurring schedules. | [optional] 
**user** | **str** | Maximum guaranteed number of local users. | [optional] 
**user_group** | **str** | Maximum guaranteed number of user groups. | [optional] 
**sslvpn** | **str** | Maximum guaranteed number of Agentless VPNs. | [optional] 
**proxy** | **str** | Maximum guaranteed number of concurrent proxy users. | [optional] 
**log_disk_quota** | **str** | Log disk quota in megabytes (MB). Range depends on how much disk space is available. | [optional] 

## Example

```python
from microlab_fortinet.models.system_vdom_property_name_get200_response import SystemVdomPropertyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVdomPropertyNameGet200Response from a JSON string
system_vdom_property_name_get200_response_instance = SystemVdomPropertyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemVdomPropertyNameGet200Response.to_json())

# convert the object into a dict
system_vdom_property_name_get200_response_dict = system_vdom_property_name_get200_response_instance.to_dict()
# create an instance of SystemVdomPropertyNameGet200Response from a dict
system_vdom_property_name_get200_response_from_dict = SystemVdomPropertyNameGet200Response.from_dict(system_vdom_property_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


