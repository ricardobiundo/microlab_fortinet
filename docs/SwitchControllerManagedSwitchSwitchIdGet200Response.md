# SwitchControllerManagedSwitchSwitchIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**switch_id** | **str** | Managed-switch name. | [optional] 
**sn** | **str** | Managed-switch serial number. | [optional] 
**description** | **str** | Description. | [optional] 
**switch_profile** | **str** | FortiSwitch profile. | [optional] 
**access_profile** | **str** | FortiSwitch access profile. | [optional] 
**purdue_level** | **str** | Purdue Level of this FortiSwitch.    1:Level 1 - Basic Control    1.5:Level 1.5    2:Level 2 - Area Supervisory Control    2.5:Level 2.5    3:Level 3 - Operations &amp; Control    3.5:Level 3.5    4:Level 4 - Business Planning &amp; Logistics    5:Level 5 - Enterprise Network    5.5:Level 5.5 | [optional] 
**fsw_wan1_peer** | **str** | FortiSwitch WAN1 peer port. | [optional] 
**fsw_wan1_admin** | **str** | FortiSwitch WAN1 admin status; enable to authorize the FortiSwitch as a managed switch.    discovered:Link waiting to be authorized.    disable:Link unauthorized.    enable:Link authorized. | [optional] 
**poe_pre_standard_detection** | **str** | Enable/disable PoE pre-standard detection.    enable:Enable PoE pre-standard detection.    disable:Disable PoE pre-standard detection. | [optional] 
**dhcp_server_access_list** | **str** | DHCP snooping server access list.    global:Use global setting for DHCP snooping server access list.    enable:Override global setting and enable DHCP server access list.    disable:Override global setting and disable DHCP server access list. | [optional] 
**poe_detection_type** | **int** | PoE detection type for FortiSwitch. | [optional] 
**max_poe_budget** | **int** | Max PoE budget for FortiSwitch. | [optional] 
**directly_connected** | **int** | Directly connected FortiSwitch. | [optional] 
**version** | **int** | FortiSwitch version. | [optional] 
**max_allowed_trunk_members** | **int** | FortiSwitch maximum allowed trunk members. | [optional] 
**pre_provisioned** | **int** | Pre-provisioned managed switch. | [optional] 
**l3_discovered** | **int** | Layer 3 management discovered. | [optional] 
**mgmt_mode** | **int** | FortiLink management mode. | [optional] 
**tunnel_discovered** | **int** | SOCKS tunnel management discovered. | [optional] 
**tdr_supported** | **str** | TDR supported. | [optional] 
**dynamic_capability** | **str** | List of features this FortiSwitch supports (not configurable) that is sent to the FortiGate device for subsequent configuration initiated by the FortiGate device. | [optional] 
**switch_device_tag** | **str** | User definable label/tag. | [optional] 
**switch_dhcp_opt43_key** | **str** | DHCP option43 key. | [optional] 
**mclag_igmp_snooping_aware** | **str** | Enable/disable MCLAG IGMP-snooping awareness.    enable:Enable MCLAG IGMP-snooping awareness.    disable:Disable MCLAG IGMP-snooping awareness. | [optional] 
**dynamically_discovered** | **int** | Dynamically discovered FortiSwitch. | [optional] 
**ptp_status** | **str** | Enable/disable PTP profile on this FortiSwitch.    disable:Disable PTP profile.    enable:Enable PTP profile. | [optional] 
**ptp_profile** | **str** | PTP profile configuration. | [optional] 
**radius_nas_ip_override** | **str** | Use locally defined NAS-IP.    disable:Disable radius-nas-ip-override.    enable:Enable radius-nas-ip-override. | [optional] 
**radius_nas_ip** | **str** | NAS-IP address. | [optional] 
**route_offload** | **str** | Enable/disable route offload on this FortiSwitch.    disable:Disable route offload.    enable:Enable route offload. | [optional] 
**route_offload_mclag** | **str** | Enable/disable route offload MCLAG on this FortiSwitch.    disable:Disable route offload MCLAG.    enable:Enable route offload MCLAG. | [optional] 
**route_offload_router** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseRouteOffloadRouterInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseRouteOffloadRouterInner.md) | Configure route offload MCLAG IP address. | [optional] 
**vlan** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseVlanInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseVlanInner.md) | Configure VLAN assignment priority. | [optional] 
**type** | **str** | Indication of switch type, physical or virtual.    virtual:Switch is of type virtual.    physical:Switch is of type physical. | [optional] 
**owner_vdom** | **str** | VDOM which owner of port belongs to. | [optional] 
**flow_identity** | **str** | Flow-tracking netflow ipfix switch identity in hex format(00000000-FFFFFFFF default&#x3D;0). | [optional] 
**staged_image_version** | **str** | Staged image version for FortiSwitch. | [optional] 
**delayed_restart_trigger** | **int** | Delayed restart triggered for this FortiSwitch. | [optional] 
**firmware_provision** | **str** | Enable/disable provisioning of firmware to FortiSwitches on join connection.    enable:Enable firmware-provision.    disable:Disable firmware-provision. | [optional] 
**firmware_provision_version** | **str** | Firmware version to provision to this FortiSwitch on bootup (major.minor.build, i.e. 6.2.1234). | [optional] 
**firmware_provision_latest** | **str** | Enable/disable one-time automatic provisioning of the latest firmware version.    disable:Do not automatically provision the latest available firmware.    once:Automatically attempt a one-time upgrade to the latest available firmware version. | [optional] 
**ports** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInner.md) | Managed-switch port list. | [optional] 
**ip_source_guard** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseIpSourceGuardInner.md) | IP source guard. | [optional] 
**stp_settings** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseStpSettingsInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseStpSettingsInner.md) | Configuration method to edit Spanning Tree Protocol (STP) settings used to prevent bridge loops. | [optional] 
**stp_instance** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseStpInstanceInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseStpInstanceInner.md) | Configuration method to edit Spanning Tree Protocol (STP) instances. | [optional] 
**override_snmp_sysinfo** | **str** | Enable/disable overriding the global SNMP system information.    disable:Use the global SNMP system information.    enable:Override the global SNMP system information. | [optional] 
**snmp_sysinfo** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpSysinfoInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpSysinfoInner.md) | Configuration method to edit Simple Network Management Protocol (SNMP) system info. | [optional] 
**override_snmp_trap_threshold** | **str** | Enable/disable overriding the global SNMP trap threshold values.    enable:Override the global SNMP trap threshold values.    disable:Use the global SNMP trap threshold values. | [optional] 
**snmp_trap_threshold** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpTrapThresholdInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpTrapThresholdInner.md) | Configuration method to edit Simple Network Management Protocol (SNMP) trap threshold values. | [optional] 
**override_snmp_community** | **str** | Enable/disable overriding the global SNMP communities.    enable:Override the global SNMP communities.    disable:Use the global SNMP communities. | [optional] 
**snmp_community** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpCommunityInner.md) | Configuration method to edit Simple Network Management Protocol (SNMP) communities. | [optional] 
**override_snmp_user** | **str** | Enable/disable overriding the global SNMP users.    enable:Override the global SNMPv3 users.    disable:Use the global SNMPv3 users. | [optional] 
**snmp_user** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpUserInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpUserInner.md) | Configuration method to edit Simple Network Management Protocol (SNMP) users. | [optional] 
**qos_drop_policy** | **str** | Set QoS drop-policy.    taildrop:Taildrop policy.    random-early-detection:Random early detection drop policy. | [optional] 
**qos_red_probability** | **int** | Set QoS RED/WRED drop probability. | [optional] 
**switch_log** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseSwitchLogInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseSwitchLogInner.md) | Configuration method to edit FortiSwitch logging settings (logs are transferred to and inserted into the FortiGate event log). | [optional] 
**remote_log** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseRemoteLogInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseRemoteLogInner.md) | Configure logging by FortiSwitch device to a remote syslog server. | [optional] 
**storm_control** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseStormControlInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseStormControlInner.md) | Configuration method to edit FortiSwitch storm control for measuring traffic activity using data rates to prevent traffic disruption. | [optional] 
**mirror** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInner.md) | Configuration method to edit FortiSwitch packet mirror. | [optional] 
**static_mac** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseStaticMacInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseStaticMacInner.md) | Configuration method to edit FortiSwitch Static and Sticky MAC. | [optional] 
**custom_command** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseCustomCommandInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseCustomCommandInner.md) | Configuration method to edit FortiSwitch commands to be pushed to this FortiSwitch device upon rebooting the FortiGate switch controller or the FortiSwitch. | [optional] 
**dhcp_snooping_static_client** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseDhcpSnoopingStaticClientInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseDhcpSnoopingStaticClientInner.md) | Configure FortiSwitch DHCP snooping static clients. | [optional] 
**igmp_snooping** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseIgmpSnoopingInner.md) | Configure FortiSwitch IGMP snooping global settings. | [optional] 
**var_802_1_x_settings** | [**List[SwitchControllerManagedSwitchSwitchIdGet200Response8021XSettingsInner]**](SwitchControllerManagedSwitchSwitchIdGet200Response8021XSettingsInner.md) | Configuration method to edit FortiSwitch 802.1X global settings. | [optional] 
**router_vrf** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterVrfInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterVrfInner.md) | Configure VRF. | [optional] 
**system_interface** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemInterfaceInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemInterfaceInner.md) | Configure system interface on FortiSwitch. | [optional] 
**router_static** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterStaticInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterStaticInner.md) | Configure static routes. | [optional] 
**system_dhcp_server** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInner.md) | Configure DHCP servers. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response import SwitchControllerManagedSwitchSwitchIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200Response from a JSON string
switch_controller_managed_switch_switch_id_get200_response_instance = SwitchControllerManagedSwitchSwitchIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200Response.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_dict = switch_controller_managed_switch_switch_id_get200_response_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200Response from a dict
switch_controller_managed_switch_switch_id_get200_response_from_dict = SwitchControllerManagedSwitchSwitchIdGet200Response.from_dict(switch_controller_managed_switch_switch_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


