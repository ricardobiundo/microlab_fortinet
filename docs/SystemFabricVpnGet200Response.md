# SystemFabricVpnGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable Fabric VPN.    enable:Enable Fabric VPN.    disable:Disable Fabric VPN. | [optional] 
**sync_mode** | **str** | Setting synchronized by fabric or manual.    enable:Enable fabric led configuration synchronization.    disable:Disable fabric led configuration synchronization. | [optional] 
**branch_name** | **str** | Branch name. | [optional] 
**policy_rule** | **str** | Policy creation rule.    health-check:Create health check policy automatically.    manual:All policies will be created manually.    auto:Automatically create allow policies. | [optional] 
**vpn_role** | **str** | Fabric VPN role.    hub:VPN hub.    spoke:VPN spoke. | [optional] 
**overlays** | [**List[SystemFabricVpnGet200ResponseOverlaysInner]**](SystemFabricVpnGet200ResponseOverlaysInner.md) | Local overlay interfaces table. | [optional] 
**advertised_subnets** | [**List[SystemFabricVpnGet200ResponseAdvertisedSubnetsInner]**](SystemFabricVpnGet200ResponseAdvertisedSubnetsInner.md) | Local advertised subnets. | [optional] 
**loopback_address_block** | **str** | IPv4 address and subnet mask for hub&#39;s loopback address, syntax: X.X.X.X/24. | [optional] 
**loopback_interface** | **str** | Loopback interface. | [optional] 
**loopback_advertised_subnet** | **int** | Loopback advertised subnet reference. | [optional] 
**psksecret** | **str** | Pre-shared secret for ADVPN. | [optional] 
**bgp_as** | **str** | BGP Router AS number, asplain/asdot/asdot+ format. | [optional] 
**sdwan_zone** | **str** | Reference to created SD-WAN zone. | [optional] 
**health_checks** | **str** | Underlying health checks. | [optional] 

## Example

```python
from microlab_fortinet.models.system_fabric_vpn_get200_response import SystemFabricVpnGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFabricVpnGet200Response from a JSON string
system_fabric_vpn_get200_response_instance = SystemFabricVpnGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemFabricVpnGet200Response.to_json())

# convert the object into a dict
system_fabric_vpn_get200_response_dict = system_fabric_vpn_get200_response_instance.to_dict()
# create an instance of SystemFabricVpnGet200Response from a dict
system_fabric_vpn_get200_response_from_dict = SystemFabricVpnGet200Response.from_dict(system_fabric_vpn_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


