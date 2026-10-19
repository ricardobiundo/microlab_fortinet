# WirelessControllerSnmpGet200ResponseCommunityInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Community ID. | [optional] 
**name** | **str** | Community name. | [optional] 
**status** | **str** | Enable/disable this SNMP community.    enable:Enable setting.    disable:Disable setting. | [optional] 
**query_v1_status** | **str** | Enable/disable SNMP v1 queries.    enable:Enable setting.    disable:Disable setting. | [optional] 
**query_v2c_status** | **str** | Enable/disable SNMP v2c queries.    enable:Enable setting.    disable:Disable setting. | [optional] 
**trap_v1_status** | **str** | Enable/disable SNMP v1 traps.    enable:Enable setting.    disable:Disable setting. | [optional] 
**trap_v2c_status** | **str** | Enable/disable SNMP v2c traps.    enable:Enable setting.    disable:Disable setting. | [optional] 
**hosts** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInnerHostsInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInnerHostsInner.md) | Configure IPv4 SNMP managers (hosts). | [optional] 
**hosts6** | [**List[WirelessControllerSnmpGet200ResponseCommunityInnerHosts6Inner]**](WirelessControllerSnmpGet200ResponseCommunityInnerHosts6Inner.md) | Configure IPv6 SNMP managers (hosts). | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_snmp_get200_response_community_inner import WirelessControllerSnmpGet200ResponseCommunityInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerSnmpGet200ResponseCommunityInner from a JSON string
wireless_controller_snmp_get200_response_community_inner_instance = WirelessControllerSnmpGet200ResponseCommunityInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerSnmpGet200ResponseCommunityInner.to_json())

# convert the object into a dict
wireless_controller_snmp_get200_response_community_inner_dict = wireless_controller_snmp_get200_response_community_inner_instance.to_dict()
# create an instance of WirelessControllerSnmpGet200ResponseCommunityInner from a dict
wireless_controller_snmp_get200_response_community_inner_from_dict = WirelessControllerSnmpGet200ResponseCommunityInner.from_dict(wireless_controller_snmp_get200_response_community_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


