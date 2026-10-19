# WirelessControllerHotspot20AnqpVenueNameNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of venue name duple. | [optional] 
**value_list** | [**List[WirelessControllerHotspot20AnqpVenueNameNameGet200ResponseValueListInner]**](WirelessControllerHotspot20AnqpVenueNameNameGet200ResponseValueListInner.md) | Name list. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_anqp_venue_name_name_get200_response import WirelessControllerHotspot20AnqpVenueNameNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20AnqpVenueNameNameGet200Response from a JSON string
wireless_controller_hotspot20_anqp_venue_name_name_get200_response_instance = WirelessControllerHotspot20AnqpVenueNameNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20AnqpVenueNameNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_hotspot20_anqp_venue_name_name_get200_response_dict = wireless_controller_hotspot20_anqp_venue_name_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerHotspot20AnqpVenueNameNameGet200Response from a dict
wireless_controller_hotspot20_anqp_venue_name_name_get200_response_from_dict = WirelessControllerHotspot20AnqpVenueNameNameGet200Response.from_dict(wireless_controller_hotspot20_anqp_venue_name_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


