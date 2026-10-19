# SystemDnsGet200ResponseDomainInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**domain** | **str** | DNS search domain list separated by space (maximum 8 domains). | [optional] 

## Example

```python
from microlab_fortinet.models.system_dns_get200_response_domain_inner import SystemDnsGet200ResponseDomainInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDnsGet200ResponseDomainInner from a JSON string
system_dns_get200_response_domain_inner_instance = SystemDnsGet200ResponseDomainInner.from_json(json)
# print the JSON string representation of the object
print(SystemDnsGet200ResponseDomainInner.to_json())

# convert the object into a dict
system_dns_get200_response_domain_inner_dict = system_dns_get200_response_domain_inner_instance.to_dict()
# create an instance of SystemDnsGet200ResponseDomainInner from a dict
system_dns_get200_response_domain_inner_from_dict = SystemDnsGet200ResponseDomainInner.from_dict(system_dns_get200_response_domain_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


