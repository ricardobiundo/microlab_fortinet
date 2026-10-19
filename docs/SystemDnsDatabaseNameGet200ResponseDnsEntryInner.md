# SystemDnsDatabaseNameGet200ResponseDnsEntryInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | DNS entry ID. | [optional] 
**status** | **str** | Enable/disable resource record status.    enable:Enable resource record status.    disable:Disable resource record status. | [optional] 
**type** | **str** | Resource record type.    A:Host type.    NS:Name server type.    CNAME:Canonical name type.    MX:Mail exchange type.    AAAA:IPv6 host type.    PTR:Pointer type.    PTR_V6:IPv6 pointer type. | [optional] 
**ttl** | **int** | Time-to-live for this entry (0 to 2147483647 sec, default &#x3D; 0). | [optional] 
**preference** | **int** | DNS entry preference (0 - 65535, highest preference &#x3D; 0, default &#x3D; 10). | [optional] 
**ip** | **str** | IPv4 address of the host. | [optional] 
**ipv6** | **str** | IPv6 address of the host. | [optional] 
**hostname** | **str** | Name of the host. | [optional] 
**canonical_name** | **str** | Canonical name of the host. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dns_database_name_get200_response_dns_entry_inner import SystemDnsDatabaseNameGet200ResponseDnsEntryInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDnsDatabaseNameGet200ResponseDnsEntryInner from a JSON string
system_dns_database_name_get200_response_dns_entry_inner_instance = SystemDnsDatabaseNameGet200ResponseDnsEntryInner.from_json(json)
# print the JSON string representation of the object
print(SystemDnsDatabaseNameGet200ResponseDnsEntryInner.to_json())

# convert the object into a dict
system_dns_database_name_get200_response_dns_entry_inner_dict = system_dns_database_name_get200_response_dns_entry_inner_instance.to_dict()
# create an instance of SystemDnsDatabaseNameGet200ResponseDnsEntryInner from a dict
system_dns_database_name_get200_response_dns_entry_inner_from_dict = SystemDnsDatabaseNameGet200ResponseDnsEntryInner.from_dict(system_dns_database_name_get200_response_dns_entry_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


