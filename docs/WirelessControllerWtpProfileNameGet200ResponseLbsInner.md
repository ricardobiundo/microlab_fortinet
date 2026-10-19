# WirelessControllerWtpProfileNameGet200ResponseLbsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ekahau_blink_mode** | **str** | Enable/disable Ekahau blink mode (now known as AiRISTA Flow) to track and locate WiFi tags (default &#x3D; disable).    enable:Enable Ekahau blink mode.    disable:Disable Ekahau blink mode. | [optional] 
**ekahau_tag** | **str** | WiFi frame MAC address or WiFi Tag. | [optional] 
**erc_server_ip** | **str** | IP address of Ekahau RTLS Controller (ERC). | [optional] 
**erc_server_port** | **int** | Ekahau RTLS Controller (ERC) UDP listening port. | [optional] 
**aeroscout** | **str** | Enable/disable AeroScout Real Time Location Service (RTLS) support (default &#x3D; disable).    enable:Enable AeroScout support.    disable:Disable AeroScout support. | [optional] 
**aeroscout_server_ip** | **str** | IP address of AeroScout server. | [optional] 
**aeroscout_server_port** | **int** | AeroScout server UDP listening port. | [optional] 
**aeroscout_mu** | **str** | Enable/disable AeroScout Mobile Unit (MU) support (default &#x3D; disable).    enable:Enable AeroScout MU mode support.    disable:Disable AeroScout MU mode support. | [optional] 
**aeroscout_ap_mac** | **str** | Use BSSID or board MAC address as AP MAC address in AeroScout AP messages (default &#x3D; bssid).    bssid:Use BSSID as AP MAC address in AeroScout AP messages.    board-mac:Use board MAC address as AP MAC address in AeroScout AP messages. | [optional] 
**aeroscout_mmu_report** | **str** | Enable/disable compounded AeroScout tag and MU report (default &#x3D; enable).    enable:Enable compounded AeroScout tag and MU report.    disable:Disable compounded AeroScout tag and MU report. | [optional] 
**aeroscout_mu_factor** | **int** | AeroScout MU mode dilution factor (default &#x3D; 20). | [optional] 
**aeroscout_mu_timeout** | **int** | AeroScout MU mode timeout (0 - 65535 sec, default &#x3D; 5). | [optional] 
**fortipresence** | **str** | Enable/disable FortiPresence to monitor the location and activity of WiFi clients even if they don&#39;t connect to this WiFi network (default &#x3D; disable).    foreign:FortiPresence monitors foreign channels only. Foreign channels mean all other available channels than the current operating channel of the WTP, AP, or FortiAP.    both:Enable FortiPresence on both foreign and home channels. Select this option to have FortiPresence monitor all WiFi channels.    disable:Disable FortiPresence. | [optional] 
**fortipresence_server_addr_type** | **str** | FortiPresence server address type (default &#x3D; ipv4).    ipv4:IPv4 address.    fqdn:Fully Qualified Domain Name address. | [optional] 
**fortipresence_server** | **str** | IP address of FortiPresence server. | [optional] 
**fortipresence_server_fqdn** | **str** | FQDN of FortiPresence server. | [optional] 
**fortipresence_port** | **int** | UDP listening port of FortiPresence server (default &#x3D; 3000). | [optional] 
**fortipresence_secret** | **str** | FortiPresence secret password (max. 16 characters). | [optional] 
**fortipresence_project** | **str** | FortiPresence project name (max. 16 characters, default &#x3D; fortipresence). | [optional] 
**fortipresence_frequency** | **int** | FortiPresence report transmit frequency (5 - 65535 sec, default &#x3D; 30). | [optional] 
**fortipresence_rogue** | **str** | Enable/disable FortiPresence finding and reporting rogue APs.    enable:Enable FortiPresence finding and reporting rogue APs.    disable:Disable FortiPresence finding and reporting rogue APs. | [optional] 
**fortipresence_unassoc** | **str** | Enable/disable FortiPresence finding and reporting unassociated stations.    enable:Enable FortiPresence finding and reporting unassociated stations.    disable:Disable FortiPresence finding and reporting unassociated stations. | [optional] 
**fortipresence_ble** | **str** | Enable/disable FortiPresence finding and reporting BLE devices.    enable:Enable FortiPresence finding and reporting BLE devices.    disable:Disable FortiPresence finding and reporting BLE devices. | [optional] 
**station_locate** | **str** | Enable/disable client station locating services for all clients, whether associated or not (default &#x3D; disable).    enable:Enable station locating service.    disable:Disable station locating service. | [optional] 
**ble_rtls** | **str** | Set BLE Real Time Location Service (RTLS) support (default &#x3D; none).    none:Set BLE RTLS to none (default &#x3D; none).    polestar:Set BLE RTLS to PoleStar.    evresys:Set BLE RTLS to Evresys. | [optional] 
**ble_rtls_protocol** | **str** | Select the protocol to report Measurements, Advertising Data, or Location Data to Cloud Server (default &#x3D; WSS).    WSS:Use WebSocket protocol to report Measurements, Advertising Data, or Location Data to Cloud Server. | [optional] 
**ble_rtls_server_fqdn** | **str** | FQDN of BLE Real Time Location Service (RTLS) Server. | [optional] 
**ble_rtls_server_path** | **str** | Path of BLE Real Time Location Service (RTLS) Server. | [optional] 
**ble_rtls_server_token** | **str** | Access Token of BLE Real Time Location Service (RTLS) Server. | [optional] 
**ble_rtls_server_port** | **int** | Port of BLE Real Time Location Service (RTLS) Server (default &#x3D; 443). | [optional] 
**ble_rtls_accumulation_interval** | **int** | Time that measurements should be accumulated in seconds (default &#x3D; 2). | [optional] 
**ble_rtls_reporting_interval** | **int** | Time between reporting accumulated measurements in seconds (default &#x3D; 2). | [optional] 
**ble_rtls_asset_uuid_list1** | **str** | Tags and asset UUID list 1 to be reported (string in the format of &#39;XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX&#39;). | [optional] 
**ble_rtls_asset_uuid_list2** | **str** | Tags and asset UUID list 2 to be reported (string in the format of &#39;XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX&#39;). | [optional] 
**ble_rtls_asset_uuid_list3** | **str** | Tags and asset UUID list 3 to be reported (string in the format of &#39;XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX&#39;). | [optional] 
**ble_rtls_asset_uuid_list4** | **str** | Tags and asset UUID list 4 to be reported (string in the format of &#39;XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX&#39;). | [optional] 
**ble_rtls_asset_addrgrp_list** | **str** | Tags and asset addrgrp list to be reported. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_wtp_profile_name_get200_response_lbs_inner import WirelessControllerWtpProfileNameGet200ResponseLbsInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerWtpProfileNameGet200ResponseLbsInner from a JSON string
wireless_controller_wtp_profile_name_get200_response_lbs_inner_instance = WirelessControllerWtpProfileNameGet200ResponseLbsInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerWtpProfileNameGet200ResponseLbsInner.to_json())

# convert the object into a dict
wireless_controller_wtp_profile_name_get200_response_lbs_inner_dict = wireless_controller_wtp_profile_name_get200_response_lbs_inner_instance.to_dict()
# create an instance of WirelessControllerWtpProfileNameGet200ResponseLbsInner from a dict
wireless_controller_wtp_profile_name_get200_response_lbs_inner_from_dict = WirelessControllerWtpProfileNameGet200ResponseLbsInner.from_dict(wireless_controller_wtp_profile_name_get200_response_lbs_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


