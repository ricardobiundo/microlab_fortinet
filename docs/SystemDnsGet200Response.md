# SystemDnsGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**primary** | **str** | Primary DNS server IP address. | [optional] 
**secondary** | **str** | Secondary DNS server IP address. | [optional] 
**protocol** | **str** | DNS transport protocols.    cleartext:DNS over UDP/53, DNS over TCP/53.    dot:DNS over TLS/853.    doh:DNS over HTTPS/443. | [optional] 
**ssl_certificate** | **str** | Name of local certificate for SSL connections. | [optional] 
**server_hostname** | [**List[SystemDnsGet200ResponseServerHostnameInner]**](SystemDnsGet200ResponseServerHostnameInner.md) | DNS server host name list. | [optional] 
**domain** | [**List[SystemDnsGet200ResponseDomainInner]**](SystemDnsGet200ResponseDomainInner.md) | Search suffix list for hostname lookup. | [optional] 
**ip6_primary** | **str** | Primary DNS server IPv6 address. | [optional] 
**ip6_secondary** | **str** | Secondary DNS server IPv6 address. | [optional] 
**timeout** | **int** | DNS query timeout interval in seconds (1 - 10). | [optional] 
**retry** | **int** | Number of times to retry (0 - 5). | [optional] 
**dns_cache_limit** | **int** | Maximum number of records in the DNS cache. | [optional] 
**dns_cache_ttl** | **int** | Duration in seconds that the DNS cache retains information. | [optional] 
**cache_notfound_responses** | **str** | Enable/disable response from the DNS server when a record is not in cache.    disable:Disable cache NOTFOUND responses from DNS server.    enable:Enable cache NOTFOUND responses from DNS server. | [optional] 
**source_ip** | **str** | IP address used by the DNS server as its source IP. | [optional] 
**source_ip_interface** | **str** | IP address of the specified interface as the source IP address. | [optional] 
**root_servers** | **str** | Configure up to two preferred servers that serve the DNS root zone (default uses all 13 root servers). | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 
**server_select_method** | **str** | Specify how configured servers are prioritized.    least-rtt:Select servers based on least round trip time.    failover:Select servers based on the order they are configured. | [optional] 
**alt_primary** | **str** | Alternate primary DNS server. This is not used as a failover DNS server. | [optional] 
**alt_secondary** | **str** | Alternate secondary DNS server. This is not used as a failover DNS server. | [optional] 
**log** | **str** | Local DNS log setting.    disable:Disable.    error:Enable local DNS error log.    all:Enable local DNS log. | [optional] 
**fqdn_cache_ttl** | **int** | FQDN cache time to live in seconds (0 - 86400, default &#x3D; 0). | [optional] 
**fqdn_max_refresh** | **int** | FQDN cache maximum refresh time in seconds (3600 - 86400, default &#x3D; 3600). | [optional] 
**fqdn_min_refresh** | **int** | FQDN cache minimum refresh time in seconds (10 - 3600, default &#x3D; 60). | [optional] 
**hostname_ttl** | **int** | TTL of hostname table entries (60 - 86400). | [optional] 
**hostname_limit** | **int** | Limit of the number of hostname table entries (0 - 50000). | [optional] 

## Example

```python
from microlab_fortinet.models.system_dns_get200_response import SystemDnsGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDnsGet200Response from a JSON string
system_dns_get200_response_instance = SystemDnsGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemDnsGet200Response.to_json())

# convert the object into a dict
system_dns_get200_response_dict = system_dns_get200_response_instance.to_dict()
# create an instance of SystemDnsGet200Response from a dict
system_dns_get200_response_from_dict = SystemDnsGet200Response.from_dict(system_dns_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


