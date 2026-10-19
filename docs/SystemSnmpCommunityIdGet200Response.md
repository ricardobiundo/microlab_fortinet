# SystemSnmpCommunityIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Community ID. | [optional] 
**name** | **str** | Community name. | [optional] 
**status** | **str** | Enable/disable this SNMP community.    enable:Enable setting.    disable:Disable setting. | [optional] 
**hosts** | [**List[SystemSnmpCommunityIdGet200ResponseHostsInner]**](SystemSnmpCommunityIdGet200ResponseHostsInner.md) | Configure IPv4 SNMP managers (hosts). | [optional] 
**hosts6** | [**List[SystemSnmpCommunityIdGet200ResponseHosts6Inner]**](SystemSnmpCommunityIdGet200ResponseHosts6Inner.md) | Configure IPv6 SNMP managers. | [optional] 
**query_v1_status** | **str** | Enable/disable SNMP v1 queries.    enable:Enable setting.    disable:Disable setting. | [optional] 
**query_v1_port** | **int** | SNMP v1 query port (default &#x3D; 161). | [optional] 
**query_v2c_status** | **str** | Enable/disable SNMP v2c queries.    enable:Enable setting.    disable:Disable setting. | [optional] 
**query_v2c_port** | **int** | SNMP v2c query port (default &#x3D; 161). | [optional] 
**trap_v1_status** | **str** | Enable/disable SNMP v1 traps.    enable:Enable setting.    disable:Disable setting. | [optional] 
**trap_v1_lport** | **int** | SNMP v1 trap local port (default &#x3D; 162). | [optional] 
**trap_v1_rport** | **int** | SNMP v1 trap remote port (default &#x3D; 162). | [optional] 
**trap_v2c_status** | **str** | Enable/disable SNMP v2c traps.    enable:Enable setting.    disable:Disable setting. | [optional] 
**trap_v2c_lport** | **int** | SNMP v2c trap local port (default &#x3D; 162). | [optional] 
**trap_v2c_rport** | **int** | SNMP v2c trap remote port (default &#x3D; 162). | [optional] 
**events** | **str** | SNMP trap events.    cpu-high:Send a trap when CPU usage is high.    mem-low:Send a trap when used memory is high, free memory is low, or freeable memory is high.    log-full:Send a trap when log disk space becomes low.    intf-ip:Send a trap when an interface IP address is changed.    vpn-tun-up:Send a trap when a VPN tunnel comes up.    vpn-tun-down:Send a trap when a VPN tunnel goes down.    ha-switch:Send a trap after an HA failover when the backup unit has taken over.    ha-hb-failure:Send a trap when HA heartbeats are not received.    ips-signature:Send a trap when IPS detects an attack.    ips-anomaly:Send a trap when IPS finds an anomaly.    av-virus:Send a trap when AntiVirus finds a virus.    av-oversize:Send a trap when AntiVirus finds an oversized file.    av-pattern:Send a trap when AntiVirus finds file matching pattern.    av-fragmented:Send a trap when AntiVirus finds a fragmented file.    fm-if-change:Send a trap when FortiManager interface changes. Send a FortiManager trap.    fm-conf-change:Send a trap when a configuration change is made by a FortiGate administrator and the FortiGate is managed by FortiManager.    bgp-established:Send a trap when a BGP FSM transitions to the established state.    bgp-backward-transition:Send a trap when a BGP FSM goes from a high numbered state to a lower numbered state.    ha-member-up:Send a trap when an HA cluster member goes up.    ha-member-down:Send a trap when an HA cluster member goes down.    ent-conf-change:Send a trap when an entity MIB change occurs (RFC4133).    av-conserve:Send a trap when the FortiGate enters conserve mode.    av-bypass:Send a trap when the FortiGate enters bypass mode.    av-oversize-passed:Send a trap when AntiVirus passes an oversized file.    av-oversize-blocked:Send a trap when AntiVirus blocks an oversized file.    ips-pkg-update:Send a trap when the IPS signature database or engine is updated.    ips-fail-open:Send a trap when the IPS network buffer is full.    temperature-high:Send a trap when a temperature sensor registers a temperature that is too high.    voltage-alert:Send a trap when a voltage sensor registers a voltage that is outside of the normal range.    power-supply:Send a trap when a power supply fails or restores.    faz-disconnect:Send a trap when a FortiAnalyzer disconnects from the FortiGate.    faz:Send a trap when Fortianalyzer main server failover and alternate server take over, or alternate server failover and main server take over.    wc-ap-up:Send a trap when a managed FortiAP comes up.    wc-ap-down:Send a trap when a managed FortiAP goes down.    fswctl-session-up:Send a trap when a FortiSwitch controller session comes up.    fswctl-session-down:Send a trap when a FortiSwitch controller session goes down.    load-balance-real-server-down:Send a trap when a server load balance real server goes down.    device-new:Send a trap when a new device is found.    per-cpu-high:Send a trap when per-CPU usage is high.    dhcp:Send a trap when the DHCP server exhausts the IP pool, an IP address already is in use, or a DHCP client interface received a DHCP-NAK.    pool-usage:Send a trap about ippool usage.    ippool:Send a trap for ippool events.    interface:Send a trap for interface event.    ospf-nbr-state-change:Send a trap when there has been a change in the state of a non-virtual OSPF neighbor.    ospf-virtnbr-state-change:Send a trap when there has been a change in the state of an OSPF virtual neighbor.    bfd:Send a trap for bfd event. | [optional] 
**mib_view** | **str** | SNMP access control MIB view. | [optional] 
**vdoms** | [**List[SystemSnmpCommunityIdGet200ResponseVdomsInner]**](SystemSnmpCommunityIdGet200ResponseVdomsInner.md) | SNMP access control VDOMs. | [optional] 

## Example

```python
from microlab_fortinet.models.system_snmp_community_id_get200_response import SystemSnmpCommunityIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSnmpCommunityIdGet200Response from a JSON string
system_snmp_community_id_get200_response_instance = SystemSnmpCommunityIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSnmpCommunityIdGet200Response.to_json())

# convert the object into a dict
system_snmp_community_id_get200_response_dict = system_snmp_community_id_get200_response_instance.to_dict()
# create an instance of SystemSnmpCommunityIdGet200Response from a dict
system_snmp_community_id_get200_response_from_dict = SystemSnmpCommunityIdGet200Response.from_dict(system_snmp_community_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


