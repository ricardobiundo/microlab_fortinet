# SwitchControllerLocationNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Unique location item name. | [optional] 
**address_civic** | [**List[SwitchControllerLocationNameGet200ResponseAddressCivicInner]**](SwitchControllerLocationNameGet200ResponseAddressCivicInner.md) | Configure location civic address. | [optional] 
**coordinates** | [**List[SwitchControllerLocationNameGet200ResponseCoordinatesInner]**](SwitchControllerLocationNameGet200ResponseCoordinatesInner.md) | Configure location GPS coordinates. | [optional] 
**elin_number** | [**List[SwitchControllerLocationNameGet200ResponseElinNumberInner]**](SwitchControllerLocationNameGet200ResponseElinNumberInner.md) | Configure location ELIN number. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_location_name_get200_response import SwitchControllerLocationNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerLocationNameGet200Response from a JSON string
switch_controller_location_name_get200_response_instance = SwitchControllerLocationNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerLocationNameGet200Response.to_json())

# convert the object into a dict
switch_controller_location_name_get200_response_dict = switch_controller_location_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerLocationNameGet200Response from a dict
switch_controller_location_name_get200_response_from_dict = SwitchControllerLocationNameGet200Response.from_dict(switch_controller_location_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


