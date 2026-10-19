# SwitchControllerAutoConfigPolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Auto-config policy name. | [optional] 
**qos_policy** | **str** | Auto-Config QoS policy. | [optional] 
**storm_control_policy** | **str** | Auto-Config storm control policy. | [optional] 
**poe_status** | **str** | Enable/disable PoE status.    enable:Enable PoE status.    disable:Disable PoE status. | [optional] 
**igmp_flood_report** | **str** | Enable/disable IGMP flood report.    enable:Enable IGMP flood report.    disable:Disable IGMP flood report. | [optional] 
**igmp_flood_traffic** | **str** | Enable/disable IGMP flood traffic.    enable:Enable IGMP flood traffic.    disable:Disable IGMP flood traffic. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_auto_config_policy_name_get200_response import SwitchControllerAutoConfigPolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerAutoConfigPolicyNameGet200Response from a JSON string
switch_controller_auto_config_policy_name_get200_response_instance = SwitchControllerAutoConfigPolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerAutoConfigPolicyNameGet200Response.to_json())

# convert the object into a dict
switch_controller_auto_config_policy_name_get200_response_dict = switch_controller_auto_config_policy_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerAutoConfigPolicyNameGet200Response from a dict
switch_controller_auto_config_policy_name_get200_response_from_dict = SwitchControllerAutoConfigPolicyNameGet200Response.from_dict(switch_controller_auto_config_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


