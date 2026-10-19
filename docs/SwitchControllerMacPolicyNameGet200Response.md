# SwitchControllerMacPolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | MAC policy name. | [optional] 
**description** | **str** | Description for the MAC policy. | [optional] 
**fortilink** | **str** | FortiLink interface for which this MAC policy belongs to. | [optional] 
**vlan** | **str** | Ingress traffic VLAN assignment for the MAC address matching this MAC policy. | [optional] 
**traffic_policy** | **str** | Traffic policy to be applied when using this MAC policy. | [optional] 
**count** | **str** | Enable/disable packet count on the NAC device.    disable:Enable packet count on the NAC device.    enable:Disable packet count on the NAC device. | [optional] 
**bounce_port_link** | **str** | Enable/disable bouncing (administratively bring the link down, up) of a switch port where this mac-policy is applied.    disable:Disable bouncing (administratively bring the link down, up) of a switch port where this mac-policy is applied.    enable:Enable bouncing (administratively bring the link down, up) of a switch port where this mac-policy is applied. | [optional] 
**bounce_port_duration** | **int** | Bounce duration in seconds of a switch port where this mac-policy is applied. | [optional] 
**poe_reset** | **str** | Enable/disable POE reset of a switch port where this mac-policy is applied.    disable:Disable POE reset of a switch port where this mac-policy is applied.    enable:Enable POE reset of a switch port where this mac-policy is applied. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_mac_policy_name_get200_response import SwitchControllerMacPolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerMacPolicyNameGet200Response from a JSON string
switch_controller_mac_policy_name_get200_response_instance = SwitchControllerMacPolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerMacPolicyNameGet200Response.to_json())

# convert the object into a dict
switch_controller_mac_policy_name_get200_response_dict = switch_controller_mac_policy_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerMacPolicyNameGet200Response from a dict
switch_controller_mac_policy_name_get200_response_from_dict = SwitchControllerMacPolicyNameGet200Response.from_dict(switch_controller_mac_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


