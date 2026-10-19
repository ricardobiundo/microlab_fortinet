# SwitchControllerLocationNameGet200ResponseCoordinatesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**altitude** | **str** | Plus or minus floating point number. For example, 117.47. | [optional] 
**altitude_unit** | **str** | Configure the unit for which the altitude is to (m &#x3D; meters, f &#x3D; floors of a building).    m:set altitude unit meters    f:set altitude unit floors | [optional] 
**datum** | **str** | WGS84, NAD83, NAD83/MLLW.    WGS84:set coordinates datum WGS84    NAD83:set coordinates datum NAD83    NAD83/MLLW:set coordinates datum NAD83/MLLW | [optional] 
**latitude** | **str** | Floating point starting with +/- or ending with (N or S). For example, +/-16.67 or 16.67N. | [optional] 
**longitude** | **str** | Floating point starting with +/- or ending with (N or S). For example, +/-26.789 or 26.789E. | [optional] 
**parent_key** | **str** | Parent key name. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_location_name_get200_response_coordinates_inner import SwitchControllerLocationNameGet200ResponseCoordinatesInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerLocationNameGet200ResponseCoordinatesInner from a JSON string
switch_controller_location_name_get200_response_coordinates_inner_instance = SwitchControllerLocationNameGet200ResponseCoordinatesInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerLocationNameGet200ResponseCoordinatesInner.to_json())

# convert the object into a dict
switch_controller_location_name_get200_response_coordinates_inner_dict = switch_controller_location_name_get200_response_coordinates_inner_instance.to_dict()
# create an instance of SwitchControllerLocationNameGet200ResponseCoordinatesInner from a dict
switch_controller_location_name_get200_response_coordinates_inner_from_dict = SwitchControllerLocationNameGet200ResponseCoordinatesInner.from_dict(switch_controller_location_name_get200_response_coordinates_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


