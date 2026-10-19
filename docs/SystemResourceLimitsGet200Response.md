# SystemResourceLimitsGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**session** | **int** | Maximum number of sessions. | [optional] 
**ipsec_phase1** | **int** | Maximum number of VPN IPsec phase1 tunnels. | [optional] 
**ipsec_phase2** | **int** | Maximum number of VPN IPsec phase2 tunnels. | [optional] 
**ipsec_phase1_interface** | **int** | Maximum number of VPN IPsec phase1 interface tunnels. | [optional] 
**ipsec_phase2_interface** | **int** | Maximum number of VPN IPsec phase2 interface tunnels. | [optional] 
**dialup_tunnel** | **int** | Maximum number of dial-up tunnels. | [optional] 
**firewall_policy** | **int** | Maximum number of firewall policies (policy, DoS-policy4, DoS-policy6, multicast). | [optional] 
**firewall_address** | **int** | Maximum number of firewall addresses (IPv4, IPv6, multicast). | [optional] 
**firewall_addrgrp** | **int** | Maximum number of firewall address groups (IPv4, IPv6). | [optional] 
**custom_service** | **int** | Maximum number of firewall custom services. | [optional] 
**service_group** | **int** | Maximum number of firewall service groups. | [optional] 
**onetime_schedule** | **int** | Maximum number of firewall one-time schedules. | [optional] 
**recurring_schedule** | **int** | Maximum number of firewall recurring schedules. | [optional] 
**user** | **int** | Maximum number of local users. | [optional] 
**user_group** | **int** | Maximum number of user groups. | [optional] 
**sslvpn** | **int** | Maximum number of Agentless VPN. | [optional] 
**proxy** | **int** | Maximum number of concurrent proxy users. | [optional] 
**log_disk_quota** | **int** | Log disk quota in megabytes (MB). | [optional] 

## Example

```python
from microlab_fortinet.models.system_resource_limits_get200_response import SystemResourceLimitsGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemResourceLimitsGet200Response from a JSON string
system_resource_limits_get200_response_instance = SystemResourceLimitsGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemResourceLimitsGet200Response.to_json())

# convert the object into a dict
system_resource_limits_get200_response_dict = system_resource_limits_get200_response_instance.to_dict()
# create an instance of SystemResourceLimitsGet200Response from a dict
system_resource_limits_get200_response_from_dict = SystemResourceLimitsGet200Response.from_dict(system_resource_limits_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


