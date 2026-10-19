# SystemZoneNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Zone name. | [optional] 
**tagging** | [**List[SystemInterfaceNameGet200ResponseTaggingInner]**](SystemInterfaceNameGet200ResponseTaggingInner.md) | Config object tagging. | [optional] 
**description** | **str** | Description. | [optional] 
**intrazone** | **str** | Allow or deny traffic routing between different interfaces in the same zone (default &#x3D; deny).    allow:Allow traffic between interfaces in the zone.    deny:Deny traffic between interfaces in the zone. | [optional] 
**interface** | [**List[SystemZoneNameGet200ResponseInterfaceInner]**](SystemZoneNameGet200ResponseInterfaceInner.md) | Add interfaces to this zone. Interfaces must not be assigned to another zone or have firewall policies defined. | [optional] 

## Example

```python
from microlab_fortinet.models.system_zone_name_get200_response import SystemZoneNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemZoneNameGet200Response from a JSON string
system_zone_name_get200_response_instance = SystemZoneNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemZoneNameGet200Response.to_json())

# convert the object into a dict
system_zone_name_get200_response_dict = system_zone_name_get200_response_instance.to_dict()
# create an instance of SystemZoneNameGet200Response from a dict
system_zone_name_get200_response_from_dict = SystemZoneNameGet200Response.from_dict(system_zone_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


