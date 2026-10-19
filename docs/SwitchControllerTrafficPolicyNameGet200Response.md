# SwitchControllerTrafficPolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Traffic policy name. | [optional] 
**description** | **str** | Description of the traffic policy. | [optional] 
**policer_status** | **str** | Enable/disable policer config on the traffic policy.    enable:Enable policer config on the traffic policy.    disable:Disable policer config on the traffic policy. | [optional] 
**guaranteed_bandwidth** | **int** | Guaranteed bandwidth in kbps (max value &#x3D; 524287000). | [optional] 
**guaranteed_burst** | **int** | Guaranteed burst size in bytes (max value &#x3D; 4294967295). | [optional] 
**maximum_burst** | **int** | Maximum burst size in bytes (max value &#x3D; 4294967295). | [optional] 
**type** | **str** | Configure type of policy(ingress/egress).    ingress:Ingress policy.    egress:Egress policy. | [optional] 
**cos_queue** | **int** | COS queue(0 - 7), or unset to disable. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_traffic_policy_name_get200_response import SwitchControllerTrafficPolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerTrafficPolicyNameGet200Response from a JSON string
switch_controller_traffic_policy_name_get200_response_instance = SwitchControllerTrafficPolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerTrafficPolicyNameGet200Response.to_json())

# convert the object into a dict
switch_controller_traffic_policy_name_get200_response_dict = switch_controller_traffic_policy_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerTrafficPolicyNameGet200Response from a dict
switch_controller_traffic_policy_name_get200_response_from_dict = SwitchControllerTrafficPolicyNameGet200Response.from_dict(switch_controller_traffic_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


