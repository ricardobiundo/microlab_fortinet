# SystemIpsUrlfilterDns6Address6Get200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address6** | **str** | IPv6 address of DNS server. | [optional] 
**status** | **str** | Enable/disable this server for IPv6 DNS queries.    enable:Enable setting.    disable:Disable setting. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ips_urlfilter_dns6_address6_get200_response import SystemIpsUrlfilterDns6Address6Get200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIpsUrlfilterDns6Address6Get200Response from a JSON string
system_ips_urlfilter_dns6_address6_get200_response_instance = SystemIpsUrlfilterDns6Address6Get200Response.from_json(json)
# print the JSON string representation of the object
print(SystemIpsUrlfilterDns6Address6Get200Response.to_json())

# convert the object into a dict
system_ips_urlfilter_dns6_address6_get200_response_dict = system_ips_urlfilter_dns6_address6_get200_response_instance.to_dict()
# create an instance of SystemIpsUrlfilterDns6Address6Get200Response from a dict
system_ips_urlfilter_dns6_address6_get200_response_from_dict = SystemIpsUrlfilterDns6Address6Get200Response.from_dict(system_ips_urlfilter_dns6_address6_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


