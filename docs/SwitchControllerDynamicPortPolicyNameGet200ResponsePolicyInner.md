# SwitchControllerDynamicPortPolicyNameGet200ResponsePolicyInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Policy name. | [optional] 
**description** | **str** | Description for the policy. | [optional] 
**status** | **str** | Enable/disable policy.    enable:Enable policy.    disable:Disable policy. | [optional] 
**category** | **str** | Category of Dynamic port policy.    device:Device category.    interface-tag:Interface Tag category. | [optional] 
**match_type** | **str** | Match and retain the devices based on the type.    dynamic:Matched devices will be removed on dynamic events like link-down,device-inactivity,switch-offline.    override:Matched devices will be retained until the match-period. | [optional] 
**match_period** | **int** | Number of days the matched devices will be retained (0 - 120, 0 &#x3D; always retain). | [optional] 
**match_remove** | **str** | Options to remove the matched override devices.    default:Remove the matched override devices based on the match period.    link-down:Remove the matched override devices based on switch port link down event. | [optional] 
**interface_tags** | [**List[SwitchControllerDynamicPortPolicyNameGet200ResponsePolicyInnerInterfaceTagsInner]**](SwitchControllerDynamicPortPolicyNameGet200ResponsePolicyInnerInterfaceTagsInner.md) | Match policy based on the FortiSwitch interface object tags. | [optional] 
**mac** | **str** | Match policy based on MAC address. | [optional] 
**hw_vendor** | **str** | Match policy based on hardware vendor. | [optional] 
**type** | **str** | Match policy based on type. | [optional] 
**family** | **str** | Match policy based on family. | [optional] 
**host** | **str** | Match policy based on host. | [optional] 
**lldp_profile** | **str** | LLDP profile to be applied when using this policy. | [optional] 
**qos_policy** | **str** | QoS policy to be applied when using this policy. | [optional] 
**var_802_1x** | **str** | 802.1x security policy to be applied when using this policy. | [optional] 
**vlan_policy** | **str** | VLAN policy to be applied when using this policy. | [optional] 
**bounce_port_link** | **str** | Enable/disable bouncing (administratively bring the link down, up) of a switch port where this policy is applied. Helps to clear and reassign VLAN from lldp-profile.    disable:Disable bouncing (administratively bring the link down, up) of a switch port where this policy is applied.    enable:Enable bouncing (administratively bring the link down, up) of a switch port where this policy is applied. | [optional] 
**bounce_port_duration** | **int** | Bounce duration in seconds of a switch port where this policy is applied. | [optional] 
**poe_reset** | **str** | Enable/disable POE reset of a switch port where this policy is applied.    disable:Disable POE reset of a switch port where this policy is applied.    enable:Enable POE reset of a switch port where this policy is applied. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_dynamic_port_policy_name_get200_response_policy_inner import SwitchControllerDynamicPortPolicyNameGet200ResponsePolicyInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerDynamicPortPolicyNameGet200ResponsePolicyInner from a JSON string
switch_controller_dynamic_port_policy_name_get200_response_policy_inner_instance = SwitchControllerDynamicPortPolicyNameGet200ResponsePolicyInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerDynamicPortPolicyNameGet200ResponsePolicyInner.to_json())

# convert the object into a dict
switch_controller_dynamic_port_policy_name_get200_response_policy_inner_dict = switch_controller_dynamic_port_policy_name_get200_response_policy_inner_instance.to_dict()
# create an instance of SwitchControllerDynamicPortPolicyNameGet200ResponsePolicyInner from a dict
switch_controller_dynamic_port_policy_name_get200_response_policy_inner_from_dict = SwitchControllerDynamicPortPolicyNameGet200ResponsePolicyInner.from_dict(switch_controller_dynamic_port_policy_name_get200_response_policy_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


