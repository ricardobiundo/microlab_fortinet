# WirelessControllerHotspot20QosMapNameGet200ResponseDscpRangeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**index** | **int** | DSCP range index. | [optional] 
**up** | **int** | User priority. | [optional] 
**low** | **int** | DSCP low value. | [optional] 
**high** | **int** | DSCP high value. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_qos_map_name_get200_response_dscp_range_inner import WirelessControllerHotspot20QosMapNameGet200ResponseDscpRangeInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20QosMapNameGet200ResponseDscpRangeInner from a JSON string
wireless_controller_hotspot20_qos_map_name_get200_response_dscp_range_inner_instance = WirelessControllerHotspot20QosMapNameGet200ResponseDscpRangeInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20QosMapNameGet200ResponseDscpRangeInner.to_json())

# convert the object into a dict
wireless_controller_hotspot20_qos_map_name_get200_response_dscp_range_inner_dict = wireless_controller_hotspot20_qos_map_name_get200_response_dscp_range_inner_instance.to_dict()
# create an instance of WirelessControllerHotspot20QosMapNameGet200ResponseDscpRangeInner from a dict
wireless_controller_hotspot20_qos_map_name_get200_response_dscp_range_inner_from_dict = WirelessControllerHotspot20QosMapNameGet200ResponseDscpRangeInner.from_dict(wireless_controller_hotspot20_qos_map_name_get200_response_dscp_range_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


