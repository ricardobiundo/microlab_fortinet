# SwitchControllerSecurityPolicy8021XNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Policy name. | [optional] 
**security_mode** | **str** | Port or MAC based 802.1X security mode.    802.1X:802.1X port based authentication.    802.1X-mac-based:802.1X MAC based authentication. | [optional] 
**user_group** | [**List[SwitchControllerSecurityPolicy8021XNameGet200ResponseUserGroupInner]**](SwitchControllerSecurityPolicy8021XNameGet200ResponseUserGroupInner.md) | Name of user-group to assign to this MAC Authentication Bypass (MAB) policy. | [optional] 
**mac_auth_bypass** | **str** | Enable/disable MAB for this policy.    disable:Disable MAB.    enable:Enable MAB. | [optional] 
**auth_order** | **str** | Configure authentication order.    dot1x-mab:Use EAP 1X authentication first then MAB.    mab-dot1x:Use MAB authentication first then EAP 1X.    mab:Use MAB authentication only. | [optional] 
**auth_priority** | **str** | Configure authentication priority.    legacy:EAP 1X authentication has a higher priority than MAB with the legacy implementation.    dot1x-mab:EAP 1X authentication has a higher priority than MAB.    mab-dot1x:MAB authentication has a higher priority than EAP 1X. | [optional] 
**open_auth** | **str** | Enable/disable open authentication for this policy.    disable:Disable open authentication.    enable:Enable open authentication. | [optional] 
**eap_passthru** | **str** | Enable/disable EAP pass-through mode, allowing protocols (such as LLDP) to pass through ports for more flexible authentication.    disable:Disable EAP pass-through mode on this interface.    enable:Enable EAP pass-through mode on this interface. | [optional] 
**eap_auto_untagged_vlans** | **str** | Enable/disable automatic inclusion of untagged VLANs.    disable:Disable automatic inclusion of untagged VLANs.    enable:Enable automatic inclusion of untagged VLANs. | [optional] 
**guest_vlan** | **str** | Enable the guest VLAN feature to allow limited access to non-802.1X-compliant clients.    disable:Disable guest VLAN on this interface.    enable:Enable guest VLAN on this interface. | [optional] 
**guest_vlan_id** | **str** | Guest VLAN name. | [optional] 
**guest_auth_delay** | **int** | Guest authentication delay (1 - 900  sec, default &#x3D; 30). | [optional] 
**auth_fail_vlan** | **str** | Enable to allow limited access to clients that cannot authenticate.    disable:Disable authentication fail VLAN on this interface.    enable:Enable authentication fail VLAN on this interface. | [optional] 
**auth_fail_vlan_id** | **str** | VLAN ID on which authentication failed. | [optional] 
**framevid_apply** | **str** | Enable/disable the capability to apply the EAP/MAB frame VLAN to the port native VLAN.    disable:Disable the capability to apply the EAP/MAB frame VLAN to the port native VLAN.    enable:Enable the capability to apply the EAP/MAB frame VLAN to the port native VLAN. | [optional] 
**radius_timeout_overwrite** | **str** | Enable to override the global RADIUS session timeout.    disable:Override the global RADIUS session timeout.    enable:Use the global RADIUS session timeout. | [optional] 
**policy_type** | **str** | Policy type.    802.1X:802.1X security policy. | [optional] 
**authserver_timeout_period** | **int** | Authentication server timeout period (3 - 15 sec, default &#x3D; 3). | [optional] 
**authserver_timeout_vlan** | **str** | Enable/disable the authentication server timeout VLAN to allow limited access when RADIUS is unavailable.    disable:Disable authentication server timeout VLAN on this interface.    enable:Enable authentication server timeout VLAN on this interface. | [optional] 
**authserver_timeout_vlanid** | **str** | Authentication server timeout VLAN name. | [optional] 
**authserver_timeout_tagged** | **str** | Configure timeout option for the tagged VLAN which allows limited access when the authentication server is unavailable.    disable:Disable authentication server timeout on this interface.    lldp-voice:LLDP voice timeout for the tagged VLAN on this interface.    static:Static timeout for the tagged VLAN on this interface. | [optional] 
**authserver_timeout_tagged_vlanid** | **str** | Tagged VLAN name for which the timeout option is applied to (only one VLAN ID). | [optional] 
**dacl** | **str** | Enable/disable dynamic access control list on this interface.    disable:Disable dynamic access control list on this interface.    enable:Enable dynamic access control on this interface. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_security_policy8021_x_name_get200_response import SwitchControllerSecurityPolicy8021XNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerSecurityPolicy8021XNameGet200Response from a JSON string
switch_controller_security_policy8021_x_name_get200_response_instance = SwitchControllerSecurityPolicy8021XNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerSecurityPolicy8021XNameGet200Response.to_json())

# convert the object into a dict
switch_controller_security_policy8021_x_name_get200_response_dict = switch_controller_security_policy8021_x_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerSecurityPolicy8021XNameGet200Response from a dict
switch_controller_security_policy8021_x_name_get200_response_from_dict = SwitchControllerSecurityPolicy8021XNameGet200Response.from_dict(switch_controller_security_policy8021_x_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


