# SystemSdwanGet200ResponseMembersInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**seq_num** | **int** | Sequence number(1-512). | [optional] 
**interface** | **str** | Interface name. | [optional] 
**zone** | **str** | Zone name. | [optional] 
**gateway** | **str** | The default gateway for this interface. Usually the default gateway of the Internet service provider that this interface is connected to. | [optional] 
**preferred_source** | **str** | Preferred source of route for this member. | [optional] 
**source** | **str** | Source IP address used in the health-check packet to the server. | [optional] 
**gateway6** | **str** | IPv6 gateway. | [optional] 
**source6** | **str** | Source IPv6 address used in the health-check packet to the server. | [optional] 
**cost** | **int** | Cost of this interface for services in SLA mode (0 - 4294967295, default &#x3D; 0). | [optional] 
**weight** | **int** | Weight of this interface for weighted load balancing. (1 - 255) More traffic is directed to interfaces with higher weights. | [optional] 
**priority** | **int** | Priority of the interface for IPv4 (1 - 65535, default &#x3D; 1). Used for SD-WAN rules or priority rules. | [optional] 
**priority6** | **int** | Priority of the interface for IPv6 (1 - 65535, default &#x3D; 1024). Used for SD-WAN rules or priority rules. | [optional] 
**priority_in_sla** | **int** | Preferred priority of routes to this member when this member is in-sla (0 - 65535, default &#x3D; 0). | [optional] 
**priority_out_sla** | **int** | Preferred priority of routes to this member when this member is out-of-sla (0 - 65535, default &#x3D; 0). | [optional] 
**spillover_threshold** | **int** | Egress spillover threshold for this interface (0 - 16776000 kbit/s). When this traffic volume threshold is reached, new sessions spill over to other interfaces in the SD-WAN. | [optional] 
**ingress_spillover_threshold** | **int** | Ingress spillover threshold for this interface (0 - 16776000 kbit/s). When this traffic volume threshold is reached, new sessions spill over to other interfaces in the SD-WAN. | [optional] 
**volume_ratio** | **int** | Measured volume ratio (this value / sum of all values &#x3D; percentage of link volume, 1 - 255). | [optional] 
**status** | **str** | Enable/disable this interface in the SD-WAN.    disable:Disable this interface in the SD-WAN.    enable:Enable this interface in the SD-WAN. | [optional] 
**transport_group** | **int** | Measured transport group (0 - 255). | [optional] 
**comment** | **str** | Comments. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdwan_get200_response_members_inner import SystemSdwanGet200ResponseMembersInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdwanGet200ResponseMembersInner from a JSON string
system_sdwan_get200_response_members_inner_instance = SystemSdwanGet200ResponseMembersInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdwanGet200ResponseMembersInner.to_json())

# convert the object into a dict
system_sdwan_get200_response_members_inner_dict = system_sdwan_get200_response_members_inner_instance.to_dict()
# create an instance of SystemSdwanGet200ResponseMembersInner from a dict
system_sdwan_get200_response_members_inner_from_dict = SystemSdwanGet200ResponseMembersInner.from_dict(system_sdwan_get200_response_members_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


