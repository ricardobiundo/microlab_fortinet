# SystemIpamGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable IP address management services.    enable:Enable integration with IP address management services.    disable:Disable integration with IP address management services. | [optional] 
**server_type** | **str** | Configure the type of IPAM server to use.    fabric-root:Use the IPAM server running on the Security Fabric root. | [optional] 
**automatic_conflict_resolution** | **str** | Enable/disable automatic conflict resolution.    disable:Disable automatic conflict resolution.    enable:Enable automatic conflict resolution. | [optional] 
**require_subnet_size_match** | **str** | Enable/disable reassignment of subnets to make requested and actual sizes match.    disable:Disable requiring subnet sizes to match.    enable:Enable requiring subnet sizes to match. | [optional] 
**manage_lan_addresses** | **str** | Enable/disable default management of LAN interface addresses.    disable:Disable LAN interface address management by default.    enable:Enable LAN interface address management by default. | [optional] 
**manage_lan_extension_addresses** | **str** | Enable/disable default management of FortiExtender LAN extension interface addresses.    disable:Disable FortiExtender LAN extension interface address management by default.    enable:Enable FortiExtender LAN extension interface address management by default. | [optional] 
**manage_ssid_addresses** | **str** | Enable/disable default management of FortiAP SSID addresses.    disable:Disable FortiAP SSID address management by default.    enable:Enable FortiAP SSID address management by default. | [optional] 
**pools** | [**List[SystemIpamGet200ResponsePoolsInner]**](SystemIpamGet200ResponsePoolsInner.md) | Configure IPAM pools. | [optional] 
**rules** | [**List[SystemIpamGet200ResponseRulesInner]**](SystemIpamGet200ResponseRulesInner.md) | Configure IPAM allocation rules. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ipam_get200_response import SystemIpamGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIpamGet200Response from a JSON string
system_ipam_get200_response_instance = SystemIpamGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemIpamGet200Response.to_json())

# convert the object into a dict
system_ipam_get200_response_dict = system_ipam_get200_response_instance.to_dict()
# create an instance of SystemIpamGet200Response from a dict
system_ipam_get200_response_from_dict = SystemIpamGet200Response.from_dict(system_ipam_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


