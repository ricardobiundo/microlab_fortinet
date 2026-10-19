# SystemDnsDatabaseNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Zone name. | [optional] 
**status** | **str** | Enable/disable this DNS zone.    enable:Enable setting.    disable:Disable setting. | [optional] 
**domain** | **str** | Domain name. | [optional] 
**allow_transfer** | **str** | DNS zone transfer IP address list. | [optional] 
**type** | **str** | Zone type (primary to manage entries directly, secondary to import entries from other zones).    primary:Primary DNS zone, to manage entries directly.    secondary:Secondary DNS zone, to import entries from other DNS zones. | [optional] 
**view** | **str** | Zone view (public to serve public clients, shadow to serve internal clients).    shadow:Shadow DNS zone to serve internal clients.    public:Public DNS zone to serve public clients.    shadow-ztna:implicit DNS zone for ztna dox tunnel.    proxy:Shadow DNS zone for internal proxy. | [optional] 
**ip_primary** | **str** | IP address of primary DNS server. Entries in this primary DNS server and imported into the DNS zone. | [optional] 
**primary_name** | **str** | Domain name of the default DNS server for this zone. | [optional] 
**contact** | **str** | Email address of the administrator for this zone. You can specify only the username, such as admin or the full email address, such as admin@test.com When using only a username, the domain of the email will be this zone. | [optional] 
**ttl** | **int** | Default time-to-live value for the entries of this DNS zone (0 - 2147483647 sec, default &#x3D; 86400). | [optional] 
**authoritative** | **str** | Enable/disable authoritative zone.    enable:Enable authoritative zone.    disable:Disable authoritative zone. | [optional] 
**forwarder** | **str** | DNS zone forwarder IP address list. | [optional] 
**forwarder6** | **str** | Forwarder IPv6 address. | [optional] 
**source_ip** | **str** | Source IP for forwarding to DNS server. | [optional] 
**source_ip6** | **str** | IPv6 source IP address for forwarding to DNS server. | [optional] 
**source_ip_interface** | **str** | IP address of the specified interface as the source IP address. | [optional] 
**rr_max** | **int** | Maximum number of resource records (10 - 65536, 0 means infinite). | [optional] 
**dns_entry** | [**List[SystemDnsDatabaseNameGet200ResponseDnsEntryInner]**](SystemDnsDatabaseNameGet200ResponseDnsEntryInner.md) | DNS entry. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dns_database_name_get200_response import SystemDnsDatabaseNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDnsDatabaseNameGet200Response from a JSON string
system_dns_database_name_get200_response_instance = SystemDnsDatabaseNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemDnsDatabaseNameGet200Response.to_json())

# convert the object into a dict
system_dns_database_name_get200_response_dict = system_dns_database_name_get200_response_instance.to_dict()
# create an instance of SystemDnsDatabaseNameGet200Response from a dict
system_dns_database_name_get200_response_from_dict = SystemDnsDatabaseNameGet200Response.from_dict(system_dns_database_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


