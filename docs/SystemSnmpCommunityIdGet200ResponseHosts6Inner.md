# SystemSnmpCommunityIdGet200ResponseHosts6Inner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Host6 entry ID. | [optional] 
**source_ipv6** | **str** | Source IPv6 address for SNMP traps. | [optional] 
**ipv6** | **str** | SNMP manager IPv6 address prefix. | [optional] 
**ha_direct** | **str** | Enable/disable direct management of HA cluster members.    enable:Enable setting.    disable:Disable setting. | [optional] 
**host_type** | **str** | Control whether the SNMP manager sends SNMP queries, receives SNMP traps, or both.    any:Accept queries from and send traps to this SNMP manager.    query:Accept queries from this SNMP manager but do not send traps.    trap:Send traps to this SNMP manager but do not accept SNMP queries from this SNMP manager. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_snmp_community_id_get200_response_hosts6_inner import SystemSnmpCommunityIdGet200ResponseHosts6Inner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSnmpCommunityIdGet200ResponseHosts6Inner from a JSON string
system_snmp_community_id_get200_response_hosts6_inner_instance = SystemSnmpCommunityIdGet200ResponseHosts6Inner.from_json(json)
# print the JSON string representation of the object
print(SystemSnmpCommunityIdGet200ResponseHosts6Inner.to_json())

# convert the object into a dict
system_snmp_community_id_get200_response_hosts6_inner_dict = system_snmp_community_id_get200_response_hosts6_inner_instance.to_dict()
# create an instance of SystemSnmpCommunityIdGet200ResponseHosts6Inner from a dict
system_snmp_community_id_get200_response_hosts6_inner_from_dict = SystemSnmpCommunityIdGet200ResponseHosts6Inner.from_dict(system_snmp_community_id_get200_response_hosts6_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


