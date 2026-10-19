# SwitchControllerStormControlPolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Storm control policy name. | [optional] 
**description** | **str** | Description of the storm control policy. | [optional] 
**storm_control_mode** | **str** | Set Storm control mode.    global:Apply Global or switch level storm control configuration.    override:Override global and switch level storm control to use port level configuration.    disabled:Disable storm control on the port entirely overriding global and switch level storm control. | [optional] 
**rate** | **int** | Threshold rate in packets per second at which storm traffic is controlled in override mode (default&#x3D;500, 0 to drop all). | [optional] 
**burst_size_level** | **int** | Increase level to handle bursty traffic (0 - 4, default &#x3D; 0). | [optional] 
**unknown_unicast** | **str** | Enable/disable storm control to drop/allow unknown unicast traffic in override mode.    enable:Enable storm control for unknown unicast traffic to drop packets which exceed configured rate limits.    disable:Disable storm control for unknown unicast traffic to allow all packets. | [optional] 
**unknown_multicast** | **str** | Enable/disable storm control to drop/allow unknown multicast traffic in override mode.    enable:Enable storm control for unknown multicast traffic to drop packets which exceed configured rate limits.    disable:Disable storm control for unknown multicast traffic to allow all packets. | [optional] 
**broadcast** | **str** | Enable/disable storm control to drop/allow broadcast traffic in override mode.    enable:Enable storm control for broadcast traffic to drop packets which exceed configured rate limits.    disable:Disable storm control for broadcast traffic to allow all packets. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_storm_control_policy_name_get200_response import SwitchControllerStormControlPolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerStormControlPolicyNameGet200Response from a JSON string
switch_controller_storm_control_policy_name_get200_response_instance = SwitchControllerStormControlPolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerStormControlPolicyNameGet200Response.to_json())

# convert the object into a dict
switch_controller_storm_control_policy_name_get200_response_dict = switch_controller_storm_control_policy_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerStormControlPolicyNameGet200Response from a dict
switch_controller_storm_control_policy_name_get200_response_from_dict = SwitchControllerStormControlPolicyNameGet200Response.from_dict(switch_controller_storm_control_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


