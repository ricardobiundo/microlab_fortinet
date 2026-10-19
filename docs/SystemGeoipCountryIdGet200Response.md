# SystemGeoipCountryIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Country ID. | [optional] 
**name** | **str** | Country name. | [optional] 

## Example

```python
from microlab_fortinet.models.system_geoip_country_id_get200_response import SystemGeoipCountryIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemGeoipCountryIdGet200Response from a JSON string
system_geoip_country_id_get200_response_instance = SystemGeoipCountryIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemGeoipCountryIdGet200Response.to_json())

# convert the object into a dict
system_geoip_country_id_get200_response_dict = system_geoip_country_id_get200_response_instance.to_dict()
# create an instance of SystemGeoipCountryIdGet200Response from a dict
system_geoip_country_id_get200_response_from_dict = SystemGeoipCountryIdGet200Response.from_dict(system_geoip_country_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


