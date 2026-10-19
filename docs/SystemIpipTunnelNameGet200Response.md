# SystemIpipTunnelNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | IPIP Tunnel name. | [optional] 
**interface** | **str** | Interface name that is associated with the incoming traffic from available options. | [optional] 
**remote_gw** | **str** | IPv4 address for the remote gateway. | [optional] 
**local_gw** | **str** | IPv4 address for the local gateway. | [optional] 
**use_sdwan** | **str** | Enable/disable use of SD-WAN to reach remote gateway.    disable:Disable use of SD-WAN to reach remote gateway.    enable:Enable use of SD-WAN to reach remote gateway. | [optional] 
**auto_asic_offload** | **str** | Enable/disable tunnel ASIC offloading.    enable:Enable auto ASIC offloading.    disable:Disable ASIC offloading. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ipip_tunnel_name_get200_response import SystemIpipTunnelNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIpipTunnelNameGet200Response from a JSON string
system_ipip_tunnel_name_get200_response_instance = SystemIpipTunnelNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemIpipTunnelNameGet200Response.to_json())

# convert the object into a dict
system_ipip_tunnel_name_get200_response_dict = system_ipip_tunnel_name_get200_response_instance.to_dict()
# create an instance of SystemIpipTunnelNameGet200Response from a dict
system_ipip_tunnel_name_get200_response_from_dict = SystemIpipTunnelNameGet200Response.from_dict(system_ipip_tunnel_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


