# SystemIpsUrlfilterDnsAddressGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** | DNS server IP address. | [optional] 
**status** | **str** | Enable/disable using this DNS server for IPS URL filter DNS queries.    enable:Enable this DNS server for IPS URL filter DNS queries.    disable:Disable this DNS server for IPS URL filter DNS queries. | [optional] 
**ipv6_capability** | **str** | Enable/disable this server for IPv6 queries.    enable:Enable setting.    disable:Disable setting. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ips_urlfilter_dns_address_get200_response import SystemIpsUrlfilterDnsAddressGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIpsUrlfilterDnsAddressGet200Response from a JSON string
system_ips_urlfilter_dns_address_get200_response_instance = SystemIpsUrlfilterDnsAddressGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemIpsUrlfilterDnsAddressGet200Response.to_json())

# convert the object into a dict
system_ips_urlfilter_dns_address_get200_response_dict = system_ips_urlfilter_dns_address_get200_response_instance.to_dict()
# create an instance of SystemIpsUrlfilterDnsAddressGet200Response from a dict
system_ips_urlfilter_dns_address_get200_response_from_dict = SystemIpsUrlfilterDnsAddressGet200Response.from_dict(system_ips_urlfilter_dns_address_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


