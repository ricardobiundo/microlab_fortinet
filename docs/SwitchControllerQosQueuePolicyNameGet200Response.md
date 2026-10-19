# SwitchControllerQosQueuePolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | QoS policy name. | [optional] 
**schedule** | **str** | COS queue scheduling.    strict:Strict scheduling (queue7: highest priority, queue0: lowest priority).    round-robin:Round robin scheduling.    weighted:Weighted round robin scheduling. | [optional] 
**rate_by** | **str** | COS queue rate by kbps or percent.    kbps:Rate by kbps.    percent:Rate by percent. | [optional] 
**cos_queue** | [**List[SwitchControllerQosQueuePolicyNameGet200ResponseCosQueueInner]**](SwitchControllerQosQueuePolicyNameGet200ResponseCosQueueInner.md) | COS queue configuration. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_qos_queue_policy_name_get200_response import SwitchControllerQosQueuePolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerQosQueuePolicyNameGet200Response from a JSON string
switch_controller_qos_queue_policy_name_get200_response_instance = SwitchControllerQosQueuePolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerQosQueuePolicyNameGet200Response.to_json())

# convert the object into a dict
switch_controller_qos_queue_policy_name_get200_response_dict = switch_controller_qos_queue_policy_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerQosQueuePolicyNameGet200Response from a dict
switch_controller_qos_queue_policy_name_get200_response_from_dict = SwitchControllerQosQueuePolicyNameGet200Response.from_dict(switch_controller_qos_queue_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


