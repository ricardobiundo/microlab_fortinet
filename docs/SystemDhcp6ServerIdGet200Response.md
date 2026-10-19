# SystemDhcp6ServerIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**status** | **str** | Enable/disable this DHCPv6 configuration.    disable:Enable this DHCPv6 server configuration.    enable:Disable this DHCPv6 server configuration. | [optional] 
**rapid_commit** | **str** | Enable/disable allow/disallow rapid commit.    disable:Do not allow rapid commit.    enable:Allow rapid commit. | [optional] 
**lease_time** | **int** | Lease time in seconds, 0 means unlimited. | [optional] 
**dns_service** | **str** | Options for assigning DNS servers to DHCPv6 clients.    delegated:Delegated DNS settings.    default:Clients are assigned the FortiGate&#39;s configured DNS servers.    specify:Specify up to 3 DNS servers in the DHCPv6 server configuration. | [optional] 
**dns_search_list** | **str** | DNS search list options.    delegated:Delegated the DNS search list.    specify:Specify the DNS search list. | [optional] 
**dns_server1** | **str** | DNS server 1. | [optional] 
**dns_server2** | **str** | DNS server 2. | [optional] 
**dns_server3** | **str** | DNS server 3. | [optional] 
**dns_server4** | **str** | DNS server 4. | [optional] 
**domain** | **str** | Domain name suffix for the IP addresses that the DHCP server assigns to clients. | [optional] 
**subnet** | **str** | Subnet or subnet-id if the IP mode is delegated. | [optional] 
**interface** | **str** | DHCP server can assign IP configurations to clients connected to this interface. | [optional] 
**delegated_prefix_route** | **str** | Enable/disable automatically adding of routing for delegated prefix.    disable:Disable automatically adding of routing for delegated prefix.    enable:Enable automatically adding of routing for delegated prefix. | [optional] 
**options** | [**List[SystemDhcp6ServerIdGet200ResponseOptionsInner]**](SystemDhcp6ServerIdGet200ResponseOptionsInner.md) | DHCPv6 options. | [optional] 
**upstream_interface** | **str** | Interface name from where delegated information is provided. | [optional] 
**delegated_prefix_iaid** | **int** | IAID of obtained delegated-prefix from the upstream interface. | [optional] 
**ip_mode** | **str** | Method used to assign client IP.    range:Use range defined by start IP/end IP to assign client IP.    delegated:Use delegated prefix method to assign client IP. | [optional] 
**prefix_mode** | **str** | Assigning a prefix from a DHCPv6 client or RA.    dhcp6:Use delegated prefix from a DHCPv6 client.    ra:Use prefix from RA. | [optional] 
**prefix_range** | [**List[SystemDhcp6ServerIdGet200ResponsePrefixRangeInner]**](SystemDhcp6ServerIdGet200ResponsePrefixRangeInner.md) | DHCP prefix configuration. | [optional] 
**ip_range** | [**List[SystemDhcp6ServerIdGet200ResponseIpRangeInner]**](SystemDhcp6ServerIdGet200ResponseIpRangeInner.md) | DHCP IP range configuration. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dhcp6_server_id_get200_response import SystemDhcp6ServerIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDhcp6ServerIdGet200Response from a JSON string
system_dhcp6_server_id_get200_response_instance = SystemDhcp6ServerIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemDhcp6ServerIdGet200Response.to_json())

# convert the object into a dict
system_dhcp6_server_id_get200_response_dict = system_dhcp6_server_id_get200_response_instance.to_dict()
# create an instance of SystemDhcp6ServerIdGet200Response from a dict
system_dhcp6_server_id_get200_response_from_dict = SystemDhcp6ServerIdGet200Response.from_dict(system_dhcp6_server_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


