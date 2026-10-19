# SwitchControllerPtpInterfacePolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Policy name. | [optional] 
**description** | **str** | Description. | [optional] 
**vlan** | **str** | PTP VLAN. | [optional] 
**vlan_pri** | **int** | Configure PTP VLAN priority (0 - 7, default &#x3D; 4). | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_ptp_interface_policy_name_get200_response import SwitchControllerPtpInterfacePolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerPtpInterfacePolicyNameGet200Response from a JSON string
switch_controller_ptp_interface_policy_name_get200_response_instance = SwitchControllerPtpInterfacePolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerPtpInterfacePolicyNameGet200Response.to_json())

# convert the object into a dict
switch_controller_ptp_interface_policy_name_get200_response_dict = switch_controller_ptp_interface_policy_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerPtpInterfacePolicyNameGet200Response from a dict
switch_controller_ptp_interface_policy_name_get200_response_from_dict = SwitchControllerPtpInterfacePolicyNameGet200Response.from_dict(switch_controller_ptp_interface_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


