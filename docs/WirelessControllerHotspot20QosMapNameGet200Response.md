# WirelessControllerHotspot20QosMapNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | QOS-MAP name. | [optional] 
**dscp_except** | [**List[WirelessControllerHotspot20QosMapNameGet200ResponseDscpExceptInner]**](WirelessControllerHotspot20QosMapNameGet200ResponseDscpExceptInner.md) | Differentiated Services Code Point (DSCP) exceptions. | [optional] 
**dscp_range** | [**List[WirelessControllerHotspot20QosMapNameGet200ResponseDscpRangeInner]**](WirelessControllerHotspot20QosMapNameGet200ResponseDscpRangeInner.md) | Differentiated Services Code Point (DSCP) ranges. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_qos_map_name_get200_response import WirelessControllerHotspot20QosMapNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20QosMapNameGet200Response from a JSON string
wireless_controller_hotspot20_qos_map_name_get200_response_instance = WirelessControllerHotspot20QosMapNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20QosMapNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_hotspot20_qos_map_name_get200_response_dict = wireless_controller_hotspot20_qos_map_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerHotspot20QosMapNameGet200Response from a dict
wireless_controller_hotspot20_qos_map_name_get200_response_from_dict = WirelessControllerHotspot20QosMapNameGet200Response.from_dict(wireless_controller_hotspot20_qos_map_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


