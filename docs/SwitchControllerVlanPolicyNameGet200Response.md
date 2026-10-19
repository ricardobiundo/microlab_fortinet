# SwitchControllerVlanPolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | VLAN policy name. | [optional] 
**description** | **str** | Description for the VLAN policy. | [optional] 
**fortilink** | **str** | FortiLink interface for which this VLAN policy belongs to. | [optional] 
**vlan** | **str** | Native VLAN to be applied when using this VLAN policy. | [optional] 
**allowed_vlans** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerAllowedVlansInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerAllowedVlansInner.md) | Allowed VLANs to be applied when using this VLAN policy. | [optional] 
**untagged_vlans** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerAllowedVlansInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerAllowedVlansInner.md) | Untagged VLANs to be applied when using this VLAN policy. | [optional] 
**allowed_vlans_all** | **str** | Enable/disable all defined VLANs when using this VLAN policy.    enable:Enable all defined VLANs.    disable:Disable all defined VLANs. | [optional] 
**discard_mode** | **str** | Discard mode to be applied when using this VLAN policy.    none:Discard disabled.    all-untagged:Discard all frames that are untagged.    all-tagged:Discard all frames that are tagged. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_vlan_policy_name_get200_response import SwitchControllerVlanPolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerVlanPolicyNameGet200Response from a JSON string
switch_controller_vlan_policy_name_get200_response_instance = SwitchControllerVlanPolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerVlanPolicyNameGet200Response.to_json())

# convert the object into a dict
switch_controller_vlan_policy_name_get200_response_dict = switch_controller_vlan_policy_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerVlanPolicyNameGet200Response from a dict
switch_controller_vlan_policy_name_get200_response_from_dict = SwitchControllerVlanPolicyNameGet200Response.from_dict(switch_controller_vlan_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


