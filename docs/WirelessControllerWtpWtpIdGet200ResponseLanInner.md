# WirelessControllerWtpWtpIdGet200ResponseLanInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**port_mode** | **str** | LAN port mode.    offline:Offline.    nat-to-wan:NAT WTP LAN port to WTP WAN port.    bridge-to-wan:Bridge WTP LAN port to WTP WAN port.    bridge-to-ssid:Bridge WTP LAN port to SSID. | [optional] 
**port_ssid** | **str** | Bridge LAN port to SSID. | [optional] 
**port1_mode** | **str** | LAN port 1 mode.    offline:Offline.    nat-to-wan:NAT WTP LAN port to WTP WAN port.    bridge-to-wan:Bridge WTP LAN port to WTP WAN port.    bridge-to-ssid:Bridge WTP LAN port to SSID. | [optional] 
**port1_ssid** | **str** | Bridge LAN port 1 to SSID. | [optional] 
**port2_mode** | **str** | LAN port 2 mode.    offline:Offline.    nat-to-wan:NAT WTP LAN port to WTP WAN port.    bridge-to-wan:Bridge WTP LAN port to WTP WAN port.    bridge-to-ssid:Bridge WTP LAN port to SSID. | [optional] 
**port2_ssid** | **str** | Bridge LAN port 2 to SSID. | [optional] 
**port3_mode** | **str** | LAN port 3 mode.    offline:Offline.    nat-to-wan:NAT WTP LAN port to WTP WAN port.    bridge-to-wan:Bridge WTP LAN port to WTP WAN port.    bridge-to-ssid:Bridge WTP LAN port to SSID. | [optional] 
**port3_ssid** | **str** | Bridge LAN port 3 to SSID. | [optional] 
**port4_mode** | **str** | LAN port 4 mode.    offline:Offline.    nat-to-wan:NAT WTP LAN port to WTP WAN port.    bridge-to-wan:Bridge WTP LAN port to WTP WAN port.    bridge-to-ssid:Bridge WTP LAN port to SSID. | [optional] 
**port4_ssid** | **str** | Bridge LAN port 4 to SSID. | [optional] 
**port5_mode** | **str** | LAN port 5 mode.    offline:Offline.    nat-to-wan:NAT WTP LAN port to WTP WAN port.    bridge-to-wan:Bridge WTP LAN port to WTP WAN port.    bridge-to-ssid:Bridge WTP LAN port to SSID. | [optional] 
**port5_ssid** | **str** | Bridge LAN port 5 to SSID. | [optional] 
**port6_mode** | **str** | LAN port 6 mode.    offline:Offline.    nat-to-wan:NAT WTP LAN port to WTP WAN port.    bridge-to-wan:Bridge WTP LAN port to WTP WAN port.    bridge-to-ssid:Bridge WTP LAN port to SSID. | [optional] 
**port6_ssid** | **str** | Bridge LAN port 6 to SSID. | [optional] 
**port7_mode** | **str** | LAN port 7 mode.    offline:Offline.    nat-to-wan:NAT WTP LAN port to WTP WAN port.    bridge-to-wan:Bridge WTP LAN port to WTP WAN port.    bridge-to-ssid:Bridge WTP LAN port to SSID. | [optional] 
**port7_ssid** | **str** | Bridge LAN port 7 to SSID. | [optional] 
**port8_mode** | **str** | LAN port 8 mode.    offline:Offline.    nat-to-wan:NAT WTP LAN port to WTP WAN port.    bridge-to-wan:Bridge WTP LAN port to WTP WAN port.    bridge-to-ssid:Bridge WTP LAN port to SSID. | [optional] 
**port8_ssid** | **str** | Bridge LAN port 8 to SSID. | [optional] 
**port_esl_mode** | **str** | ESL port mode.    offline:Offline.    nat-to-wan:NAT WTP ESL port to WTP WAN port.    bridge-to-wan:Bridge WTP ESL port to WTP WAN port.    bridge-to-ssid:Bridge WTP ESL port to SSID. | [optional] 
**port_esl_ssid** | **str** | Bridge ESL port to SSID. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_wtp_wtp_id_get200_response_lan_inner import WirelessControllerWtpWtpIdGet200ResponseLanInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerWtpWtpIdGet200ResponseLanInner from a JSON string
wireless_controller_wtp_wtp_id_get200_response_lan_inner_instance = WirelessControllerWtpWtpIdGet200ResponseLanInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerWtpWtpIdGet200ResponseLanInner.to_json())

# convert the object into a dict
wireless_controller_wtp_wtp_id_get200_response_lan_inner_dict = wireless_controller_wtp_wtp_id_get200_response_lan_inner_instance.to_dict()
# create an instance of WirelessControllerWtpWtpIdGet200ResponseLanInner from a dict
wireless_controller_wtp_wtp_id_get200_response_lan_inner_from_dict = WirelessControllerWtpWtpIdGet200ResponseLanInner.from_dict(wireless_controller_wtp_wtp_id_get200_response_lan_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


