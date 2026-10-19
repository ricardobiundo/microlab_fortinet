# SystemSdnVpnNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Public cloud VPN name. | [optional] 
**sdn** | **str** | SDN connector name. | [optional] 
**remote_type** | **str** | Type of remote device.    vgw:Virtual private gateway.    tgw:Transit gateway. | [optional] 
**routing_type** | **str** | Type of routing.    static:Static routing.    dynamic:Dynamic routing. | [optional] 
**vgw_id** | **str** | Virtual private gateway id. | [optional] 
**tgw_id** | **str** | Transit gateway id. | [optional] 
**subnet_id** | **str** | AWS subnet id for TGW route propagation. | [optional] 
**bgp_as** | **int** | BGP Router AS number. | [optional] 
**cgw_gateway** | **str** | Public IP address of the customer gateway. | [optional] 
**nat_traversal** | **str** | Enable/disable use for NAT traversal. Please enable if your FortiGate device is behind a NAT/PAT device.    disable:Disable NAT traversal.    enable:Enable NAT traversal. | [optional] 
**tunnel_interface** | **str** | Tunnel interface with public IP. | [optional] 
**internal_interface** | **str** | Internal interface with local subnet. | [optional] 
**local_cidr** | **str** | Local subnet address and subnet mask. | [optional] 
**remote_cidr** | **str** | Remote subnet address and subnet mask. | [optional] 
**cgw_name** | **str** | AWS customer gateway name to be created. | [optional] 
**psksecret** | **str** | Pre-shared secret for PSK authentication. Auto-generated if not specified | [optional] 
**type** | **int** | SDN VPN type. | [optional] 
**status** | **int** | SDN VPN status. | [optional] 
**code** | **int** | SDN VPN error code. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdn_vpn_name_get200_response import SystemSdnVpnNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdnVpnNameGet200Response from a JSON string
system_sdn_vpn_name_get200_response_instance = SystemSdnVpnNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSdnVpnNameGet200Response.to_json())

# convert the object into a dict
system_sdn_vpn_name_get200_response_dict = system_sdn_vpn_name_get200_response_instance.to_dict()
# create an instance of SystemSdnVpnNameGet200Response from a dict
system_sdn_vpn_name_get200_response_from_dict = SystemSdnVpnNameGet200Response.from_dict(system_sdn_vpn_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


