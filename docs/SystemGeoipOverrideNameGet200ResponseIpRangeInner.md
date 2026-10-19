# SystemGeoipOverrideNameGet200ResponseIpRangeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID of individual entry in the IP range table. | [optional] 
**start_ip** | **str** | Starting IP address, inclusive, of the address range (format: xxx.xxx.xxx.xxx). | [optional] 
**end_ip** | **str** | Ending IP address, inclusive, of the address range (format: xxx.xxx.xxx.xxx). | [optional] 

## Example

```python
from microlab_fortinet.models.system_geoip_override_name_get200_response_ip_range_inner import SystemGeoipOverrideNameGet200ResponseIpRangeInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemGeoipOverrideNameGet200ResponseIpRangeInner from a JSON string
system_geoip_override_name_get200_response_ip_range_inner_instance = SystemGeoipOverrideNameGet200ResponseIpRangeInner.from_json(json)
# print the JSON string representation of the object
print(SystemGeoipOverrideNameGet200ResponseIpRangeInner.to_json())

# convert the object into a dict
system_geoip_override_name_get200_response_ip_range_inner_dict = system_geoip_override_name_get200_response_ip_range_inner_instance.to_dict()
# create an instance of SystemGeoipOverrideNameGet200ResponseIpRangeInner from a dict
system_geoip_override_name_get200_response_ip_range_inner_from_dict = SystemGeoipOverrideNameGet200ResponseIpRangeInner.from_dict(system_geoip_override_name_get200_response_ip_range_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


