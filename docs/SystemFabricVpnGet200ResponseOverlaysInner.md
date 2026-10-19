# SystemFabricVpnGet200ResponseOverlaysInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Overlay name. | [optional] 
**ipsec_network_id** | **int** | VPN gateway network ID. | [optional] 
**overlay_tunnel_block** | **str** | IPv4 address and subnet mask for the overlay tunnel , syntax: X.X.X.X/24. | [optional] 
**remote_gw** | **str** | IP address of the hub gateway (Set by hub). | [optional] 
**interface** | **str** | Underlying interface name. | [optional] 
**bgp_neighbor** | **str** | Underlying BGP neighbor entry. | [optional] 
**overlay_policy** | **int** | The overlay policy to allow ADVPN thru traffic. | [optional] 
**bgp_network** | **int** | Underlying BGP network. | [optional] 
**route_policy** | **int** | Underlying router policy. | [optional] 
**bgp_neighbor_group** | **str** | Underlying BGP neighbor group entry. | [optional] 
**bgp_neighbor_range** | **int** | Underlying BGP neighbor range entry. | [optional] 
**ipsec_phase1** | **str** | IPsec interface. | [optional] 
**sdwan_member** | **int** | Reference to SD-WAN member entry. | [optional] 

## Example

```python
from microlab_fortinet.models.system_fabric_vpn_get200_response_overlays_inner import SystemFabricVpnGet200ResponseOverlaysInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFabricVpnGet200ResponseOverlaysInner from a JSON string
system_fabric_vpn_get200_response_overlays_inner_instance = SystemFabricVpnGet200ResponseOverlaysInner.from_json(json)
# print the JSON string representation of the object
print(SystemFabricVpnGet200ResponseOverlaysInner.to_json())

# convert the object into a dict
system_fabric_vpn_get200_response_overlays_inner_dict = system_fabric_vpn_get200_response_overlays_inner_instance.to_dict()
# create an instance of SystemFabricVpnGet200ResponseOverlaysInner from a dict
system_fabric_vpn_get200_response_overlays_inner_from_dict = SystemFabricVpnGet200ResponseOverlaysInner.from_dict(system_fabric_vpn_get200_response_overlays_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


