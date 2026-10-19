# WirelessControllerSnmpGet200ResponseCommunityInnerHosts6Inner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Host6 entry ID. | [optional] 
**ipv6** | **str** | IPv6 address of the SNMP manager (host). | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_snmp_get200_response_community_inner_hosts6_inner import WirelessControllerSnmpGet200ResponseCommunityInnerHosts6Inner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerSnmpGet200ResponseCommunityInnerHosts6Inner from a JSON string
wireless_controller_snmp_get200_response_community_inner_hosts6_inner_instance = WirelessControllerSnmpGet200ResponseCommunityInnerHosts6Inner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerSnmpGet200ResponseCommunityInnerHosts6Inner.to_json())

# convert the object into a dict
wireless_controller_snmp_get200_response_community_inner_hosts6_inner_dict = wireless_controller_snmp_get200_response_community_inner_hosts6_inner_instance.to_dict()
# create an instance of WirelessControllerSnmpGet200ResponseCommunityInnerHosts6Inner from a dict
wireless_controller_snmp_get200_response_community_inner_hosts6_inner_from_dict = WirelessControllerSnmpGet200ResponseCommunityInnerHosts6Inner.from_dict(wireless_controller_snmp_get200_response_community_inner_hosts6_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


