# WirelessControllerWtpWtpIdGet200ResponseRadio1Inner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**override_band** | **str** | Enable to override the WTP profile band setting.    enable:Override the WTP profile band setting.    disable:Use the WTP profile band setting. | [optional] 
**band** | **str** | WiFi band that Radio 1 operates on.    802.11a:802.11a.    802.11b:802.11b.    802.11g:802.11g.    802.11n-2G:802.11n (WiFi 4) at 2.4GHz.    802.11n-5G:802.11n (WiFi 4) at 5GHz.    802.11ac-2G:802.11ac (WiFi 5) at 2.4GHz.    802.11ac-5G:802.11ac (WiFi 5) at 5GHz.    802.11ax-2G:802.11ax (WiFi 6) at 2.4GHz.    802.11ax-5G:802.11ax (WiFi 6) at 5GHz.    802.11ax-6G:802.11ax (WiFi 6) at 6GHz.    802.11be-2G:802.11be (WiFi 7) at 2.4GHz.    802.11be-5G:802.11be (WiFi 7) at 5GHz.    802.11be-6G:802.11be (WiFi 7) at 6GHz. | [optional] 
**override_txpower** | **str** | Enable to override the WTP profile power level configuration.    enable:Override the WTP profile power level configuration.    disable:Use the WTP profile power level configuration. | [optional] 
**auto_power_level** | **str** | Enable/disable automatic power-level adjustment to prevent co-channel interference (default &#x3D; enable).    enable:Enable automatic transmit power adjustment.    disable:Disable automatic transmit power adjustment. | [optional] 
**auto_power_high** | **int** | The upper bound of automatic transmit power adjustment in dBm (the actual range of transmit power depends on the AP platform type). | [optional] 
**auto_power_low** | **int** | The lower bound of automatic transmit power adjustment in dBm (the actual range of transmit power depends on the AP platform type). | [optional] 
**auto_power_target** | **str** | Target of automatic transmit power adjustment in dBm (-95 to -20, default &#x3D; -70). | [optional] 
**power_mode** | **str** | Set radio effective isotropic radiated power (EIRP) in dBm or by a percentage of the maximum EIRP (default &#x3D; percentage). This power takes into account both radio transmit power and antenna gain. Higher power level settings may be constrained by local regulatory requirements and AP capabilities.    dBm:Set radio EIRP power in dBm.    percentage:Set radio EIRP power by percentage. | [optional] 
**power_level** | **int** | Radio EIRP power level as a percentage of the maximum EIRP power (0 - 100, default &#x3D; 100). | [optional] 
**power_value** | **int** | Radio EIRP power in dBm (1 - 33, default &#x3D; 27). | [optional] 
**override_vaps** | **str** | Enable to override WTP profile Virtual Access Point (VAP) settings.    enable:Override WTP profile VAP settings.    disable:Use WTP profile VAP settings. | [optional] 
**vap_all** | **str** | Configure method for assigning SSIDs to this FortiAP (default &#x3D; automatically assign tunnel SSIDs).    tunnel:Automatically select tunnel SSIDs.    bridge:Automatically select local-bridging SSIDs.    manual:Manually select SSIDs. | [optional] 
**vaps** | [**List[WirelessControllerWtpWtpIdGet200ResponseRadio1InnerVapsInner]**](WirelessControllerWtpWtpIdGet200ResponseRadio1InnerVapsInner.md) | Manually selected list of Virtual Access Points (VAPs). | [optional] 
**override_channel** | **str** | Enable to override WTP profile channel settings.    enable:Override WTP profile channel settings.    disable:Use WTP profile channel settings. | [optional] 
**channel** | [**List[WirelessControllerWidsProfileNameGet200ResponseApScanChannelList2G5GInner]**](WirelessControllerWidsProfileNameGet200ResponseApScanChannelList2G5GInner.md) | Selected list of wireless radio channels. | [optional] 
**drma_manual_mode** | **str** | Radio mode to be used for DRMA manual mode (default &#x3D; ncf).    ap:Set the radio to AP mode.    monitor:Set the radio to monitor mode    ncf:Select and set the radio mode based on NCF score.    ncf-peek:Select the radio mode based on NCF score, but do not apply. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_wtp_wtp_id_get200_response_radio1_inner import WirelessControllerWtpWtpIdGet200ResponseRadio1Inner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerWtpWtpIdGet200ResponseRadio1Inner from a JSON string
wireless_controller_wtp_wtp_id_get200_response_radio1_inner_instance = WirelessControllerWtpWtpIdGet200ResponseRadio1Inner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerWtpWtpIdGet200ResponseRadio1Inner.to_json())

# convert the object into a dict
wireless_controller_wtp_wtp_id_get200_response_radio1_inner_dict = wireless_controller_wtp_wtp_id_get200_response_radio1_inner_instance.to_dict()
# create an instance of WirelessControllerWtpWtpIdGet200ResponseRadio1Inner from a dict
wireless_controller_wtp_wtp_id_get200_response_radio1_inner_from_dict = WirelessControllerWtpWtpIdGet200ResponseRadio1Inner.from_dict(wireless_controller_wtp_wtp_id_get200_response_radio1_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


