# WirelessControllerHotspot20H2qpWanMetricNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | WAN metric name. | [optional] 
**link_status** | **str** | Link status.    up:Link up.    down:Link down.    in-test:Link in test state. | [optional] 
**symmetric_wan_link** | **str** | WAN link symmetry.    symmetric:Symmetric WAN link (uplink and downlink speeds are the same).    asymmetric:Asymmetric WAN link (uplink and downlink speeds are not the same). | [optional] 
**link_at_capacity** | **str** | Link at capacity.    enable:Link at capacity (not allow additional mobile devices to associate).    disable:Link not at capacity (allow additional mobile devices to associate). | [optional] 
**uplink_speed** | **int** | Uplink speed (in kilobits/s). | [optional] 
**downlink_speed** | **int** | Downlink speed (in kilobits/s). | [optional] 
**uplink_load** | **int** | Uplink load. | [optional] 
**downlink_load** | **int** | Downlink load. | [optional] 
**load_measurement_duration** | **int** | Load measurement duration (in tenths of a second). | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_h2qp_wan_metric_name_get200_response import WirelessControllerHotspot20H2qpWanMetricNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20H2qpWanMetricNameGet200Response from a JSON string
wireless_controller_hotspot20_h2qp_wan_metric_name_get200_response_instance = WirelessControllerHotspot20H2qpWanMetricNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20H2qpWanMetricNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_hotspot20_h2qp_wan_metric_name_get200_response_dict = wireless_controller_hotspot20_h2qp_wan_metric_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerHotspot20H2qpWanMetricNameGet200Response from a dict
wireless_controller_hotspot20_h2qp_wan_metric_name_get200_response_from_dict = WirelessControllerHotspot20H2qpWanMetricNameGet200Response.from_dict(wireless_controller_hotspot20_h2qp_wan_metric_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


