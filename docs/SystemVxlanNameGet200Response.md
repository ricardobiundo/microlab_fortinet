# SystemVxlanNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | VXLAN device or interface name. Must be a unique interface name. | [optional] 
**interface** | **str** | Outgoing interface for VXLAN encapsulated traffic. | [optional] 
**vni** | **int** | VXLAN network ID. | [optional] 
**ip_version** | **str** | IP version to use for the VXLAN interface and so for communication over the VXLAN. IPv4 or IPv6 unicast or multicast.    ipv4-unicast:Use IPv4 unicast addressing over the VXLAN.    ipv6-unicast:Use IPv6 unicast addressing over the VXLAN.    ipv4-multicast:Use IPv4 multicast addressing over the VXLAN.    ipv6-multicast:Use IPv6 multicast addressing over the VXLAN. | [optional] 
**remote_ip** | [**List[SystemSdnConnectorNameGet200ResponseServerListInner]**](SystemSdnConnectorNameGet200ResponseServerListInner.md) | IPv4 address of the VXLAN interface on the device at the remote end of the VXLAN. | [optional] 
**local_ip** | **str** | IPv4 address to use as the source address for egress VXLAN packets. | [optional] 
**remote_ip6** | [**List[SystemVxlanNameGet200ResponseRemoteIp6Inner]**](SystemVxlanNameGet200ResponseRemoteIp6Inner.md) | IPv6 IP address of the VXLAN interface on the device at the remote end of the VXLAN. | [optional] 
**local_ip6** | **str** | IPv6 address to use as the source address for egress VXLAN packets. | [optional] 
**dstport** | **int** | VXLAN destination port (1 - 65535, default &#x3D; 4789). | [optional] 
**multicast_ttl** | **int** | VXLAN multicast TTL (1-255, default &#x3D; 0). | [optional] 
**evpn_id** | **int** | EVPN instance. | [optional] 
**learn_from_traffic** | **str** | Enable/disable VXLAN MAC learning from traffic.    enable:Enable VXLAN MAC learning from traffic.    disable:Disable VXLAN MAC learning from traffic. | [optional] 

## Example

```python
from microlab_fortinet.models.system_vxlan_name_get200_response import SystemVxlanNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVxlanNameGet200Response from a JSON string
system_vxlan_name_get200_response_instance = SystemVxlanNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemVxlanNameGet200Response.to_json())

# convert the object into a dict
system_vxlan_name_get200_response_dict = system_vxlan_name_get200_response_instance.to_dict()
# create an instance of SystemVxlanNameGet200Response from a dict
system_vxlan_name_get200_response_from_dict = SystemVxlanNameGet200Response.from_dict(system_vxlan_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


