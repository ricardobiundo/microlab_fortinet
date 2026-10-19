# SwitchControllerLldpProfileNameGet200ResponseMedNetworkPolicyInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Policy type name. | [optional] 
**status** | **str** | Enable or disable this TLV.    disable:Do not transmit this network policy TLV.    enable:Transmit this TLV if a VLAN has been addded to the port. | [optional] 
**vlan_intf** | **str** | VLAN interface to advertise; if configured on port. | [optional] 
**assign_vlan** | **str** | Enable/disable VLAN assignment when this profile is applied on managed FortiSwitch port.    disable:Disable VLAN assignment when this profile is applied on port.    enable:Enable VLAN assignment when this profile is applied on port. | [optional] 
**priority** | **int** | Advertised Layer 2 priority (0 - 7; from lowest to highest priority). | [optional] 
**dscp** | **int** | Advertised Differentiated Services Code Point (DSCP) value, a packet header value indicating the level of service requested for traffic, such as high priority or best effort delivery. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_lldp_profile_name_get200_response_med_network_policy_inner import SwitchControllerLldpProfileNameGet200ResponseMedNetworkPolicyInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerLldpProfileNameGet200ResponseMedNetworkPolicyInner from a JSON string
switch_controller_lldp_profile_name_get200_response_med_network_policy_inner_instance = SwitchControllerLldpProfileNameGet200ResponseMedNetworkPolicyInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerLldpProfileNameGet200ResponseMedNetworkPolicyInner.to_json())

# convert the object into a dict
switch_controller_lldp_profile_name_get200_response_med_network_policy_inner_dict = switch_controller_lldp_profile_name_get200_response_med_network_policy_inner_instance.to_dict()
# create an instance of SwitchControllerLldpProfileNameGet200ResponseMedNetworkPolicyInner from a dict
switch_controller_lldp_profile_name_get200_response_med_network_policy_inner_from_dict = SwitchControllerLldpProfileNameGet200ResponseMedNetworkPolicyInner.from_dict(switch_controller_lldp_profile_name_get200_response_med_network_policy_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


