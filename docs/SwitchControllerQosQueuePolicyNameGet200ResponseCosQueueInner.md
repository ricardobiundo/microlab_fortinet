# SwitchControllerQosQueuePolicyNameGet200ResponseCosQueueInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Cos queue ID. | [optional] 
**description** | **str** | Description of the COS queue. | [optional] 
**min_rate** | **int** | Minimum rate (0 - 4294967295 kbps, 0 to disable). | [optional] 
**max_rate** | **int** | Maximum rate (0 - 4294967295 kbps, 0 to disable). | [optional] 
**min_rate_percent** | **int** | Minimum rate (% of link speed). | [optional] 
**max_rate_percent** | **int** | Maximum rate (% of link speed). | [optional] 
**drop_policy** | **str** | COS queue drop policy.    taildrop:Taildrop policy.    weighted-random-early-detection:Weighted random early detection drop policy. | [optional] 
**ecn** | **str** | Enable/disable ECN packet marking to drop eligible packets.    disable:Disable ECN packet marking to drop eligible packets.    enable:Enable ECN packet marking to drop eligible packets. | [optional] 
**weight** | **int** | Weight of weighted round robin scheduling. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_qos_queue_policy_name_get200_response_cos_queue_inner import SwitchControllerQosQueuePolicyNameGet200ResponseCosQueueInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerQosQueuePolicyNameGet200ResponseCosQueueInner from a JSON string
switch_controller_qos_queue_policy_name_get200_response_cos_queue_inner_instance = SwitchControllerQosQueuePolicyNameGet200ResponseCosQueueInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerQosQueuePolicyNameGet200ResponseCosQueueInner.to_json())

# convert the object into a dict
switch_controller_qos_queue_policy_name_get200_response_cos_queue_inner_dict = switch_controller_qos_queue_policy_name_get200_response_cos_queue_inner_instance.to_dict()
# create an instance of SwitchControllerQosQueuePolicyNameGet200ResponseCosQueueInner from a dict
switch_controller_qos_queue_policy_name_get200_response_cos_queue_inner_from_dict = SwitchControllerQosQueuePolicyNameGet200ResponseCosQueueInner.from_dict(switch_controller_qos_queue_policy_name_get200_response_cos_queue_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


