# SystemFabricVpnGet200ResponseAdvertisedSubnetsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**prefix** | **str** | Network prefix. | [optional] 
**access** | **str** | Access policy direction.    inbound:Allow inbound traffic to subnet.    bidirectional:Allow inbound and outbound traffic to subnet. | [optional] 
**bgp_network** | **int** | Underlying BGP network. | [optional] 
**firewall_address** | **str** | Underlying firewall address. | [optional] 
**policies** | **int** | Underlying policies. | [optional] 

## Example

```python
from microlab_fortinet.models.system_fabric_vpn_get200_response_advertised_subnets_inner import SystemFabricVpnGet200ResponseAdvertisedSubnetsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFabricVpnGet200ResponseAdvertisedSubnetsInner from a JSON string
system_fabric_vpn_get200_response_advertised_subnets_inner_instance = SystemFabricVpnGet200ResponseAdvertisedSubnetsInner.from_json(json)
# print the JSON string representation of the object
print(SystemFabricVpnGet200ResponseAdvertisedSubnetsInner.to_json())

# convert the object into a dict
system_fabric_vpn_get200_response_advertised_subnets_inner_dict = system_fabric_vpn_get200_response_advertised_subnets_inner_instance.to_dict()
# create an instance of SystemFabricVpnGet200ResponseAdvertisedSubnetsInner from a dict
system_fabric_vpn_get200_response_advertised_subnets_inner_from_dict = SystemFabricVpnGet200ResponseAdvertisedSubnetsInner.from_dict(system_fabric_vpn_get200_response_advertised_subnets_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


