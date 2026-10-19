# SystemProxyArpIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique integer ID of the entry. | [optional] 
**interface** | **str** | Interface acting proxy-ARP. | [optional] 
**ip** | **str** | IP address or start IP to be proxied. | [optional] 
**end_ip** | **str** | End IP of IP range to be proxied. | [optional] 

## Example

```python
from microlab_fortinet.models.system_proxy_arp_id_get200_response import SystemProxyArpIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemProxyArpIdGet200Response from a JSON string
system_proxy_arp_id_get200_response_instance = SystemProxyArpIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemProxyArpIdGet200Response.to_json())

# convert the object into a dict
system_proxy_arp_id_get200_response_dict = system_proxy_arp_id_get200_response_instance.to_dict()
# create an instance of SystemProxyArpIdGet200Response from a dict
system_proxy_arp_id_get200_response_from_dict = SystemProxyArpIdGet200Response.from_dict(system_proxy_arp_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


