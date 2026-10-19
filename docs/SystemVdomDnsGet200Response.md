# SystemVdomDnsGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vdom_dns** | **str** | Enable/disable configuring DNS servers for the current VDOM.    enable:Enable configuring DNS servers for the current VDOM.    disable:Disable configuring DNS servers for the current VDOM. | [optional] 
**primary** | **str** | Primary DNS server IP address for the VDOM. | [optional] 
**secondary** | **str** | Secondary DNS server IP address for the VDOM. | [optional] 
**protocol** | **str** | DNS transport protocols.    cleartext:DNS over UDP/53, DNS over TCP/53.    dot:DNS over TLS/853.    doh:DNS over HTTPS/443. | [optional] 
**ssl_certificate** | **str** | Name of local certificate for SSL connections. | [optional] 
**server_hostname** | [**List[SystemDnsGet200ResponseServerHostnameInner]**](SystemDnsGet200ResponseServerHostnameInner.md) | DNS server host name list. | [optional] 
**ip6_primary** | **str** | Primary IPv6 DNS server IP address for the VDOM. | [optional] 
**ip6_secondary** | **str** | Secondary IPv6 DNS server IP address for the VDOM. | [optional] 
**source_ip** | **str** | Source IP for communications with the DNS server. | [optional] 
**source_ip_interface** | **str** | IP address of the specified interface as the source IP address. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 
**server_select_method** | **str** | Specify how configured servers are prioritized.    least-rtt:Select servers based on least round trip time.    failover:Select servers based on the order they are configured. | [optional] 
**alt_primary** | **str** | Alternate primary DNS server. This is not used as a failover DNS server. | [optional] 
**alt_secondary** | **str** | Alternate secondary DNS server. This is not used as a failover DNS server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_vdom_dns_get200_response import SystemVdomDnsGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVdomDnsGet200Response from a JSON string
system_vdom_dns_get200_response_instance = SystemVdomDnsGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemVdomDnsGet200Response.to_json())

# convert the object into a dict
system_vdom_dns_get200_response_dict = system_vdom_dns_get200_response_instance.to_dict()
# create an instance of SystemVdomDnsGet200Response from a dict
system_vdom_dns_get200_response_from_dict = SystemVdomDnsGet200Response.from_dict(system_vdom_dns_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


