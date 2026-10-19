# SystemSitTunnelNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Tunnel name. | [optional] 
**source** | **str** | Source IP address of the tunnel. | [optional] 
**destination** | **str** | Destination IP address of the tunnel. | [optional] 
**ip6** | **str** | IPv6 address of the tunnel. | [optional] 
**interface** | **str** | Interface name. | [optional] 
**use_sdwan** | **str** | Enable/disable use of SD-WAN to reach remote gateway.    disable:Disable use of SD-WAN to reach remote gateway.    enable:Enable use of SD-WAN to reach remote gateway. | [optional] 
**auto_asic_offload** | **str** | Enable/disable tunnel ASIC offloading.    enable:Enable auto ASIC offloading.    disable:Disable ASIC offloading. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sit_tunnel_name_get200_response import SystemSitTunnelNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSitTunnelNameGet200Response from a JSON string
system_sit_tunnel_name_get200_response_instance = SystemSitTunnelNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSitTunnelNameGet200Response.to_json())

# convert the object into a dict
system_sit_tunnel_name_get200_response_dict = system_sit_tunnel_name_get200_response_instance.to_dict()
# create an instance of SystemSitTunnelNameGet200Response from a dict
system_sit_tunnel_name_get200_response_from_dict = SystemSitTunnelNameGet200Response.from_dict(system_sit_tunnel_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


