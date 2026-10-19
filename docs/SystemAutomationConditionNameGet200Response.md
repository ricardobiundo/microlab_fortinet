# SystemAutomationConditionNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**description** | **str** | Description. | [optional] 
**condition_type** | **str** | Condition type.    cpu:CPU usage condition,    memory:Memory usage condition,    vpn:VPN state condition. | [optional] 
**cpu_usage_percent** | **int** | CPU usage reaches specified percentage. | [optional] 
**mem_usage_percent** | **int** | Memory usage reaches specified percentage. | [optional] 
**vdom** | **str** | Virtual domain which the tunnel belongs to. | [optional] 
**vpn_tunnel_name** | **str** | VPN tunnel name. | [optional] 
**vpn_tunnel_state** | **str** | VPN tunnel state.    tunnel-up:VPN tunnel is up.    tunnel-down:VPN tunnel is down. | [optional] 

## Example

```python
from microlab_fortinet.models.system_automation_condition_name_get200_response import SystemAutomationConditionNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAutomationConditionNameGet200Response from a JSON string
system_automation_condition_name_get200_response_instance = SystemAutomationConditionNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAutomationConditionNameGet200Response.to_json())

# convert the object into a dict
system_automation_condition_name_get200_response_dict = system_automation_condition_name_get200_response_instance.to_dict()
# create an instance of SystemAutomationConditionNameGet200Response from a dict
system_automation_condition_name_get200_response_from_dict = SystemAutomationConditionNameGet200Response.from_dict(system_automation_condition_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


