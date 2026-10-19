# WirelessControllerGlobalGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the wireless controller. | [optional] 
**location** | **str** | Description of the location of the wireless controller. | [optional] 
**acd_process_count** | **int** | Configure the number cw_acd daemons for multi-core CPU support (default &#x3D; 0). | [optional] 
**wpad_process_count** | **int** | Wpad daemon process count for multi-core CPU support. | [optional] 
**image_download** | **str** | Enable/disable WTP image download at join time.    enable:Enable WTP image download at join time.    disable:Disable WTP image download at join time. | [optional] 
**rolling_wtp_upgrade** | **str** | Enable/disable rolling WTP upgrade (default &#x3D; disable).    enable:Enable rolling WTP upgrade.    disable:Disable rolling WTP upgrade. | [optional] 
**rolling_wtp_upgrade_threshold** | **str** | Minimum signal level/threshold in dBm required for the managed WTP to be included in rolling WTP upgrade (-95 to -20, default &#x3D; -80). | [optional] 
**max_retransmit** | **int** | Maximum number of tunnel packet retransmissions (0 - 64, default &#x3D; 3). | [optional] 
**control_message_offload** | **str** | Configure CAPWAP control message data channel offload.    ebp-frame:Ekahau blink protocol (EBP) frames.    aeroscout-tag:AeroScout tag.    ap-list:Rogue AP list.    sta-list:Rogue STA list.    sta-cap-list:STA capability list.    stats:WTP, radio, VAP, and STA statistics.    aeroscout-mu:AeroScout Mobile Unit (MU) report.    sta-health:STA health log.    spectral-analysis:Spectral analysis report. | [optional] 
**data_ethernet_ii** | **str** | Configure the wireless controller to use Ethernet II or 802.3 frames with 802.3 data tunnel mode (default &#x3D; enable).    enable:Use Ethernet II frames with 802.3 data tunnel mode.    disable:Use 802.3 Ethernet frames with 802.3 data tunnel mode. | [optional] 
**link_aggregation** | **str** | Enable/disable calculating the CAPWAP transmit hash to load balance sessions to link aggregation nodes (default &#x3D; disable).    enable:Enable calculating the CAPWAP transmit hash.    disable:Disable calculating the CAPWAP transmit hash. | [optional] 
**mesh_eth_type** | **int** | Mesh Ethernet identifier included in backhaul packets (0 - 65535, default &#x3D; 8755). | [optional] 
**fiapp_eth_type** | **int** | Ethernet type for Fortinet Inter-Access Point Protocol (IAPP), or IEEE 802.11f, packets (0 - 65535, default &#x3D; 5252). | [optional] 
**discovery_mc_addr** | **str** | Multicast IP address for AP discovery (default &#x3D; 224.0.1.140). | [optional] 
**discovery_mc_addr6** | **str** | Multicast IPv6 address for AP discovery (default &#x3D; FF02::18C). | [optional] 
**max_clients** | **int** | Maximum number of clients that can connect simultaneously (default &#x3D; 0, meaning no limitation). | [optional] 
**rogue_scan_mac_adjacency** | **int** | Maximum numerical difference between an AP&#39;s Ethernet and wireless MAC values to match for rogue detection (0 - 31, default &#x3D; 7). | [optional] 
**ipsec_base_ip** | **str** | Base IP address for IPsec VPN tunnels between the access points and the wireless controller (default &#x3D; 169.254.0.1). | [optional] 
**wtp_share** | **str** | Enable/disable sharing of WTPs between VDOMs.    enable:WTP can be shared between all VDOMs.    disable:WTP can be used only in its own VDOM. | [optional] 
**tunnel_mode** | **str** | Compatible/strict tunnel mode.    compatible:Allow for backward compatible ciphers(3DES+SHA1+Strong list).    strict:Follow system level strong-crypto ciphers. | [optional] 
**nac_interval** | **int** | Interval in seconds between two WiFi network access control (NAC) checks (10 - 600, default &#x3D; 120). | [optional] 
**ap_log_server** | **str** | Enable/disable configuring FortiGate to redirect wireless event log messages or FortiAPs to send UTM log messages to a syslog server (default &#x3D; disable).    enable:Enable AP log server.    disable:Disable AP log server. | [optional] 
**ap_log_server_ip** | **str** | IP address that FortiGate or FortiAPs send log messages to. | [optional] 
**ap_log_server_port** | **int** | Port that FortiGate or FortiAPs send log messages to. | [optional] 
**max_sta_offline** | **int** | Maximum number of station offline stored on the controller (default &#x3D; 0). | [optional] 
**max_sta_offline_ip2mac** | **int** | Maximum number of station offline ip2mac stored on the controller (default &#x3D; 0). | [optional] 
**max_sta_cap** | **int** | Maximum number of station cap stored on the controller (default &#x3D; 0). | [optional] 
**max_sta_cap_wtp** | **int** | Maximum number of station cap&#39;s wtp info stored on the controller (1 - 16, default &#x3D; 8). | [optional] 
**max_rogue_ap** | **int** | Maximum number of rogue APs stored on the controller (default &#x3D; 0). | [optional] 
**max_rogue_ap_wtp** | **int** | Maximum number of rogue AP&#39;s wtp info stored on the controller (1 - 16, default &#x3D; 16). | [optional] 
**max_rogue_sta** | **int** | Maximum number of rogue stations stored on the controller (default &#x3D; 0). | [optional] 
**max_wids_entry** | **int** | Maximum number of wids entries stored on the controller (default &#x3D; 0). | [optional] 
**max_ble_device** | **int** | Maximum number of BLE devices stored on the controller (default &#x3D; 0). | [optional] 
**dfs_lab_test** | **str** | Enable/disable DFS certificate lab test mode.    enable:Enable DFS certificate lab test mode.    disable:Disable DFS certificate lab test mode. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_global_get200_response import WirelessControllerGlobalGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerGlobalGet200Response from a JSON string
wireless_controller_global_get200_response_instance = WirelessControllerGlobalGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerGlobalGet200Response.to_json())

# convert the object into a dict
wireless_controller_global_get200_response_dict = wireless_controller_global_get200_response_instance.to_dict()
# create an instance of WirelessControllerGlobalGet200Response from a dict
wireless_controller_global_get200_response_from_dict = WirelessControllerGlobalGet200Response.from_dict(wireless_controller_global_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


