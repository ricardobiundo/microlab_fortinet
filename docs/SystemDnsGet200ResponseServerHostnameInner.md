# SystemDnsGet200ResponseServerHostnameInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**hostname** | **str** | DNS server host name list separated by space (maximum 4 domains). | [optional] 

## Example

```python
from microlab_fortinet.models.system_dns_get200_response_server_hostname_inner import SystemDnsGet200ResponseServerHostnameInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDnsGet200ResponseServerHostnameInner from a JSON string
system_dns_get200_response_server_hostname_inner_instance = SystemDnsGet200ResponseServerHostnameInner.from_json(json)
# print the JSON string representation of the object
print(SystemDnsGet200ResponseServerHostnameInner.to_json())

# convert the object into a dict
system_dns_get200_response_server_hostname_inner_dict = system_dns_get200_response_server_hostname_inner_instance.to_dict()
# create an instance of SystemDnsGet200ResponseServerHostnameInner from a dict
system_dns_get200_response_server_hostname_inner_from_dict = SystemDnsGet200ResponseServerHostnameInner.from_dict(system_dns_get200_response_server_hostname_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


