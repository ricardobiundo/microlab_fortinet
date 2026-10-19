# SystemDnsServerNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | DNS server name. | [optional] 
**mode** | **str** | DNS server mode.    recursive:Shadow DNS database and forward.    non-recursive:Public DNS database only.    forward-only:Forward only.    resolver:Recursive resolver mode. | [optional] 
**dnsfilter_profile** | **str** | DNS filter profile. | [optional] 
**doh** | **str** | Enable/disable DNS over HTTPS/443 (default &#x3D; disable).    enable:Enable DNS over HTTPS.    disable:Disable DNS over HTTPS. | [optional] 
**doh3** | **str** | Enable/disable DNS over QUIC/HTTP3/443 (default &#x3D; disable).    enable:Enable DNS over HTTP3/QUIC.    disable:Disable DNS over HTTP3/QUIC. | [optional] 
**doq** | **str** | Enable/disable DNS over QUIC/853 (default &#x3D; disable).    enable:Enable DNS over QUIC.    disable:Disable DNS over QUIC. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dns_server_name_get200_response import SystemDnsServerNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDnsServerNameGet200Response from a JSON string
system_dns_server_name_get200_response_instance = SystemDnsServerNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemDnsServerNameGet200Response.to_json())

# convert the object into a dict
system_dns_server_name_get200_response_dict = system_dns_server_name_get200_response_instance.to_dict()
# create an instance of SystemDnsServerNameGet200Response from a dict
system_dns_server_name_get200_response_from_dict = SystemDnsServerNameGet200Response.from_dict(system_dns_server_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


