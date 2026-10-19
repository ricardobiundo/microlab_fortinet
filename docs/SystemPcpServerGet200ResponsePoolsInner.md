# SystemPcpServerGet200ResponsePoolsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | PCP pool name. | [optional] 
**description** | **str** | Description. | [optional] 
**id** | **int** | ID. | [optional] 
**client_subnet** | [**List[SystemPcpServerGet200ResponsePoolsInnerClientSubnetInner]**](SystemPcpServerGet200ResponsePoolsInnerClientSubnetInner.md) | Subnets from which PCP requests are accepted. | [optional] 
**ext_intf** | **str** | External interface name. | [optional] 
**arp_reply** | **str** | Enable to respond to ARP requests for external IP (default &#x3D; enable).    disable:Disable ARP reply.    enable:Enable ARP reply. | [optional] 
**extip** | **str** | IP address or address range on the external interface that you want to map to an address on the internal network. | [optional] 
**extport** | **str** | Incoming port number range that you want to map to a port number on the internal network. | [optional] 
**minimal_lifetime** | **int** | Minimal lifetime of a PCP mapping in seconds (60 - 300, default &#x3D; 120). | [optional] 
**maximal_lifetime** | **int** | Maximal lifetime of a PCP mapping in seconds (3600 - 604800, default &#x3D; 86400). | [optional] 
**client_mapping_limit** | **int** | Mapping limit per client (0 - 65535, default &#x3D; 0, 0 &#x3D; unlimited). | [optional] 
**mapping_filter_limit** | **int** | Filter limit per mapping (0 - 5, default &#x3D; 1). | [optional] 
**allow_opcode** | **str** | Allowed PCP opcode.    map:Allow opcode MAP.    peer:Allow opcode PEER.    announce:Allow opcode ANNOUNCE. | [optional] 
**third_party** | **str** | Allow/disallow third party option.    allow:Allow third party option.    disallow:Disallow third party opiton. | [optional] 
**third_party_subnet** | [**List[SystemPcpServerGet200ResponsePoolsInnerThirdPartySubnetInner]**](SystemPcpServerGet200ResponsePoolsInnerThirdPartySubnetInner.md) | Subnets from which third party requests are accepted. | [optional] 
**multicast_announcement** | **str** | Enable/disable multicast announcements.    enable:Enable multicast announcements.    disable:Disable multicast announcements. | [optional] 
**announcement_count** | **int** | Number of multicast announcements. | [optional] 
**intl_intf** | [**List[SystemAcmeGet200ResponseInterfaceInner]**](SystemAcmeGet200ResponseInterfaceInner.md) | Internal interface name. | [optional] 
**recycle_delay** | **int** | Minimum delay (in seconds) the PCP Server will wait before recycling mappings that have expired (0 - 3600, default &#x3D; 0). | [optional] 

## Example

```python
from microlab_fortinet.models.system_pcp_server_get200_response_pools_inner import SystemPcpServerGet200ResponsePoolsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPcpServerGet200ResponsePoolsInner from a JSON string
system_pcp_server_get200_response_pools_inner_instance = SystemPcpServerGet200ResponsePoolsInner.from_json(json)
# print the JSON string representation of the object
print(SystemPcpServerGet200ResponsePoolsInner.to_json())

# convert the object into a dict
system_pcp_server_get200_response_pools_inner_dict = system_pcp_server_get200_response_pools_inner_instance.to_dict()
# create an instance of SystemPcpServerGet200ResponsePoolsInner from a dict
system_pcp_server_get200_response_pools_inner_from_dict = SystemPcpServerGet200ResponsePoolsInner.from_dict(system_pcp_server_get200_response_pools_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


