# SystemIpv6TunnelNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | IPv6 tunnel name. | [optional] 
**source** | **str** | Local IPv6 address of the tunnel. | [optional] 
**destination** | **str** | Remote IPv6 address of the tunnel. | [optional] 
**interface** | **str** | Interface name. | [optional] 
**use_sdwan** | **str** | Enable/disable use of SD-WAN to reach remote gateway.    disable:Disable use of SD-WAN to reach remote gateway.    enable:Enable use of SD-WAN to reach remote gateway. | [optional] 
**auto_asic_offload** | **str** | Enable/disable tunnel ASIC offloading.    enable:Enable auto ASIC offloading.    disable:Disable ASIC offloading. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ipv6_tunnel_name_get200_response import SystemIpv6TunnelNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIpv6TunnelNameGet200Response from a JSON string
system_ipv6_tunnel_name_get200_response_instance = SystemIpv6TunnelNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemIpv6TunnelNameGet200Response.to_json())

# convert the object into a dict
system_ipv6_tunnel_name_get200_response_dict = system_ipv6_tunnel_name_get200_response_instance.to_dict()
# create an instance of SystemIpv6TunnelNameGet200Response from a dict
system_ipv6_tunnel_name_get200_response_from_dict = SystemIpv6TunnelNameGet200Response.from_dict(system_ipv6_tunnel_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


