# SystemZoneNameGet200ResponseInterfaceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**interface_name** | **str** | Select interfaces to add to the zone. | [optional] 

## Example

```python
from microlab_fortinet.models.system_zone_name_get200_response_interface_inner import SystemZoneNameGet200ResponseInterfaceInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemZoneNameGet200ResponseInterfaceInner from a JSON string
system_zone_name_get200_response_interface_inner_instance = SystemZoneNameGet200ResponseInterfaceInner.from_json(json)
# print the JSON string representation of the object
print(SystemZoneNameGet200ResponseInterfaceInner.to_json())

# convert the object into a dict
system_zone_name_get200_response_interface_inner_dict = system_zone_name_get200_response_interface_inner_instance.to_dict()
# create an instance of SystemZoneNameGet200ResponseInterfaceInner from a dict
system_zone_name_get200_response_interface_inner_from_dict = SystemZoneNameGet200ResponseInterfaceInner.from_dict(system_zone_name_get200_response_interface_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


