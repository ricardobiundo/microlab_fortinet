# SystemGeoipOverrideNameGet200ResponseIp6RangeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID of individual entry in the IPv6 range table. | [optional] 
**start_ip** | **str** | Starting IP address, inclusive, of the address range (format: xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx). | [optional] 
**end_ip** | **str** | Ending IP address, inclusive, of the address range (format: xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx). | [optional] 

## Example

```python
from microlab_fortinet.models.system_geoip_override_name_get200_response_ip6_range_inner import SystemGeoipOverrideNameGet200ResponseIp6RangeInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemGeoipOverrideNameGet200ResponseIp6RangeInner from a JSON string
system_geoip_override_name_get200_response_ip6_range_inner_instance = SystemGeoipOverrideNameGet200ResponseIp6RangeInner.from_json(json)
# print the JSON string representation of the object
print(SystemGeoipOverrideNameGet200ResponseIp6RangeInner.to_json())

# convert the object into a dict
system_geoip_override_name_get200_response_ip6_range_inner_dict = system_geoip_override_name_get200_response_ip6_range_inner_instance.to_dict()
# create an instance of SystemGeoipOverrideNameGet200ResponseIp6RangeInner from a dict
system_geoip_override_name_get200_response_ip6_range_inner_from_dict = SystemGeoipOverrideNameGet200ResponseIp6RangeInner.from_dict(system_geoip_override_name_get200_response_ip6_range_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


