# SwitchControllerFlowTrackingGet200ResponseAggregatesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Aggregate id. | [optional] 
**ip** | **str** | IP address to group all matching traffic sessions to a flow. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_flow_tracking_get200_response_aggregates_inner import SwitchControllerFlowTrackingGet200ResponseAggregatesInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerFlowTrackingGet200ResponseAggregatesInner from a JSON string
switch_controller_flow_tracking_get200_response_aggregates_inner_instance = SwitchControllerFlowTrackingGet200ResponseAggregatesInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerFlowTrackingGet200ResponseAggregatesInner.to_json())

# convert the object into a dict
switch_controller_flow_tracking_get200_response_aggregates_inner_dict = switch_controller_flow_tracking_get200_response_aggregates_inner_instance.to_dict()
# create an instance of SwitchControllerFlowTrackingGet200ResponseAggregatesInner from a dict
switch_controller_flow_tracking_get200_response_aggregates_inner_from_dict = SwitchControllerFlowTrackingGet200ResponseAggregatesInner.from_dict(switch_controller_flow_tracking_get200_response_aggregates_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


