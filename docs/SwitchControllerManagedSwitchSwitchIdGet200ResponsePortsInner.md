# SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**port_name** | **str** | Switch port name. | [optional] 
**port_owner** | **str** | Switch port name. | [optional] 
**switch_id** | **str** | Switch id. | [optional] 
**speed** | **str** | Switch port speed; default and available settings depend on hardware.    10half:10M half-duplex.    10full:10M full-duplex.    100half:100M half-duplex.    100full:100M full-duplex.    1000full:1G full-duplex    10000full:10G full-duplex    auto:Auto-negotiation.    1000auto:Auto-negotiation (1G full-duplex only).    1000full-fiber:1G full-duplex (fiber SFPs only)    40000full:40G full-duplex    auto-module:Auto Module.    100FX-half:100Mbps half-duplex.100Base-FX.    100FX-full:100Mbps full-duplex.100Base-FX.    100000full:100Gbps full-duplex.    2500auto:Auto-Negotiation (2.5Gbps Only).    2500full:2.5Gbps full-duplex.    25000full:25Gbps full-duplex.    50000full:50Gbps full-duplex.    10000cr:10Gbps copper interface.    10000sr:10Gbps SFI interface.    100000sr4:100Gbps SFI interface.    100000cr4:100Gbps copper interface.    40000sr4:40Gbps SFI interface.    40000cr4:40Gbps copper interface.    40000auto:Auto-Negotiation (40Gbps Only).    25000cr:25Gbps copper interface.    25000sr:25Gbps SFI interface.    50000cr:50Gbps copper interface.    50000sr:50Gbps SFI interface.    5000auto:5Gbps full-duplex.    sgmii-auto:Auto-negotiation in SGMII mode. | [optional] 
**status** | **str** | Switch port admin status: up or down.    up:Set admin status up.    down:Set admin status down. | [optional] 
**poe_status** | **str** | Enable/disable PoE status.    enable:Enable PoE status.    disable:Disable PoE status. | [optional] 
**ip_source_guard** | **str** | Enable/disable IP source guard.    disable:Disable IP source guard.    enable:Enable IP source guard. | [optional] 
**ptp_status** | **str** | Enable/disable PTP policy on this FortiSwitch port.    disable:Disable PTP policy.    enable:Enable PTP policy. | [optional] 
**ptp_policy** | **str** | PTP policy configuration. | [optional] 
**dsl_profile** | **str** | DSL policy configuration. | [optional] 
**aggregator_mode** | **str** | LACP member select mode.    bandwidth:Member selection based on largest total bandwidth of links of similar speed.    count:Member selection based on largest count of similar link speed. | [optional] 
**flapguard** | **str** | Enable/disable flap guard.    enable:Enable FlapGuard for this port.    disable:Disable FlapGuard for this port. | [optional] 
**flap_rate** | **int** | Number of stage change events needed within flap-duration. | [optional] 
**flap_duration** | **int** | Period over which flap events are calculated (seconds). | [optional] 
**flap_timeout** | **int** | Flap guard disabling protection (min). | [optional] 
**rpvst_port** | **str** | Enable/disable inter-operability with rapid PVST on this interface.    disabled:Disable inter-operability with rapid PVST on this interface.    enabled:Enable inter-operability with rapid PVST on this interface. | [optional] 
**poe_pre_standard_detection** | **str** | Enable/disable PoE pre-standard detection.    enable:Enable PoE pre-standard detection.    disable:Disable PoE pre-standard detection. | [optional] 
**port_number** | **int** | Port number. | [optional] 
**port_prefix_type** | **int** | Port prefix type. | [optional] 
**fortilink_port** | **int** | FortiLink uplink port. | [optional] 
**poe_capable** | **int** | PoE capable. | [optional] 
**pd_capable** | **int** | Powered device capable. | [optional] 
**stacking_port** | **int** | Stacking port. | [optional] 
**p2p_port** | **int** | General peer to peer tunnel port. | [optional] 
**mclag_icl_port** | **int** | MCLAG-ICL port. | [optional] 
**authenticated_port** | **int** | Peer to Peer Authenticated port. | [optional] 
**restricted_auth_port** | **int** | Peer to Peer Restricted Authenticated port. | [optional] 
**encrypted_port** | **int** | Peer to Peer Encrypted port. | [optional] 
**fiber_port** | **int** | Fiber-port. | [optional] 
**media_type** | **str** | Media type. | [optional] 
**poe_standard** | **str** | PoE standard supported. | [optional] 
**poe_max_power** | **str** | PoE maximum power. | [optional] 
**poe_mode_bt_cabable** | **int** | PoE mode IEEE 802.3BT capable. | [optional] 
**poe_port_mode** | **str** | Configure PoE port mode.    ieee802-3af:IEEE802.3 AF.    ieee802-3at:IEEE802.3 AT.    ieee802-3bt:IEEE802.3 BT. | [optional] 
**poe_port_priority** | **str** | Configure PoE port priority.    critical-priority:Critical Priority.    high-priority:High Priority.    low-priority:Low Priority.    medium-priority:Medium Priority. | [optional] 
**poe_port_power** | **str** | Configure PoE port power.    normal:Power not delivered during boot.    perpetual:Power delivered during soft reboot.    perpetual-fast:Early power delivered during cold boot. | [optional] 
**flags** | **int** | Port properties flags. | [optional] 
**isl_local_trunk_name** | **str** | ISL local trunk name. | [optional] 
**isl_peer_port_name** | **str** | ISL peer port name. | [optional] 
**isl_peer_device_name** | **str** | ISL peer device name. | [optional] 
**isl_peer_device_sn** | **str** | ISL peer device serial number. | [optional] 
**fgt_peer_port_name** | **str** | FGT peer port name. | [optional] 
**fgt_peer_device_name** | **str** | FGT peer device name. | [optional] 
**vlan** | **str** | Assign switch ports to a VLAN. | [optional] 
**allowed_vlans_all** | **str** | Enable/disable all defined vlans on this port.    enable:Enable all defined VLANs on this port.    disable:Disable all defined VLANs on this port. | [optional] 
**allowed_vlans** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerAllowedVlansInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerAllowedVlansInner.md) | Configure switch port tagged VLANs. | [optional] 
**untagged_vlans** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerAllowedVlansInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerAllowedVlansInner.md) | Configure switch port untagged VLANs. | [optional] 
**type** | **str** | Interface type: physical or trunk port.    physical:Physical port.    trunk:Trunk port. | [optional] 
**access_mode** | **str** | Access mode of the port.    dynamic:Dynamic mode.    nac:NAC mode.    static:Static mode. | [optional] 
**matched_dpp_policy** | **str** | Matched child policy in the dynamic port policy. | [optional] 
**matched_dpp_intf_tags** | **str** | Matched interface tags in the dynamic port policy. | [optional] 
**acl_group** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerAclGroupInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerAclGroupInner.md) | ACL groups on this port. | [optional] 
**fortiswitch_acls** | [**List[SwitchControllerAclGroupNameGet200ResponseIngressInner]**](SwitchControllerAclGroupNameGet200ResponseIngressInner.md) | ACLs on this port. | [optional] 
**dhcp_snooping** | **str** | Trusted or untrusted DHCP-snooping interface.    untrusted:Untrusted DHCP snooping interface.    trusted:Trusted DHCP snooping interface. | [optional] 
**dhcp_snoop_option82_trust** | **str** | Enable/disable allowance of DHCP with option-82 on untrusted interface.    enable:Enable allowance of DHCP with option-82 on untrusted interface.    disable:Disable allowance of DHCP with option-82 on untrusted interface. | [optional] 
**dhcp_snoop_option82_override** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerDhcpSnoopOption82OverrideInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerDhcpSnoopOption82OverrideInner.md) | Configure DHCP snooping option 82 override. | [optional] 
**arp_inspection_trust** | **str** | Trusted or untrusted dynamic ARP inspection.    untrusted:Untrusted dynamic ARP inspection.    trusted:Trusted dynamic ARP inspection. | [optional] 
**igmp_snooping_flood_reports** | **str** | Enable/disable flooding of IGMP reports to this interface when igmp-snooping enabled.    enable:Enable flooding of IGMP snooping reports to this interface.    disable:Disable flooding of IGMP snooping reports to this interface. | [optional] 
**mcast_snooping_flood_traffic** | **str** | Enable/disable flooding of IGMP snooping traffic to this interface.    enable:Enable flooding of IGMP snooping traffic to this interface.    disable:Disable flooding of IGMP snooping traffic to this interface. | [optional] 
**stp_state** | **str** | Enable/disable Spanning Tree Protocol (STP) on this interface.    enabled:Enable STP on this interface.    disabled:Disable STP on this interface. | [optional] 
**stp_root_guard** | **str** | Enable/disable STP root guard on this interface.    enabled:Enable STP root-guard on this interface.    disabled:Disable STP root-guard on this interface. | [optional] 
**stp_bpdu_guard** | **str** | Enable/disable STP BPDU guard on this interface.    enabled:Enable STP BPDU guard on this interface.    disabled:Disable STP BPDU guard on this interface. | [optional] 
**stp_bpdu_guard_timeout** | **int** | BPDU Guard disabling protection (0 - 120 min). | [optional] 
**edge_port** | **str** | Enable/disable this interface as an edge port, bridging connections between workstations and/or computers.    enable:Enable this interface as an edge port.    disable:Disable this interface as an edge port. | [optional] 
**discard_mode** | **str** | Configure discard mode for port.    none:Discard disabled.    all-untagged:Discard all frames that are untagged.    all-tagged:Discard all frames that are tagged. | [optional] 
**packet_sampler** | **str** | Enable/disable packet sampling on this interface.    enabled:Enable packet sampling on this interface.    disabled:Disable packet sampling on this interface. | [optional] 
**packet_sample_rate** | **int** | Packet sampling rate (0 - 99999 p/sec). | [optional] 
**sflow_counter_interval** | **int** | sFlow sampling counter polling interval in seconds (0 - 255). | [optional] 
**sample_direction** | **str** | Packet sampling direction.    tx:Monitor transmitted traffic.    rx:Monitor received traffic.    both:Monitor transmitted and received traffic. | [optional] 
**fec_capable** | **int** | FEC capable. | [optional] 
**fec_state** | **str** | State of forward error correction.    disabled:Disable forward error correction.    cl74:Enable Clause 74 FC-FEC, which only applies to 25Gbps.    cl91:Enable Clause 91 RS-FEC, which only applies to 100Gbps.    detect-by-module:FEC supported by module. | [optional] 
**flow_control** | **str** | Flow control direction.    disable:Disable flow control.    tx:Enable flow control for transmission pause control frames.    rx:Enable flow control for receive pause control frames.    both:Enable flow control for both transmission and receive pause control frames. | [optional] 
**pause_meter** | **int** | Configure ingress pause metering rate, in kbps (default &#x3D; 0, disabled). | [optional] 
**pause_meter_resume** | **str** | Resume threshold for resuming traffic on ingress port.    75%:Back pressure state won&#39;t be cleared until bucket count falls below 75% of pause threshold.    50%:Back pressure state won&#39;t be cleared until bucket count falls below 50% of pause threshold.    25%:Back pressure state won&#39;t be cleared until bucket count falls below 25% of pause threshold. | [optional] 
**loop_guard** | **str** | Enable/disable loop-guard on this interface, an STP optimization used to prevent network loops.    enabled:Enable loop-guard on this interface.    disabled:Disable loop-guard on this interface. | [optional] 
**loop_guard_timeout** | **int** | Loop-guard timeout (0 - 120 min, default &#x3D; 45). | [optional] 
**port_policy** | **str** | Switch controller dynamic port policy from available options. | [optional] 
**qos_policy** | **str** | Switch controller QoS policy from available options. | [optional] 
**storm_control_policy** | **str** | Switch controller storm control policy from available options. | [optional] 
**port_security_policy** | **str** | Switch controller authentication policy to apply to this managed switch from available options. | [optional] 
**export_to_pool** | **str** | Switch controller export port to pool-list. | [optional] 
**interface_tags** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerInterfaceTagsInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerInterfaceTagsInner.md) | Tag(s) associated with the interface for various features including virtual port pool, dynamic port policy. | [optional] 
**learning_limit** | **int** | Limit the number of dynamic MAC addresses on this Port (1 - 128, 0 &#x3D; no limit, default). | [optional] 
**sticky_mac** | **str** | Enable or disable sticky-mac on the interface.    enable:Enable sticky mac on the interface.    disable:Disable sticky mac on the interface. | [optional] 
**lldp_status** | **str** | LLDP transmit and receive status.    disable:Disable LLDP TX and RX.    rx-only:Enable LLDP as RX only.    tx-only:Enable LLDP as TX only.    tx-rx:Enable LLDP TX and RX. | [optional] 
**lldp_profile** | **str** | LLDP port TLV profile. | [optional] 
**export_to** | **str** | Export managed-switch port to a tenant VDOM. | [optional] 
**mac_addr** | **str** | Port/Trunk MAC. | [optional] 
**allow_arp_monitor** | **str** | Enable/Disable allow ARP monitor.    disable:Disable allow ARP monitor.    enable:Enable allow ARP monitor. | [optional] 
**qnq** | **str** | 802.1AD VLANs in the VDom. | [optional] 
**log_mac_event** | **str** | Enable/disable logging for dynamic MAC address events.    disable:Disable log MAC event for this interface.    enable:Enable log MAC event for this interface. | [optional] 
**port_selection_criteria** | **str** | Algorithm for aggregate port selection.    src-mac:Source MAC address.    dst-mac:Destination MAC address.    src-dst-mac:Source and destination MAC address.    src-ip:Source IP address.    dst-ip:Destination IP address.    src-dst-ip:Source and destination IP address. | [optional] 
**description** | **str** | Description for port. | [optional] 
**lacp_speed** | **str** | End Link Aggregation Control Protocol (LACP) messages every 30 seconds (slow) or every second (fast).    slow:Send LACP message every 30 seconds.    fast:Send LACP message every second. | [optional] 
**mode** | **str** | LACP mode: ignore and do not send control messages, or negotiate 802.3ad aggregation passively or actively.    static:Static aggregation, do not send and ignore any control messages.    lacp-passive:Passively use LACP to negotiate 802.3ad aggregation.    lacp-active:Actively use LACP to negotiate 802.3ad aggregation. | [optional] 
**bundle** | **str** | Enable/disable Link Aggregation Group (LAG) bundling for non-FortiLink interfaces.    enable:Enable bundling.    disable:Disable bundling. | [optional] 
**member_withdrawal_behavior** | **str** | Port behavior after it withdraws because of loss of control packets.    forward:Forward traffic.    block:Block traffic. | [optional] 
**mclag** | **str** | Enable/disable multi-chassis link aggregation (MCLAG).    enable:Enable MCLAG.    disable:Disable MCLAG. | [optional] 
**min_bundle** | **int** | Minimum size of LAG bundle (1 - 24, default &#x3D; 1). | [optional] 
**max_bundle** | **int** | Maximum size of LAG bundle (1 - 24, default &#x3D; 24). | [optional] 
**members** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerMembersInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerMembersInner.md) | Aggregated LAG bundle interfaces. | [optional] 
**fallback_port** | **str** | LACP fallback port. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_ports_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_ports_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_ports_inner_dict = switch_controller_managed_switch_switch_id_get200_response_ports_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInner from a dict
switch_controller_managed_switch_switch_id_get200_response_ports_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_ports_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


