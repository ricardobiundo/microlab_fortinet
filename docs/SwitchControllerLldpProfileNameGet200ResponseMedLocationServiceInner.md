# SwitchControllerLldpProfileNameGet200ResponseMedLocationServiceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Location service type name. | [optional] 
**status** | **str** | Enable or disable this TLV.    disable:Do not transmit this location service TLV.    enable:Transmit this location service TLV. | [optional] 
**sys_location_id** | **str** | Location service ID. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_lldp_profile_name_get200_response_med_location_service_inner import SwitchControllerLldpProfileNameGet200ResponseMedLocationServiceInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerLldpProfileNameGet200ResponseMedLocationServiceInner from a JSON string
switch_controller_lldp_profile_name_get200_response_med_location_service_inner_instance = SwitchControllerLldpProfileNameGet200ResponseMedLocationServiceInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerLldpProfileNameGet200ResponseMedLocationServiceInner.to_json())

# convert the object into a dict
switch_controller_lldp_profile_name_get200_response_med_location_service_inner_dict = switch_controller_lldp_profile_name_get200_response_med_location_service_inner_instance.to_dict()
# create an instance of SwitchControllerLldpProfileNameGet200ResponseMedLocationServiceInner from a dict
switch_controller_lldp_profile_name_get200_response_med_location_service_inner_from_dict = SwitchControllerLldpProfileNameGet200ResponseMedLocationServiceInner.from_dict(switch_controller_lldp_profile_name_get200_response_med_location_service_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


