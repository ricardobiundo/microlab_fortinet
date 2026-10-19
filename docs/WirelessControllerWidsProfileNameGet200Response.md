# WirelessControllerWidsProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | WIDS profile name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**sensor_mode** | **str** | Scan nearby WiFi stations (default &#x3D; disable).    disable:Disable the scan.    foreign:Enable the scan and monitor foreign channels. Foreign channels are all other available channels than the current operating channel.    both:Enable the scan and monitor both foreign and home channels. Select this option to monitor all WiFi channels. | [optional] 
**ap_scan** | **str** | Enable/disable rogue AP detection.    disable:Disable rogue AP detection.    enable:Enable rogue AP detection. | [optional] 
**ap_scan_channel_list_2_g_5_g** | [**List[WirelessControllerWidsProfileNameGet200ResponseApScanChannelList2G5GInner]**](WirelessControllerWidsProfileNameGet200ResponseApScanChannelList2G5GInner.md) | Selected ap scan channel list for 2.4G and 5G bands. | [optional] 
**ap_scan_channel_list_6_g** | [**List[WirelessControllerWidsProfileNameGet200ResponseApScanChannelList6GInner]**](WirelessControllerWidsProfileNameGet200ResponseApScanChannelList6GInner.md) | Selected ap scan channel list for 6G band. | [optional] 
**ap_bgscan_period** | **int** | Period between background scans (10 - 3600 sec, default &#x3D; 600). | [optional] 
**ap_bgscan_intv** | **int** | Period between successive channel scans (1 - 600 sec, default &#x3D; 3). | [optional] 
**ap_bgscan_duration** | **int** | Listen time on scanning a channel (10 - 1000 msec, default &#x3D; 30). | [optional] 
**ap_bgscan_idle** | **int** | Wait time for channel inactivity before scanning this channel (0 - 1000 msec, default &#x3D; 20). | [optional] 
**ap_bgscan_report_intv** | **int** | Period between background scan reports (15 - 600 sec, default &#x3D; 30). | [optional] 
**ap_bgscan_disable_schedules** | [**List[WirelessControllerArrpProfileNameGet200ResponseDarrpOptimizeSchedulesInner]**](WirelessControllerArrpProfileNameGet200ResponseDarrpOptimizeSchedulesInner.md) | Firewall schedules for turning off FortiAP radio background scan. Background scan will be disabled when at least one of the schedules is valid. Separate multiple schedule names with a space. | [optional] 
**ap_fgscan_report_intv** | **int** | Period between foreground scan reports (15 - 600 sec, default &#x3D; 15). | [optional] 
**ap_scan_passive** | **str** | Enable/disable passive scanning. Enable means do not send probe request on any channels (default &#x3D; disable).    enable:Passive scanning on all channels.    disable:Passive scanning only on DFS channels. | [optional] 
**ap_scan_threshold** | **str** | Minimum signal level/threshold in dBm required for the AP to report detected rogue AP (-95 to -20, default &#x3D; -90). | [optional] 
**ap_auto_suppress** | **str** | Enable/disable on-wire rogue AP auto-suppression (default &#x3D; disable).    enable:Enable on-wire rogue AP auto-suppression.    disable:Disable on-wire rogue AP auto-suppression. | [optional] 
**wireless_bridge** | **str** | Enable/disable wireless bridge detection (default &#x3D; disable).    enable:Enable wireless bridge detection.    disable:Disable wireless bridge detection. | [optional] 
**deauth_broadcast** | **str** | Enable/disable broadcasting de-authentication detection (default &#x3D; disable).    enable:Enable broadcast de-authentication detection.    disable:Disable broadcast de-authentication detection. | [optional] 
**null_ssid_probe_resp** | **str** | Enable/disable null SSID probe response detection (default &#x3D; disable).    enable:Enable null SSID probe resp detection.    disable:Disable null SSID probe resp detection. | [optional] 
**long_duration_attack** | **str** | Enable/disable long duration attack detection based on user configured threshold (default &#x3D; disable).    enable:Enable long duration attack detection.    disable:Disable long duration attack detection. | [optional] 
**long_duration_thresh** | **int** | Threshold value for long duration attack detection (1000 - 32767 usec, default &#x3D; 8200). | [optional] 
**invalid_mac_oui** | **str** | Enable/disable invalid MAC OUI detection.    enable:Enable invalid MAC OUI detection.    disable:Disable invalid MAC OUI detection. | [optional] 
**weak_wep_iv** | **str** | Enable/disable weak WEP IV (Initialization Vector) detection (default &#x3D; disable).    enable:Enable weak WEP IV detection.    disable:Disable weak WEP IV detection. | [optional] 
**auth_frame_flood** | **str** | Enable/disable authentication frame flooding detection (default &#x3D; disable).    enable:Enable authentication frame flooding detection.    disable:Disable authentication frame flooding detection. | [optional] 
**auth_flood_time** | **int** | Number of seconds after which a station is considered not connected. | [optional] 
**auth_flood_thresh** | **int** | The threshold value for authentication frame flooding. | [optional] 
**assoc_frame_flood** | **str** | Enable/disable association frame flooding detection (default &#x3D; disable).    enable:Enable association frame flooding detection.    disable:Disable association frame flooding detection. | [optional] 
**assoc_flood_time** | **int** | Number of seconds after which a station is considered not connected. | [optional] 
**assoc_flood_thresh** | **int** | The threshold value for association frame flooding. | [optional] 
**reassoc_flood** | **str** | Enable/disable reassociation flood detection (default &#x3D; disable).    enable:Enable reassociation flood detection.    disable:Disable reassociation flood detection. | [optional] 
**reassoc_flood_time** | **int** | Detection Window Period. | [optional] 
**reassoc_flood_thresh** | **int** | The threshold value for reassociation flood. | [optional] 
**probe_flood** | **str** | Enable/disable probe flood detection (default &#x3D; disable).    enable:Enable probe flood detection.    disable:Disable probe flood detection. | [optional] 
**probe_flood_time** | **int** | Detection Window Period. | [optional] 
**probe_flood_thresh** | **int** | The threshold value for probe flood. | [optional] 
**bcn_flood** | **str** | Enable/disable bcn flood detection (default &#x3D; disable).    enable:Enable bcn flood detection.    disable:Disable bcn flood detection. | [optional] 
**bcn_flood_time** | **int** | Detection Window Period. | [optional] 
**bcn_flood_thresh** | **int** | The threshold value for bcn flood. | [optional] 
**rts_flood** | **str** | Enable/disable rts flood detection (default &#x3D; disable).    enable:Enable rts flood detection.    disable:Disable rts flood detection. | [optional] 
**rts_flood_time** | **int** | Detection Window Period. | [optional] 
**rts_flood_thresh** | **int** | The threshold value for rts flood. | [optional] 
**cts_flood** | **str** | Enable/disable cts flood detection (default &#x3D; disable).    enable:Enable cts flood detection.    disable:Disable cts flood detection. | [optional] 
**cts_flood_time** | **int** | Detection Window Period. | [optional] 
**cts_flood_thresh** | **int** | The threshold value for cts flood. | [optional] 
**client_flood** | **str** | Enable/disable client flood detection (default &#x3D; disable).    enable:Enable client flood detection.    disable:Disable client flood detection. | [optional] 
**client_flood_time** | **int** | Detection Window Period. | [optional] 
**client_flood_thresh** | **int** | The threshold value for client flood. | [optional] 
**block_ack_flood** | **str** | Enable/disable block_ack flood detection (default &#x3D; disable).    enable:Enable block_ack flood detection.    disable:Disable block_ack flood detection. | [optional] 
**block_ack_flood_time** | **int** | Detection Window Period. | [optional] 
**block_ack_flood_thresh** | **int** | The threshold value for block_ack flood. | [optional] 
**pspoll_flood** | **str** | Enable/disable pspoll flood detection (default &#x3D; disable).    enable:Enable pspoll flood detection.    disable:Disable pspoll flood detection. | [optional] 
**pspoll_flood_time** | **int** | Detection Window Period. | [optional] 
**pspoll_flood_thresh** | **int** | The threshold value for pspoll flood. | [optional] 
**netstumbler** | **str** | Enable/disable netstumbler detection (default &#x3D; disable).    enable:Enable netstumbler detection.    disable:Disable netstumbler detection. | [optional] 
**netstumbler_time** | **int** | Detection Window Period. | [optional] 
**netstumbler_thresh** | **int** | The threshold value for netstumbler. | [optional] 
**wellenreiter** | **str** | Enable/disable wellenreiter detection (default &#x3D; disable).    enable:Enable wellenreiter detection.    disable:Disable wellenreiter detection. | [optional] 
**wellenreiter_time** | **int** | Detection Window Period. | [optional] 
**wellenreiter_thresh** | **int** | The threshold value for wellenreiter. | [optional] 
**spoofed_deauth** | **str** | Enable/disable spoofed de-authentication attack detection (default &#x3D; disable).    enable:Enable spoofed de-authentication attack detection.    disable:Disable spoofed de-authentication attack detection. | [optional] 
**asleap_attack** | **str** | Enable/disable asleap attack detection (default &#x3D; disable).    enable:Enable asleap attack detection.    disable:Disable asleap attack detection. | [optional] 
**eapol_start_flood** | **str** | Enable/disable EAPOL-Start flooding (to AP) detection (default &#x3D; disable).    enable:Enable EAPOL-Start flooding detection.    disable:Disable EAPOL-Start flooding detection. | [optional] 
**eapol_start_thresh** | **int** | The threshold value for EAPOL-Start flooding in specified interval. | [optional] 
**eapol_start_intv** | **int** | The detection interval for EAPOL-Start flooding (1 - 3600 sec). | [optional] 
**eapol_logoff_flood** | **str** | Enable/disable EAPOL-Logoff flooding (to AP) detection (default &#x3D; disable).    enable:Enable EAPOL-Logoff flooding detection.    disable:Disable EAPOL-Logoff flooding detection. | [optional] 
**eapol_logoff_thresh** | **int** | The threshold value for EAPOL-Logoff flooding in specified interval. | [optional] 
**eapol_logoff_intv** | **int** | The detection interval for EAPOL-Logoff flooding (1 - 3600 sec). | [optional] 
**eapol_succ_flood** | **str** | Enable/disable EAPOL-Success flooding (to AP) detection (default &#x3D; disable).    enable:Enable EAPOL-Success flooding detection.    disable:Disable EAPOL-Success flooding detection. | [optional] 
**eapol_succ_thresh** | **int** | The threshold value for EAPOL-Success flooding in specified interval. | [optional] 
**eapol_succ_intv** | **int** | The detection interval for EAPOL-Success flooding (1 - 3600 sec). | [optional] 
**eapol_fail_flood** | **str** | Enable/disable EAPOL-Failure flooding (to AP) detection (default &#x3D; disable).    enable:Enable EAPOL-Failure flooding detection.    disable:Disable EAPOL-Failure flooding detection. | [optional] 
**eapol_fail_thresh** | **int** | The threshold value for EAPOL-Failure flooding in specified interval. | [optional] 
**eapol_fail_intv** | **int** | The detection interval for EAPOL-Failure flooding (1 - 3600 sec). | [optional] 
**eapol_pre_succ_flood** | **str** | Enable/disable premature EAPOL-Success flooding (to STA) detection (default &#x3D; disable).    enable:Enable premature EAPOL-Success flooding detection.    disable:Disable premature EAPOL-Success flooding detection. | [optional] 
**eapol_pre_succ_thresh** | **int** | The threshold value for premature EAPOL-Success flooding in specified interval. | [optional] 
**eapol_pre_succ_intv** | **int** | The detection interval for premature EAPOL-Success flooding (1 - 3600 sec). | [optional] 
**eapol_pre_fail_flood** | **str** | Enable/disable premature EAPOL-Failure flooding (to STA) detection (default &#x3D; disable).    enable:Enable premature EAPOL-Failure flooding detection.    disable:Disable premature EAPOL-Failure flooding detection. | [optional] 
**eapol_pre_fail_thresh** | **int** | The threshold value for premature EAPOL-Failure flooding in specified interval. | [optional] 
**eapol_pre_fail_intv** | **int** | The detection interval for premature EAPOL-Failure flooding (1 - 3600 sec). | [optional] 
**deauth_unknown_src_thresh** | **int** | Threshold value per second to deauth unknown src for DoS attack (0: no limit). | [optional] 
**windows_bridge** | **str** | Enable/disable windows bridge detection (default &#x3D; disable).    enable:Enable windows bridge detection.    disable:Disable windows bridge detection. | [optional] 
**disassoc_broadcast** | **str** | Enable/disable broadcast dis-association detection (default &#x3D; disable).    enable:Enable broadcast dis-association detection.    disable:Disable broadcast dis-association detection. | [optional] 
**ap_spoofing** | **str** | Enable/disable AP spoofing detection (default &#x3D; disable).    enable:Enable AP spoofing detection.    disable:Disable AP spoofing detection. | [optional] 
**chan_based_mitm** | **str** | Enable/disable channel based mitm detection (default &#x3D; disable).    enable:Enable channel based mitm detection.    disable:Disable channel based mitm detection. | [optional] 
**adhoc_valid_ssid** | **str** | Enable/disable adhoc using valid SSID detection (default &#x3D; disable).    enable:Enable adhoc using valid SSID detection.    disable:Disable adhoc using valid SSID detection. | [optional] 
**adhoc_network** | **str** | Enable/disable adhoc network detection (default &#x3D; disable).    enable:Enable adhoc network detection.    disable:Disable adhoc network detection. | [optional] 
**eapol_key_overflow** | **str** | Enable/disable overflow EAPOL key detection (default &#x3D; disable).    enable:Enable overflow EAPOL key detection.    disable:Disable overflow EAPOL key detection. | [optional] 
**ap_impersonation** | **str** | Enable/disable AP impersonation detection (default &#x3D; disable).    enable:Enable AP impersonation detection.    disable:Disable AP impersonation detection. | [optional] 
**invalid_addr_combination** | **str** | Enable/disable invalid address combination detection (default &#x3D; disable).    enable:Enable invalid address combination detection.    disable:Disable invalid address combination detection. | [optional] 
**beacon_wrong_channel** | **str** | Enable/disable beacon wrong channel detection (default &#x3D; disable).    enable:Enable beacon wrong channel detection.    disable:Disable beacon wrong channel detection. | [optional] 
**ht_greenfield** | **str** | Enable/disable HT greenfield detection (default &#x3D; disable).    enable:Enable HT greenfield detection.    disable:Disable HT greenfield detection. | [optional] 
**overflow_ie** | **str** | Enable/disable overflow IE detection (default &#x3D; disable).    enable:Enable overflow IE detection.    disable:Disable overflow IE detection. | [optional] 
**malformed_ht_ie** | **str** | Enable/disable malformed HT IE detection (default &#x3D; disable).    enable:Enable malformed HT IE detection.    disable:Disable malformed HT IE detection. | [optional] 
**malformed_auth** | **str** | Enable/disable malformed auth frame detection (default &#x3D; disable).    enable:Enable malformed auth frame detection.    disable:Disable malformed auth frame detection. | [optional] 
**malformed_association** | **str** | Enable/disable malformed association request detection (default &#x3D; disable).    enable:Enable malformed association request detection.    disable:Disable malformed association request detection. | [optional] 
**ht_40mhz_intolerance** | **str** | Enable/disable HT 40 MHz intolerance detection (default &#x3D; disable).    enable:Enable HT 40 MHz intolerance detection.    disable:Disable HT 40 MHz intolerance detection. | [optional] 
**valid_ssid_misuse** | **str** | Enable/disable valid SSID misuse detection (default &#x3D; disable).    enable:Enable valid SSID misuse detection.    disable:Disable valid SSID misuse detection. | [optional] 
**valid_client_misassociation** | **str** | Enable/disable valid client misassociation detection (default &#x3D; disable).    enable:Enable valid client misassociation detection.    disable:Disable valid client misassociation detection. | [optional] 
**hotspotter_attack** | **str** | Enable/disable hotspotter attack detection (default &#x3D; disable).    enable:Enable hotspotter attack detection.    disable:Disable hotspotter attack detection. | [optional] 
**pwsave_dos_attack** | **str** | Enable/disable power save DOS attack detection (default &#x3D; disable).    enable:Enable power save DOS attack detection.    disable:Disable power save DOS attack detection. | [optional] 
**omerta_attack** | **str** | Enable/disable omerta attack detection (default &#x3D; disable).    enable:Enable omerta attack detection.    disable:Disable omerta attack detection. | [optional] 
**disconnect_station** | **str** | Enable/disable disconnect station detection (default &#x3D; disable).    enable:Enable disconnect station detection.    disable:Disable disconnect station detection. | [optional] 
**unencrypted_valid** | **str** | Enable/disable unencrypted valid detection (default &#x3D; disable).    enable:Enable unencrypted valid detection.    disable:Disable unencrypted valid detection. | [optional] 
**fata_jack** | **str** | Enable/disable FATA-Jack detection (default &#x3D; disable).    enable:Enable FATA-Jack detection.    disable:Disable FATA-Jack detection. | [optional] 
**risky_encryption** | **str** | Enable/disable Risky Encryption detection (default &#x3D; disable).    enable:Enable Risky Encryption detection.    disable:Disable Risky Encryption detection. | [optional] 
**fuzzed_beacon** | **str** | Enable/disable fuzzed beacon detection (default &#x3D; disable).    enable:Enable fuzzed beacon detection.    disable:Disable fuzzed beacon detection. | [optional] 
**fuzzed_probe_request** | **str** | Enable/disable fuzzed probe request detection (default &#x3D; disable).    enable:Enable fuzzed probe request detection.    disable:Disable fuzzed probe request detection. | [optional] 
**fuzzed_probe_response** | **str** | Enable/disable fuzzed probe response detection (default &#x3D; disable).    enable:Enable fuzzed probe response detection.    disable:Disable fuzzed probe response detection. | [optional] 
**air_jack** | **str** | Enable/disable AirJack detection (default &#x3D; disable).    enable:Enable AirJack detection.    disable:Disable AirJack detection. | [optional] 
**wpa_ft_attack** | **str** | Enable/disable WPA FT attack detection (default &#x3D; disable).    enable:Enable WPA FT attack detection.    disable:Disable WPA FT attack detection. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_wids_profile_name_get200_response import WirelessControllerWidsProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerWidsProfileNameGet200Response from a JSON string
wireless_controller_wids_profile_name_get200_response_instance = WirelessControllerWidsProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerWidsProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_wids_profile_name_get200_response_dict = wireless_controller_wids_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerWidsProfileNameGet200Response from a dict
wireless_controller_wids_profile_name_get200_response_from_dict = WirelessControllerWidsProfileNameGet200Response.from_dict(wireless_controller_wids_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


