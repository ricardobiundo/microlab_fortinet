# WirelessControllerTimersGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**echo_interval** | **int** | Time between echo requests sent by the managed WTP, AP, or FortiAP (1 - 255 sec, default &#x3D; 30). | [optional] 
**nat_session_keep_alive** | **int** | Maximal time in seconds between control requests sent by the managed WTP, AP, or FortiAP (0 - 255 sec, default &#x3D; 0). | [optional] 
**discovery_interval** | **int** | Time between discovery requests (2 - 180 sec, default &#x3D; 5). | [optional] 
**client_idle_timeout** | **int** | Time after which a client is considered idle and times out (20 - 3600 sec, default &#x3D; 300, 0 for no timeout). | [optional] 
**client_idle_rehome_timeout** | **int** | Time after which a client is considered idle and disconnected from the home controller (2 - 3600 sec, default &#x3D; 20, 0 for no timeout). | [optional] 
**auth_timeout** | **int** | Time after which a client is considered failed in RADIUS authentication and times out (5 - 30 sec, default &#x3D; 5). | [optional] 
**rogue_ap_log** | **int** | Time between logging rogue AP messages if periodic rogue AP logging is configured (0 - 1440 min, default &#x3D; 0). | [optional] 
**fake_ap_log** | **int** | Time between recording logs about fake APs if periodic fake AP logging is configured (1 - 1440 min, default &#x3D; 1). | [optional] 
**sta_offline_cleanup** | **int** | Time period in seconds to keep station offline data after it is gone (default &#x3D; 300). | [optional] 
**sta_offline_ip2mac_cleanup** | **int** | Time period in seconds to keep station offline Ip2mac data after it is gone (default &#x3D; 300). | [optional] 
**sta_cap_cleanup** | **int** | Time period in minutes to keep station capability data after it is gone (default &#x3D; 0). | [optional] 
**rogue_ap_cleanup** | **int** | Time period in minutes to keep rogue AP after it is gone (default &#x3D; 0). | [optional] 
**rogue_sta_cleanup** | **int** | Time period in minutes to keep rogue station after it is gone (default &#x3D; 0). | [optional] 
**wids_entry_cleanup** | **int** | Time period in minutes to keep wids entry after it is gone (default &#x3D; 0). | [optional] 
**ble_device_cleanup** | **int** | Time period in minutes to keep BLE device after it is gone (default &#x3D; 60). | [optional] 
**sta_stats_interval** | **int** | Time between running client (station) reports (1 - 255 sec, default &#x3D; 10). | [optional] 
**vap_stats_interval** | **int** | Time between running Virtual Access Point (VAP) reports (1 - 255 sec, default &#x3D; 15). | [optional] 
**radio_stats_interval** | **int** | Time between running radio reports (1 - 255 sec, default &#x3D; 15). | [optional] 
**sta_capability_interval** | **int** | Time between running station capability reports (1 - 255 sec, default &#x3D; 30). | [optional] 
**sta_locate_timer** | **int** | Time between running client presence flushes to remove clients that are listed but no longer present (0 - 86400 sec, default &#x3D; 1800). | [optional] 
**ipsec_intf_cleanup** | **int** | Time period to keep IPsec VPN interfaces up after WTP sessions are disconnected (30 - 3600 sec, default &#x3D; 120). | [optional] 
**ble_scan_report_intv** | **int** | Time between running Bluetooth Low Energy (BLE) reports (10 - 3600 sec, default &#x3D; 30). | [optional] 
**drma_interval** | **int** | Dynamic radio mode assignment (DRMA) schedule interval in minutes (1 - 1440, default &#x3D; 60). | [optional] 
**ap_reboot_wait_interval1** | **int** | Time in minutes to wait before AP reboots when there is no controller detected (5 - 65535, default &#x3D; 0, 0 for no reboot). | [optional] 
**ap_reboot_wait_time** | **str** | Time to reboot the AP when there is no controller detected and standalone SSIDs are pushed to the AP in the previous session, format hh:mm. | [optional] 
**ap_reboot_wait_interval2** | **int** | Time in minutes to wait before AP reboots when there is no controller detected and standalone SSIDs are pushed to the AP in the previous session (5 - 65535, default &#x3D; 0, 0 for no reboot). | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_timers_get200_response import WirelessControllerTimersGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerTimersGet200Response from a JSON string
wireless_controller_timers_get200_response_instance = WirelessControllerTimersGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerTimersGet200Response.to_json())

# convert the object into a dict
wireless_controller_timers_get200_response_dict = wireless_controller_timers_get200_response_instance.to_dict()
# create an instance of WirelessControllerTimersGet200Response from a dict
wireless_controller_timers_get200_response_from_dict = WirelessControllerTimersGet200Response.from_dict(wireless_controller_timers_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


