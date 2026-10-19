# SwitchControllerQosQosPolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | QoS policy name. | [optional] 
**default_cos** | **int** | Default cos queue for untagged packets. | [optional] 
**trust_dot1p_map** | **str** | QoS trust 802.1p map. | [optional] 
**trust_ip_dscp_map** | **str** | QoS trust ip dscp map. | [optional] 
**queue_policy** | **str** | QoS egress queue policy. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_qos_qos_policy_name_get200_response import SwitchControllerQosQosPolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerQosQosPolicyNameGet200Response from a JSON string
switch_controller_qos_qos_policy_name_get200_response_instance = SwitchControllerQosQosPolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerQosQosPolicyNameGet200Response.to_json())

# convert the object into a dict
switch_controller_qos_qos_policy_name_get200_response_dict = switch_controller_qos_qos_policy_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerQosQosPolicyNameGet200Response from a dict
switch_controller_qos_qos_policy_name_get200_response_from_dict = SwitchControllerQosQosPolicyNameGet200Response.from_dict(switch_controller_qos_qos_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


