# SwitchControllerDynamicPortPolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Dynamic port policy name. | [optional] 
**description** | **str** | Description for the Dynamic port policy. | [optional] 
**fortilink** | **str** | FortiLink interface for which this Dynamic port policy belongs to. | [optional] 
**policy** | [**List[SwitchControllerDynamicPortPolicyNameGet200ResponsePolicyInner]**](SwitchControllerDynamicPortPolicyNameGet200ResponsePolicyInner.md) | Port policies with matching criteria and actions. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_dynamic_port_policy_name_get200_response import SwitchControllerDynamicPortPolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerDynamicPortPolicyNameGet200Response from a JSON string
switch_controller_dynamic_port_policy_name_get200_response_instance = SwitchControllerDynamicPortPolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerDynamicPortPolicyNameGet200Response.to_json())

# convert the object into a dict
switch_controller_dynamic_port_policy_name_get200_response_dict = switch_controller_dynamic_port_policy_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerDynamicPortPolicyNameGet200Response from a dict
switch_controller_dynamic_port_policy_name_get200_response_from_dict = SwitchControllerDynamicPortPolicyNameGet200Response.from_dict(switch_controller_dynamic_port_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


