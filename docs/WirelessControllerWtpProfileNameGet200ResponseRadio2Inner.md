# WirelessControllerWtpProfileNameGet200ResponseRadio2Inner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mode** | **str** | Mode of radio 2. Radio 2 can be disabled, configured as an access point, a rogue AP monitor, a sniffer, or a station.    disabled:Radio 2 is disabled.    ap:Radio 2 operates as an access point that allows WiFi clients to connect to your network.    monitor:Radio 2 operates as a dedicated monitor. As a monitor, the radio scans for other WiFi access points and adds them to the Rogue AP monitor list.    sniffer:Radio 2 operates as a sniffer capturing WiFi frames on air.    sam:Radio 2 operates as a station that can connect to a neighboring AP for connectivity and health check. | [optional] 
**band** | **str** | WiFi band that Radio 2 operates on.    802.11a:802.11a.    802.11b:802.11b.    802.11g:802.11g.    802.11n-2G:802.11n (WiFi 4) at 2.4GHz.    802.11n-5G:802.11n (WiFi 4) at 5GHz.    802.11ac-2G:802.11ac (WiFi 5) at 2.4GHz.    802.11ac-5G:802.11ac (WiFi 5) at 5GHz.    802.11ax-2G:802.11ax (WiFi 6) at 2.4GHz.    802.11ax-5G:802.11ax (WiFi 6) at 5GHz.    802.11ax-6G:802.11ax (WiFi 6) at 6GHz.    802.11be-2G:802.11be (WiFi 7) at 2.4GHz.    802.11be-5G:802.11be (WiFi 7) at 5GHz.    802.11be-6G:802.11be (WiFi 7) at 6GHz. | [optional] 
**band_5g_type** | **str** | WiFi 5G band type.    5g-full:Full 5G band.    5g-high:High 5G band.    5g-low:Low 5G band. | [optional] 
**drma** | **str** | Enable/disable dynamic radio mode assignment (DRMA) (default &#x3D; disable).    disable:Disable dynamic radio mode assignment (DRMA).    enable:Enable dynamic radio mode assignment (DRMA). | [optional] 
**drma_sensitivity** | **str** | Network Coverage Factor (NCF) percentage required to consider a radio as redundant (default &#x3D; low).    low:Consider a radio as redundant when its NCF is 100%.    medium:Consider a radio as redundant when its NCF is 95%.    high:Consider a radio as redundant when its NCF is 90%. | [optional] 
**airtime_fairness** | **str** | Enable/disable airtime fairness (default &#x3D; disable).    enable:Enable airtime fairness (ATF) support.    disable:Disable airtime fairness (ATF) support. | [optional] 
**protection_mode** | **str** | Enable/disable 802.11g protection modes to support backwards compatibility with older clients (rtscts, ctsonly, disable).    rtscts:Enable 802.11g protection RTS/CTS mode.    ctsonly:Enable 802.11g protection CTS only mode.    disable:Disable 802.11g protection mode. | [optional] 
**powersave_optimize** | **str** | Enable client power-saving features such as TIM, AC VO, and OBSS etc.    tim:TIM bit for client in power save mode.    ac-vo:Use AC VO priority to send out packets in the power save queue.    no-obss-scan:Do not put OBSS scan IE into beacon and probe response frames.    no-11b-rate:Do not send frame using 11b data rate.    client-rate-follow:Adapt transmitting PHY rate with receiving PHY rate from a client. | [optional] 
**transmit_optimize** | **str** | Packet transmission optimization options including power saving, aggregation limiting, retry limiting, etc. All are enabled by default.    disable:Disable packet transmission optimization.    power-save:Tag client as operating in power save mode if excessive transmit retries occur.    aggr-limit:Set aggregation limit to a lower value when data rate is low.    retry-limit:Set software retry limit to a lower value when data rate is low.    send-bar:Limit transmission of BAR frames. | [optional] 
**amsdu** | **str** | Enable/disable 802.11n AMSDU support. AMSDU can improve performance if supported by your WiFi clients (default &#x3D; enable).    enable:Enable AMSDU support.    disable:Disable AMSDU support. | [optional] 
**coexistence** | **str** | Enable/disable allowing both HT20 and HT40 on the same radio (default &#x3D; enable).    enable:Enable support for both HT20 and HT40 on the same radio.    disable:Disable support for both HT20 and HT40 on the same radio. | [optional] 
**zero_wait_dfs** | **str** | Enable/disable zero wait DFS on radio (default &#x3D; enable).    enable:Enable zero wait DFS    disable:Disable zero wait DFS | [optional] 
**bss_color** | **int** | BSS color value for this 11ax radio (0 - 63, disable &#x3D; 0, default &#x3D; 0). | [optional] 
**bss_color_mode** | **str** | BSS color mode for this 11ax radio (default &#x3D; auto).    auto:Automatically select BSS color value on AP.    static:Set BSS color value on this radio based on &#39;bss-color&#39; CLI. | [optional] 
**short_guard_interval** | **str** | Use either the short guard interval (Short GI) of 400 ns or the long guard interval (Long GI) of 800 ns.    enable:Select the 400 ns short guard interval (Short GI).    disable:Select the 800 ns long guard interval (Long GI). | [optional] 
**mimo_mode** | **str** | Configure radio MIMO mode (default &#x3D; default).    default:Default radio MIMO mode.    1x1:1x1 radio MIMO mode.    2x2:2x2 radio MIMO mode.    3x3:3x3 radio MIMO mode.    4x4:4x4 radio MIMO mode.    8x8:8x8 radio MIMO mode. | [optional] 
**channel_bonding** | **str** | Channel bandwidth: 320, 240, 160, 80, 40, or 20MHz. Channels may use both 20 and 40 by enabling coexistence.    320MHz:320 MHz channel width.    240MHz:240 MHz channel width.    160MHz:160 MHz channel width.    80MHz:80 MHz channel width.    40MHz:40 MHz channel width.    20MHz:20 MHz channel width. | [optional] 
**channel_bonding_ext** | **str** | Channel bandwidth extension: 320 MHz-1 and 320 MHz-2 (default &#x3D; 320 MHz-2).    320MHz-1:320 MHz channel with channel center frequency numbered 31, 95, and 159.    320MHz-2:320 MHz channel with channel center frequency numbered 63, 127, and 191. | [optional] 
**optional_antenna** | **str** | Optional antenna used on FAP (default &#x3D; none).    none:None.    custom:Customize optional antenna gain.    FANT-04ABGN-0606-O-N:6 dBi(2.4GHz) and 6 dBi(5GHz).    FANT-04ABGN-1414-P-N:14 dBi(2.4GHz) and 14 dBi(5GHz).    FANT-04ABGN-8065-P-N:8 dBi(2.4GHz) and 6.5 dBi(5GHz).    FANT-04ABGN-0606-O-R:6 dBi(2.4GHz) and 6 dBi(5GHz).    FANT-04ABGN-0606-P-R:6 dBi(2.4GHz) and 6 dBi(5GHz).    FANT-10ACAX-1213-D-N:12 dBi(2.4GHz) and 13 dBi(5GHz).    FANT-08ABGN-1213-D-R:12 dBi(2.4GHz) and 13 dBi(5GHz).    FANT-04BEAX-0606-P-R:6 dBi(2.4GHz), 6 dBi(5GHz) and 6 dBi(6GHz). | [optional] 
**optional_antenna_gain** | **str** | Optional antenna gain in dBi (0 to 20, default &#x3D; 0). | [optional] 
**auto_power_level** | **str** | Enable/disable automatic power-level adjustment to prevent co-channel interference (default &#x3D; disable).    enable:Enable automatic transmit power adjustment.    disable:Disable automatic transmit power adjustment. | [optional] 
**auto_power_high** | **int** | The upper bound of automatic transmit power adjustment in dBm (the actual range of transmit power depends on the AP platform type). | [optional] 
**auto_power_low** | **int** | The lower bound of automatic transmit power adjustment in dBm (the actual range of transmit power depends on the AP platform type). | [optional] 
**auto_power_target** | **str** | Target of automatic transmit power adjustment in dBm (-95 to -20, default &#x3D; -70). | [optional] 
**power_mode** | **str** | Set radio effective isotropic radiated power (EIRP) in dBm or by a percentage of the maximum EIRP (default &#x3D; percentage). This power takes into account both radio transmit power and antenna gain. Higher power level settings may be constrained by local regulatory requirements and AP capabilities.    dBm:Set radio EIRP power in dBm.    percentage:Set radio EIRP power by percentage. | [optional] 
**power_level** | **int** | Radio EIRP power level as a percentage of the maximum EIRP power (0 - 100, default &#x3D; 100). | [optional] 
**power_value** | **int** | Radio EIRP power in dBm (1 - 33, default &#x3D; 27). | [optional] 
**dtim** | **int** | Delivery Traffic Indication Map (DTIM) period (1 - 255, default &#x3D; 1). Set higher to save battery life of WiFi client in power-save mode. | [optional] 
**beacon_interval** | **int** | Beacon interval. The time between beacon frames in milliseconds. Actual range of beacon interval depends on the AP platform type (default &#x3D; 100). | [optional] 
**var_80211d** | **str** | Enable/disable 802.11d countryie(default &#x3D; enable).    enable:Enable 802.11d countryie.    disable:Disable 802.11d countryie. | [optional] 
**var_80211mc** | **str** | Enable/disable 802.11mc responder mode (default &#x3D; disable).    enable:Enable 802.11mc responder mode.    disable:Disable 802.11mc responder mode. | [optional] 
**rts_threshold** | **int** | Maximum packet size for RTS transmissions, specifying the maximum size of a data packet before RTS/CTS (256 - 2346 bytes, default &#x3D; 2346). | [optional] 
**frag_threshold** | **int** | Maximum packet size that can be sent without fragmentation (800 - 2346 bytes, default &#x3D; 2346). | [optional] 
**ap_sniffer_bufsize** | **int** | Sniffer buffer size (1 - 32 MB, default &#x3D; 16). | [optional] 
**ap_sniffer_chan** | **int** | Channel on which to operate the sniffer (default &#x3D; 6). | [optional] 
**ap_sniffer_chan_width** | **str** | Channel bandwidth for sniffer.    320MHz:320 MHz channel width.    240MHz:240 MHz channel width.    160MHz:160 MHz channel width.    80MHz:80 MHz channel width.    40MHz:40 MHz channel width.    20MHz:20 MHz channel width. | [optional] 
**ap_sniffer_addr** | **str** | MAC address to monitor. | [optional] 
**ap_sniffer_mgmt_beacon** | **str** | Enable/disable sniffer on WiFi management Beacon frames (default &#x3D; enable).    enable:Enable sniffer on WiFi management beacon frame.    disable:Disable sniffer on WiFi management beacon frame. | [optional] 
**ap_sniffer_mgmt_probe** | **str** | Enable/disable sniffer on WiFi management probe frames (default &#x3D; enable).    enable:Enable sniffer on WiFi management probe frame.    disable:Enable sniffer on WiFi management probe frame. | [optional] 
**ap_sniffer_mgmt_other** | **str** | Enable/disable sniffer on WiFi management other frames  (default &#x3D; enable).    enable:Enable sniffer on WiFi management other frame.    disable:Disable sniffer on WiFi management other frame. | [optional] 
**ap_sniffer_ctl** | **str** | Enable/disable sniffer on WiFi control frame (default &#x3D; enable).    enable:Enable sniffer on WiFi control frame.    disable:Disable sniffer on WiFi control frame. | [optional] 
**ap_sniffer_data** | **str** | Enable/disable sniffer on WiFi data frame (default &#x3D; enable).    enable:Enable sniffer on WiFi data frame    disable:Disable sniffer on WiFi data frame | [optional] 
**sam_ssid** | **str** | SSID for WiFi network. | [optional] 
**sam_bssid** | **str** | BSSID for WiFi network. | [optional] 
**sam_security_type** | **str** | Select WiFi network security type (default &#x3D; \&quot;wpa-personal\&quot; for 2.4/5G radio, \&quot;wpa3-sae\&quot; for 6G radio).    open:Open.    wpa-personal:WPA/WPA2 personal.    wpa-enterprise:WPA2/WPA3 enterprise.    wpa3-sae:WPA3 SAE.    owe:OWE. | [optional] 
**sam_captive_portal** | **str** | Enable/disable Captive Portal Authentication (default &#x3D; disable).    enable:Enable Captive Portal Authentication.    disable:Disable Captive Portal Authentication. | [optional] 
**sam_cwp_username** | **str** | Username for captive portal authentication. | [optional] 
**sam_cwp_password** | **str** | Password for captive portal authentication. | [optional] 
**sam_cwp_test_url** | **str** | Website the client is trying to access. | [optional] 
**sam_cwp_match_string** | **str** | Identification string from the captive portal login form. | [optional] 
**sam_cwp_success_string** | **str** | Success identification on the page after a successful login. | [optional] 
**sam_cwp_failure_string** | **str** | Failure identification on the page after an incorrect login. | [optional] 
**sam_eap_method** | **str** | Select WPA2/WPA3-ENTERPRISE EAP Method (default &#x3D; PEAP).    both:EAP PEAP and TLS. (Not applicable in FIPS mode)    tls:EAP TLS.    peap:EAP PEAP. (Not applicable in FIPS mode) | [optional] 
**sam_client_certificate** | **str** | Client certificate for WPA2/WPA3-ENTERPRISE. | [optional] 
**sam_private_key** | **str** | Private key for WPA2/WPA3-ENTERPRISE. | [optional] 
**sam_private_key_password** | **str** | Password for private key file for WPA2/WPA3-ENTERPRISE. | [optional] 
**sam_ca_certificate** | **str** | CA certificate for WPA2/WPA3-ENTERPRISE. | [optional] 
**sam_username** | **str** | Username for WiFi network connection. | [optional] 
**sam_password** | **str** | Passphrase for WiFi network connection. | [optional] 
**sam_test** | **str** | Select SAM test type (default &#x3D; \&quot;PING\&quot;).    ping:PING test.    iperf:IPERF test. | [optional] 
**sam_server_type** | **str** | Select SAM server type (default &#x3D; \&quot;IP\&quot;).    ip:IPv4 address.    fqdn:Fully Qualified Domain Name address. | [optional] 
**sam_server_ip** | **str** | SAM test server IP address. | [optional] 
**sam_server_fqdn** | **str** | SAM test server domain name. | [optional] 
**iperf_server_port** | **int** | Iperf service port number. | [optional] 
**iperf_protocol** | **str** | Iperf test protocol (default &#x3D; \&quot;UDP\&quot;).    udp:UDP.    tcp:TCP. | [optional] 
**sam_report_intv** | **int** | SAM report interval (sec), 0 for a one-time report. | [optional] 
**channel_utilization** | **str** | Enable/disable measuring channel utilization.    enable:Enable measuring channel utilization.    disable:Disable measuring channel utilization. | [optional] 
**wids_profile** | **str** | Wireless Intrusion Detection System (WIDS) profile name to assign to the radio. | [optional] 
**ai_darrp_support** | **str** | Enable/disable support for FortiAIOps to retrieve Distributed Automatic Radio Resource Provisioning (DARRP) data through REST API calls (default &#x3D; disable).    enable:Enable support for FortiAIOps REST API calls for DARRP data.    disable:Disable support for FortiAIOps REST API calls for DARRP data. | [optional] 
**darrp** | **str** | Enable/disable Distributed Automatic Radio Resource Provisioning (DARRP) to make sure the radio is always using the most optimal channel (default &#x3D; disable).    enable:Enable distributed automatic radio resource provisioning.    disable:Disable distributed automatic radio resource provisioning. | [optional] 
**arrp_profile** | **str** | Distributed Automatic Radio Resource Provisioning (DARRP) profile name to assign to the radio. | [optional] 
**max_clients** | **int** | Maximum number of stations (STAs) or WiFi clients supported by the radio. Range depends on the hardware. | [optional] 
**max_distance** | **int** | Maximum expected distance between the AP and clients (0 - 54000 m, default &#x3D; 0). | [optional] 
**vap_all** | **str** | Configure method for assigning SSIDs to this FortiAP (default &#x3D; automatically assign tunnel SSIDs).    tunnel:Automatically select tunnel SSIDs.    bridge:Automatically select local-bridging SSIDs.    manual:Manually select SSIDs. | [optional] 
**vaps** | [**List[WirelessControllerWtpWtpIdGet200ResponseRadio1InnerVapsInner]**](WirelessControllerWtpWtpIdGet200ResponseRadio1InnerVapsInner.md) | Manually selected list of Virtual Access Points (VAPs). | [optional] 
**channel** | [**List[WirelessControllerWidsProfileNameGet200ResponseApScanChannelList2G5GInner]**](WirelessControllerWidsProfileNameGet200ResponseApScanChannelList2G5GInner.md) | Selected list of wireless radio channels. | [optional] 
**call_admission_control** | **str** | Enable/disable WiFi multimedia (WMM) call admission control to optimize WiFi bandwidth use for VoIP calls. New VoIP calls are only accepted if there is enough bandwidth available to support them.    enable:Enable WMM call admission control.    disable:Disable WMM call admission control. | [optional] 
**call_capacity** | **int** | Maximum number of Voice over WLAN (VoWLAN) phones supported by the radio (0 - 60, default &#x3D; 10). | [optional] 
**bandwidth_admission_control** | **str** | Enable/disable WiFi multimedia (WMM) bandwidth admission control to optimize WiFi bandwidth use. A request to join the wireless network is only allowed if the access point has enough bandwidth to support it.    enable:Enable WMM bandwidth admission control.    disable:Disable WMM bandwidth admission control. | [optional] 
**bandwidth_capacity** | **int** | Maximum bandwidth capacity allowed (1 - 600000 Kbps, default &#x3D; 2000). | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_wtp_profile_name_get200_response_radio2_inner import WirelessControllerWtpProfileNameGet200ResponseRadio2Inner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerWtpProfileNameGet200ResponseRadio2Inner from a JSON string
wireless_controller_wtp_profile_name_get200_response_radio2_inner_instance = WirelessControllerWtpProfileNameGet200ResponseRadio2Inner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerWtpProfileNameGet200ResponseRadio2Inner.to_json())

# convert the object into a dict
wireless_controller_wtp_profile_name_get200_response_radio2_inner_dict = wireless_controller_wtp_profile_name_get200_response_radio2_inner_instance.to_dict()
# create an instance of WirelessControllerWtpProfileNameGet200ResponseRadio2Inner from a dict
wireless_controller_wtp_profile_name_get200_response_radio2_inner_from_dict = WirelessControllerWtpProfileNameGet200ResponseRadio2Inner.from_dict(wireless_controller_wtp_profile_name_get200_response_radio2_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


