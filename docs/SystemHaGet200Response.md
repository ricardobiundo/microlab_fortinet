# SystemHaGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_id** | **int** | HA group ID  (0 - 1023;  or 0 - 7 when there are more than 2 vclusters). Must be the same for all members. | [optional] 
**group_name** | **str** | Cluster group name. Must be the same for all members. | [optional] 
**mode** | **str** | HA mode. Must be the same for all members. FGSP requires standalone.    standalone:Standalone mode.    a-a:Active-active mode.    a-p:Active-passive mode. | [optional] 
**sync_packet_balance** | **str** | Enable/disable HA packet distribution to multiple CPUs.    enable:Enable HA packet distribution to multiple CPUs.    disable:Disable HA packet distribution to multiple CPUs. | [optional] 
**password** | **str** | Cluster password. Must be the same for all members. | [optional] 
**key** | **str** | Key. | [optional] 
**hbdev** | **str** | Heartbeat interfaces. Must be the same for all members. | [optional] 
**auto_virtual_mac_interface** | [**List[SystemHaGet200ResponseAutoVirtualMacInterfaceInner]**](SystemHaGet200ResponseAutoVirtualMacInterfaceInner.md) | The physical interface that will be assigned an auto-generated virtual MAC address. | [optional] 
**backup_hbdev** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner.md) | Backup heartbeat interfaces. Must be the same for all members. | [optional] 
**session_sync_dev** | **str** | Offload session-sync process to kernel and sync sessions using connected interface(s) directly. | [optional] 
**route_ttl** | **int** | TTL for primary unit routes (5 - 3600 sec). Increase to maintain active routes during failover. | [optional] 
**route_wait** | **int** | Time to wait before sending new routes to the cluster (0 - 3600 sec). | [optional] 
**route_hold** | **int** | Time to wait between routing table updates to the cluster (0 - 3600 sec). | [optional] 
**multicast_ttl** | **int** | HA multicast TTL on primary (5 - 3600 sec). | [optional] 
**evpn_ttl** | **int** | HA EVPN FDB TTL on primary box (5 - 3600 sec). | [optional] 
**load_balance_all** | **str** | Enable to load balance TCP sessions. Disable to load balance proxy sessions only.    enable:Enable load balance.    disable:Disable load balance. | [optional] 
**sync_config** | **str** | Enable/disable configuration synchronization.    enable:Enable configuration synchronization.    disable:Disable configuration synchronization. | [optional] 
**encryption** | **str** | Enable/disable heartbeat message encryption.    enable:Enable heartbeat message encryption.    disable:Disable heartbeat message encryption. | [optional] 
**authentication** | **str** | Enable/disable heartbeat message authentication.    enable:Enable heartbeat message authentication.    disable:Disable heartbeat message authentication. | [optional] 
**hb_interval** | **int** | Time between sending heartbeat packets (1 - 20). Increase to reduce false positives. | [optional] 
**hb_interval_in_milliseconds** | **str** | Units of heartbeat interval time between sending heartbeat packets. Default is 100ms.    100ms:Each heartbeat interval is 100ms.    10ms:Each heartbeat interval is 10ms. | [optional] 
**hb_lost_threshold** | **int** | Number of lost heartbeats to signal a failure (1 - 60). Increase to reduce false positives. | [optional] 
**hello_holddown** | **int** | Time to wait before changing from hello to work state (5 - 300 sec). | [optional] 
**gratuitous_arps** | **str** | Enable/disable gratuitous ARPs. Disable if link-failed-signal enabled.    enable:Enable gratuitous ARPs.    disable:Disable gratuitous ARPs. | [optional] 
**arps** | **int** | Number of gratuitous ARPs (1 - 60). Lower to reduce traffic. Higher to reduce failover time. | [optional] 
**arps_interval** | **int** | Time between gratuitous ARPs  (1 - 20 sec). Lower to reduce failover time. Higher to reduce traffic. | [optional] 
**session_pickup** | **str** | Enable/disable session pickup. Enabling it can reduce session down time when fail over happens.    enable:Enable session pickup.    disable:Disable session pickup. | [optional] 
**session_pickup_connectionless** | **str** | Enable/disable UDP and ICMP session sync.    enable:Enable setting.    disable:Disable setting. | [optional] 
**session_pickup_expectation** | **str** | Enable/disable session helper expectation session sync for FGSP.    enable:Enable setting.    disable:Disable setting. | [optional] 
**session_pickup_nat** | **str** | Enable/disable NAT session sync for FGSP.    enable:Enable setting.    disable:Disable setting. | [optional] 
**session_pickup_delay** | **str** | Enable to sync sessions longer than 30 sec. Only longer lived sessions need to be synced.    enable:Enable setting.    disable:Disable setting. | [optional] 
**link_failed_signal** | **str** | Enable to shut down all interfaces for 1 sec after a failover. Use if gratuitous ARPs do not update network.    enable:Enable setting.    disable:Disable setting. | [optional] 
**upgrade_mode** | **str** | The mode to upgrade a cluster.    simultaneous:Upgrade all HA members at the same time.    uninterruptible:Upgrade HA cluster without blocking network traffic.    local-only:Upgrade local member only.    secondary-only:Upgrade secondary member only. | [optional] 
**uninterruptible_primary_wait** | **int** | Number of minutes the primary HA unit waits before the secondary HA unit is considered upgraded and the system is started before starting its own upgrade (15 - 300, default &#x3D; 30). | [optional] 
**standalone_mgmt_vdom** | **str** | Enable/disable standalone management VDOM.    enable:Enable setting.    disable:Disable setting. | [optional] 
**ha_mgmt_status** | **str** | Enable to reserve interfaces to manage individual cluster units.    enable:Enable setting.    disable:Disable setting. | [optional] 
**ha_mgmt_interfaces** | [**List[SystemHaGet200ResponseHaMgmtInterfacesInner]**](SystemHaGet200ResponseHaMgmtInterfacesInner.md) | Reserve interfaces to manage individual cluster units. | [optional] 
**ha_eth_type** | **str** | HA heartbeat packet Ethertype (4-digit hex). | [optional] 
**hc_eth_type** | **str** | Transparent mode HA heartbeat packet Ethertype (4-digit hex). | [optional] 
**l2ep_eth_type** | **str** | Telnet session HA heartbeat packet Ethertype (4-digit hex). | [optional] 
**ha_uptime_diff_margin** | **int** | Normally you would only reduce this value for failover testing. | [optional] 
**standalone_config_sync** | **str** | Enable/disable FGSP configuration synchronization.    enable:Enable setting.    disable:Disable setting. | [optional] 
**logical_sn** | **str** | Enable/disable usage of the logical serial number.    enable:Enable usage of the logical serial number.    disable:Disable usage of the logical serial number. | [optional] 
**schedule** | **str** | Type of A-A load balancing. Use none if you have external load balancers.    none:None.    leastconnection:Least connection.    round-robin:Round robin.    weight-round-robin:Weight round robin.    random:Random.    ip:IP.    ipport:IP port. | [optional] 
**weight** | **str** | Weight-round-robin weight for each cluster unit. Syntax &lt;priority&gt; &lt;weight&gt;. | [optional] 
**cpu_threshold** | **str** | Dynamic weighted load balancing CPU usage weight and high and low thresholds. | [optional] 
**memory_threshold** | **str** | Dynamic weighted load balancing memory usage weight and high and low thresholds. | [optional] 
**http_proxy_threshold** | **str** | Dynamic weighted load balancing weight and high and low number of HTTP proxy sessions. | [optional] 
**ftp_proxy_threshold** | **str** | Dynamic weighted load balancing weight and high and low number of FTP proxy sessions. | [optional] 
**imap_proxy_threshold** | **str** | Dynamic weighted load balancing weight and high and low number of IMAP proxy sessions. | [optional] 
**nntp_proxy_threshold** | **str** | Dynamic weighted load balancing weight and high and low number of NNTP proxy sessions. | [optional] 
**pop3_proxy_threshold** | **str** | Dynamic weighted load balancing weight and high and low number of POP3 proxy sessions. | [optional] 
**smtp_proxy_threshold** | **str** | Dynamic weighted load balancing weight and high and low number of SMTP proxy sessions. | [optional] 
**override** | **str** | Enable and increase the priority of the unit that should always be primary (master).    enable:Enable setting.    disable:Disable setting. | [optional] 
**priority** | **int** | Increase the priority to select the primary unit (0 - 255). | [optional] 
**override_wait_time** | **int** | Delay negotiating if override is enabled (0 - 3600 sec). Reduces how often the cluster negotiates. | [optional] 
**monitor** | **str** | Interfaces to check for port monitoring (or link failure). | [optional] 
**pingserver_monitor_interface** | **str** | Interfaces to check for remote IP monitoring. | [optional] 
**pingserver_failover_threshold** | **int** | Remote IP monitoring failover threshold (0 - 50). | [optional] 
**pingserver_secondary_force_reset** | **str** | Enable to force the cluster to negotiate after a remote IP monitoring failover.    enable:Enable force reset of secondary member after PING server failure.    disable:Disable force reset of secondary member after PING server failure. | [optional] 
**pingserver_flip_timeout** | **int** | Time to wait in minutes before renegotiating after a remote IP monitoring failover. | [optional] 
**vcluster_status** | **str** | Enable/disable virtual cluster for virtual clustering.    enable:Enable setting.    disable:Disable setting. | [optional] 
**vcluster** | [**List[SystemHaGet200ResponseVclusterInner]**](SystemHaGet200ResponseVclusterInner.md) | Virtual cluster table. | [optional] 
**ha_direct** | **str** | Enable/disable using ha-mgmt interface for syslog, remote authentication (RADIUS), FortiAnalyzer, FortiSandbox, sFlow, and Netflow.    enable:Enable using ha-mgmt interface for syslog, remote authentication (RADIUS), FortiAnalyzer, FortiSandbox, sFlow, and Netflow.    disable:Disable using ha-mgmt interface for syslog, remote authentication (RADIUS), FortiAnalyzer, FortiSandbox, sFlow, and Netflow. | [optional] 
**ssd_failover** | **str** | Enable/disable automatic HA failover on SSD disk failure.    enable:Enable setting.    disable:Disable setting. | [optional] 
**memory_compatible_mode** | **str** | Enable/disable memory compatible mode.    enable:Enable setting.    disable:Disable setting. | [optional] 
**memory_based_failover** | **str** | Enable/disable memory based failover.    enable:Enable setting.    disable:Disable setting. | [optional] 
**memory_failover_threshold** | **int** | Memory usage threshold to trigger memory based failover (0 means using conserve mode threshold in system.global). | [optional] 
**memory_failover_monitor_period** | **int** | Duration of high memory usage before memory based failover is triggered in seconds (1 - 300, default &#x3D; 60). | [optional] 
**memory_failover_sample_rate** | **int** | Rate at which memory usage is sampled in order to measure memory usage in seconds (1 - 60, default &#x3D; 1). | [optional] 
**memory_failover_flip_timeout** | **int** | Time to wait between subsequent memory based failovers in minutes (6 - 2147483647, default &#x3D; 6). | [optional] 
**failover_hold_time** | **int** | Time to wait before failover (0 - 300 sec, default &#x3D; 0), to avoid flip. | [optional] 
**check_secondary_dev_health** | **str** | Enable/disable secondary dev health check for session load-balance in HA A-A mode.    enable:Enable setting.    disable:Disable setting. | [optional] 
**ipsec_phase2_proposal** | **str** | IPsec phase2 proposal.    aes128-sha1:aes128-sha1    aes128-sha256:aes128-sha256    aes128-sha384:aes128-sha384    aes128-sha512:aes128-sha512    aes192-sha1:aes192-sha1    aes192-sha256:aes192-sha256    aes192-sha384:aes192-sha384    aes192-sha512:aes192-sha512    aes256-sha1:aes256-sha1    aes256-sha256:aes256-sha256    aes256-sha384:aes256-sha384    aes256-sha512:aes256-sha512    aes128gcm:aes128gcm    aes256gcm:aes256gcm    chacha20poly1305:chacha20poly1305 | [optional] 
**bounce_intf_upon_failover** | **str** | Enable/disable notification of kernel to bring down and up all monitored interfaces. The setting is used during failovers if gratuitous ARPs do not update the network.    enable:Enable setting.    disable:Disable setting. | [optional] 
**status** | **str** | list ha status information | [optional] 

## Example

```python
from microlab_fortinet.models.system_ha_get200_response import SystemHaGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemHaGet200Response from a JSON string
system_ha_get200_response_instance = SystemHaGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemHaGet200Response.to_json())

# convert the object into a dict
system_ha_get200_response_dict = system_ha_get200_response_instance.to_dict()
# create an instance of SystemHaGet200Response from a dict
system_ha_get200_response_from_dict = SystemHaGet200Response.from_dict(system_ha_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


