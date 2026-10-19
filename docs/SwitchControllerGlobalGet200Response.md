# SwitchControllerGlobalGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mac_aging_interval** | **int** | Time after which an inactive MAC is aged out (10 - 1000000 sec, default &#x3D; 300, 0 &#x3D; disable). | [optional] 
**https_image_push** | **str** | Enable/disable image push to FortiSwitch using HTTPS.    enable:Enable image push to FortiSwitch using HTTPS.    disable:Disable image push to FortiSwitch using HTTPS. | [optional] 
**vlan_all_mode** | **str** | VLAN configuration mode, user-defined-vlans or all-possible-vlans.    all:Include all possible VLANs (1-4093).    defined:Include user defined VLANs. | [optional] 
**vlan_optimization** | **str** | FortiLink VLAN optimization.    prune:Enable VLAN optimization (only VLANs necessary on or along path between destinations) on FortiSwitch units for auto-generated trunks.    configured:Enable VLAN optimization (only VLANs created on Fortilink interface) on FortiSwitch units for auto-generated trunks.    none:Disable VLAN optimization on FortiSwitch units for auto-generated trunks. | [optional] 
**vlan_identity** | **str** | Identity of the VLAN. Commonly used for RADIUS Tunnel-Private-Group-Id.    description:Configure the VLAN description to that of the FortiOS interface description if available; otherwise use the interface name.    name:Configure the VLAN description to that of the FortiOS interface name. | [optional] 
**disable_discovery** | [**List[SwitchControllerGlobalGet200ResponseDisableDiscoveryInner]**](SwitchControllerGlobalGet200ResponseDisableDiscoveryInner.md) | Prevent this FortiSwitch from discovering. | [optional] 
**mac_retention_period** | **int** | Time in hours after which an inactive MAC is removed from client DB (0 &#x3D; aged out based on mac-aging-interval). | [optional] 
**default_virtual_switch_vlan** | **str** | Default VLAN for ports when added to the virtual-switch. | [optional] 
**dhcp_server_access_list** | **str** | Enable/disable DHCP snooping server access list.    enable:Enable DHCP server access list.    disable:Disable DHCP server access list. | [optional] 
**dhcp_option82_format** | **str** | DHCP option-82 format string.    ascii:Allow user to choose values for circuit-id and remote-id.    Format:  cid&#x3D; [hostname,interface,mode,vlan,description] rid&#x3D;[hostname,xx:xx:xx:xx:xx:xx,ip]     legacy:Generate predefine fixed format for circuit-id and remote.  Format: cid&#x3D;hostname-[&lt;vlan:16&gt;&lt;mod:8&gt;&lt;port:8&gt;].32bit, rid&#x3D; [mac(0..6)].48bit  | [optional] 
**dhcp_option82_circuit_id** | **str** | List the parameters to be included to inform about client identification.    intfname:Interface name.    vlan:VLAN name.    hostname:Hostname.    mode:Mode.    description:Description. | [optional] 
**dhcp_option82_remote_id** | **str** | List the parameters to be included to inform about client identification.    mac:MAC address.    hostname:Hostname.    ip:IP address. | [optional] 
**dhcp_snoop_client_req** | **str** | Client DHCP packet broadcast mode.    drop-untrusted:Broadcast packets on trusted ports in the VLAN.    forward-untrusted:Broadcast packets on all ports in the VLAN. | [optional] 
**dhcp_snoop_client_db_exp** | **int** | Expiry time for DHCP snooping server database entries (300 - 259200 sec, default &#x3D; 86400 sec). | [optional] 
**dhcp_snoop_db_per_port_learn_limit** | **int** | Per Interface dhcp-server entries learn limit (0 - 1024, default &#x3D; 64). | [optional] 
**log_mac_limit_violations** | **str** | Enable/disable logs for Learning Limit Violations.    enable:Enable Learn Limit Violation.    disable:Disable Learn Limit Violation. | [optional] 
**mac_violation_timer** | **int** | Set timeout for Learning Limit Violations (0 &#x3D; disabled). | [optional] 
**sn_dns_resolution** | **str** | Enable/disable DNS resolution of the FortiSwitch unit&#39;s IP address with switch name.    enable:Enable DNS resolution of the FortiSwitch unit&#39;s IP address with switch name.    disable:Disable DNS resolution of the FortiSwitch unit&#39;s IP address with switch name. | [optional] 
**mac_event_logging** | **str** | Enable/disable MAC address event logging.    enable:Enable MAC address event logging.    disable:Disable MAC address event logging. | [optional] 
**bounce_quarantined_link** | **str** | Enable/disable bouncing (administratively bring the link down, up) of a switch port where a quarantined device was seen last. Helps to re-initiate the DHCP process for a device.    disable:Disable bouncing (administratively bring the link down, up) of a switch port where a quarantined device was seen last.    enable:Enable bouncing (administratively bring the link down, up) of a switch port where a quarantined device was seen last. | [optional] 
**quarantine_mode** | **str** | Quarantine mode.    by-vlan:Quarantined device traffic is sent to FortiGate on a separate quarantine VLAN.    by-redirect:Quarantined device traffic is redirected only to the FortiGate on the received VLAN. | [optional] 
**update_user_device** | **str** | Control which sources update the device user list.    mac-cache:Update MAC address from switch-controller mac-cache.    lldp:Update from FortiSwitch LLDP neighbor database.    dhcp-snooping:Update from FortiSwitch DHCP snooping client and server databases.    l2-db:Update from FortiSwitch Network-monitor Layer 2 tracking database.    l3-db:Update from FortiSwitch Network-monitor Layer 3 tracking database. | [optional] 
**custom_command** | [**List[SwitchControllerGlobalGet200ResponseCustomCommandInner]**](SwitchControllerGlobalGet200ResponseCustomCommandInner.md) | List of custom commands to be pushed to all FortiSwitches in the VDOM. | [optional] 
**fips_enforce** | **str** | Enable/disable enforcement of FIPS on managed FortiSwitch devices.    disable:Disable enforcement of FIPS on managed FortiSwitch devices.    enable:Enable enforcement of FIPS on managed FortiSwitch devices. | [optional] 
**firmware_provision_on_authorization** | **str** | Enable/disable automatic provisioning of latest firmware on authorization.    enable:Enable firmware provision on authorization.    disable:Disable firmware provision on authorization. | [optional] 
**switch_on_deauth** | **str** | No-operation/Factory-reset the managed FortiSwitch on deauthorization.    no-op:No-operation on the managed FortiSwitch on deauthorization.    factory-reset:Factory-reset the managed FortiSwitch on deauthorization. | [optional] 
**firewall_auth_user_hold_period** | **int** | Time period in minutes to hold firewall authenticated MAC users (5 - 1440, default &#x3D; 5, disable &#x3D; 0). | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_global_get200_response import SwitchControllerGlobalGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerGlobalGet200Response from a JSON string
switch_controller_global_get200_response_instance = SwitchControllerGlobalGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerGlobalGet200Response.to_json())

# convert the object into a dict
switch_controller_global_get200_response_dict = switch_controller_global_get200_response_instance.to_dict()
# create an instance of SwitchControllerGlobalGet200Response from a dict
switch_controller_global_get200_response_from_dict = SwitchControllerGlobalGet200Response.from_dict(switch_controller_global_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


