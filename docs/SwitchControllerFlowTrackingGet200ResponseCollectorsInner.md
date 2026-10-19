# SwitchControllerFlowTrackingGet200ResponseCollectorsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Collector name. | [optional] 
**ip** | **str** | Collector IP address. | [optional] 
**port** | **int** | Collector port number(0-65535, default:0, netflow:2055, ipfix:4739). | [optional] 
**transport** | **str** | Collector L4 transport protocol for exporting packets.    udp:UDP protocol.    tcp:TCP protocol.    sctp:SCTP protocol. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_flow_tracking_get200_response_collectors_inner import SwitchControllerFlowTrackingGet200ResponseCollectorsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerFlowTrackingGet200ResponseCollectorsInner from a JSON string
switch_controller_flow_tracking_get200_response_collectors_inner_instance = SwitchControllerFlowTrackingGet200ResponseCollectorsInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerFlowTrackingGet200ResponseCollectorsInner.to_json())

# convert the object into a dict
switch_controller_flow_tracking_get200_response_collectors_inner_dict = switch_controller_flow_tracking_get200_response_collectors_inner_instance.to_dict()
# create an instance of SwitchControllerFlowTrackingGet200ResponseCollectorsInner from a dict
switch_controller_flow_tracking_get200_response_collectors_inner_from_dict = SwitchControllerFlowTrackingGet200ResponseCollectorsInner.from_dict(switch_controller_flow_tracking_get200_response_collectors_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


