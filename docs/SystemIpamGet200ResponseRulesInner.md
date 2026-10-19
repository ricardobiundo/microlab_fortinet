# SystemIpamGet200ResponseRulesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | IPAM rule name. | [optional] 
**description** | **str** | Description. | [optional] 
**device** | [**List[SystemIpamGet200ResponseRulesInnerDeviceInner]**](SystemIpamGet200ResponseRulesInnerDeviceInner.md) | Configure serial number or wildcard of FortiGate to match. | [optional] 
**interface** | [**List[SystemIpamGet200ResponseRulesInnerInterfaceInner]**](SystemIpamGet200ResponseRulesInnerInterfaceInner.md) | Configure name or wildcard of interface to match. | [optional] 
**role** | **str** | Configure role of interface to match.    any:Match any interface role.    lan:Match interface role lan.    wan:Match interface role wan.    dmz:Match interface role dmz.    undefined:Match interface role undefined. | [optional] 
**pool** | [**List[SystemIpamGet200ResponseRulesInnerPoolInner]**](SystemIpamGet200ResponseRulesInnerPoolInner.md) | Configure name of IPAM pool to use. | [optional] 
**dhcp** | **str** | Enable/disable DHCP server for matching IPAM interfaces.    enable:Enable DHCP server on matched IPAM interface.    disable:Disable DHCP server on matched IPAM interface. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ipam_get200_response_rules_inner import SystemIpamGet200ResponseRulesInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIpamGet200ResponseRulesInner from a JSON string
system_ipam_get200_response_rules_inner_instance = SystemIpamGet200ResponseRulesInner.from_json(json)
# print the JSON string representation of the object
print(SystemIpamGet200ResponseRulesInner.to_json())

# convert the object into a dict
system_ipam_get200_response_rules_inner_dict = system_ipam_get200_response_rules_inner_instance.to_dict()
# create an instance of SystemIpamGet200ResponseRulesInner from a dict
system_ipam_get200_response_rules_inner_from_dict = SystemIpamGet200ResponseRulesInner.from_dict(system_ipam_get200_response_rules_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


