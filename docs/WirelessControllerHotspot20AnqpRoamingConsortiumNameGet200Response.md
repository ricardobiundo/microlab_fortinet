# WirelessControllerHotspot20AnqpRoamingConsortiumNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Roaming consortium name. | [optional] 
**oi_list** | [**List[WirelessControllerHotspot20AnqpRoamingConsortiumNameGet200ResponseOiListInner]**](WirelessControllerHotspot20AnqpRoamingConsortiumNameGet200ResponseOiListInner.md) | Organization identifier list. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_anqp_roaming_consortium_name_get200_response import WirelessControllerHotspot20AnqpRoamingConsortiumNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20AnqpRoamingConsortiumNameGet200Response from a JSON string
wireless_controller_hotspot20_anqp_roaming_consortium_name_get200_response_instance = WirelessControllerHotspot20AnqpRoamingConsortiumNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20AnqpRoamingConsortiumNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_hotspot20_anqp_roaming_consortium_name_get200_response_dict = wireless_controller_hotspot20_anqp_roaming_consortium_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerHotspot20AnqpRoamingConsortiumNameGet200Response from a dict
wireless_controller_hotspot20_anqp_roaming_consortium_name_get200_response_from_dict = WirelessControllerHotspot20AnqpRoamingConsortiumNameGet200Response.from_dict(wireless_controller_hotspot20_anqp_roaming_consortium_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


