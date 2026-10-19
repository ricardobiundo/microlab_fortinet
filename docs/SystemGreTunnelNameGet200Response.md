# SystemGreTunnelNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Tunnel name. | [optional] 
**interface** | **str** | Interface name. | [optional] 
**ip_version** | **str** | IP version to use for VPN interface.    4:Use IPv4 addressing for gateways.    6:Use IPv6 addressing for gateways. | [optional] 
**remote_gw6** | **str** | IPv6 address of the remote gateway. | [optional] 
**local_gw6** | **str** | IPv6 address of the local gateway. | [optional] 
**remote_gw** | **str** | IP address of the remote gateway. | [optional] 
**local_gw** | **str** | IP address of the local gateway. | [optional] 
**use_sdwan** | **str** | Enable/disable use of SD-WAN to reach remote gateway.    disable:Disable use of SD-WAN to reach remote gateway.    enable:Enable use of SD-WAN to reach remote gateway. | [optional] 
**sequence_number_transmission** | **str** | Enable/disable including of sequence numbers in transmitted GRE packets.    disable:Include sequence numbers in transmitted GRE packets.    enable:Do not  include sequence numbers in transmitted GRE packets. | [optional] 
**sequence_number_reception** | **str** | Enable/disable validating sequence numbers in received GRE packets.    disable:Do not validate sequence number in received GRE packets.    enable:Validate sequence numbers in received GRE packets. | [optional] 
**checksum_transmission** | **str** | Enable/disable including checksums in transmitted GRE packets.    disable:Do not include checksums in transmitted GRE packets.    enable:Include checksums in transmitted GRE packets. | [optional] 
**checksum_reception** | **str** | Enable/disable validating checksums in received GRE packets.    disable:Do not validate checksums in received GRE packets.    enable:Validate checksums in received GRE packets. | [optional] 
**key_outbound** | **int** | Include this key in transmitted GRE packets (0 - 4294967295). | [optional] 
**key_inbound** | **int** | Require received GRE packets contain this key (0 - 4294967295). | [optional] 
**dscp_copying** | **str** | Enable/disable DSCP copying.    disable:Disable DSCP copying.    enable:Enable DSCP copying. | [optional] 
**diffservcode** | **str** | DiffServ setting to be applied to GRE tunnel outer IP header. | [optional] 
**keepalive_interval** | **int** | Keepalive message interval (0 - 32767, 0 &#x3D; disabled). | [optional] 
**keepalive_failtimes** | **int** | Number of consecutive unreturned keepalive messages before a GRE connection is considered down (1 - 255). | [optional] 

## Example

```python
from microlab_fortinet.models.system_gre_tunnel_name_get200_response import SystemGreTunnelNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemGreTunnelNameGet200Response from a JSON string
system_gre_tunnel_name_get200_response_instance = SystemGreTunnelNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemGreTunnelNameGet200Response.to_json())

# convert the object into a dict
system_gre_tunnel_name_get200_response_dict = system_gre_tunnel_name_get200_response_instance.to_dict()
# create an instance of SystemGreTunnelNameGet200Response from a dict
system_gre_tunnel_name_get200_response_from_dict = SystemGreTunnelNameGet200Response.from_dict(system_gre_tunnel_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


