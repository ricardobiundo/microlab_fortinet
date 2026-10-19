# SystemIpv6NeighborCacheIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique integer ID of the entry. | [optional] 
**interface** | **str** | Select the associated interface name from available options. | [optional] 
**ipv6** | **str** | IPv6 address (format: xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx). | [optional] 
**mac** | **str** | MAC address (format: xx:xx:xx:xx:xx:xx). | [optional] 

## Example

```python
from microlab_fortinet.models.system_ipv6_neighbor_cache_id_get200_response import SystemIpv6NeighborCacheIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIpv6NeighborCacheIdGet200Response from a JSON string
system_ipv6_neighbor_cache_id_get200_response_instance = SystemIpv6NeighborCacheIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemIpv6NeighborCacheIdGet200Response.to_json())

# convert the object into a dict
system_ipv6_neighbor_cache_id_get200_response_dict = system_ipv6_neighbor_cache_id_get200_response_instance.to_dict()
# create an instance of SystemIpv6NeighborCacheIdGet200Response from a dict
system_ipv6_neighbor_cache_id_get200_response_from_dict = SystemIpv6NeighborCacheIdGet200Response.from_dict(system_ipv6_neighbor_cache_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


