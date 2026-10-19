# SystemGeoipOverrideNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Location name. | [optional] 
**description** | **str** | Description. | [optional] 
**country_id** | **str** | Two character Country ID code. | [optional] 
**ip_range** | [**List[SystemGeoipOverrideNameGet200ResponseIpRangeInner]**](SystemGeoipOverrideNameGet200ResponseIpRangeInner.md) | Table of IP ranges assigned to country. | [optional] 
**ip6_range** | [**List[SystemGeoipOverrideNameGet200ResponseIp6RangeInner]**](SystemGeoipOverrideNameGet200ResponseIp6RangeInner.md) | Table of IPv6 ranges assigned to country. | [optional] 

## Example

```python
from microlab_fortinet.models.system_geoip_override_name_get200_response import SystemGeoipOverrideNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemGeoipOverrideNameGet200Response from a JSON string
system_geoip_override_name_get200_response_instance = SystemGeoipOverrideNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemGeoipOverrideNameGet200Response.to_json())

# convert the object into a dict
system_geoip_override_name_get200_response_dict = system_geoip_override_name_get200_response_instance.to_dict()
# create an instance of SystemGeoipOverrideNameGet200Response from a dict
system_geoip_override_name_get200_response_from_dict = SystemGeoipOverrideNameGet200Response.from_dict(system_geoip_override_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


