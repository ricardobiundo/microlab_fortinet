# WirelessControllerWtpProfileNameGet200ResponseDenyMacListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**mac** | **str** | A WiFi device with this MAC address is denied access to this WTP, FortiAP or AP. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_wtp_profile_name_get200_response_deny_mac_list_inner import WirelessControllerWtpProfileNameGet200ResponseDenyMacListInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerWtpProfileNameGet200ResponseDenyMacListInner from a JSON string
wireless_controller_wtp_profile_name_get200_response_deny_mac_list_inner_instance = WirelessControllerWtpProfileNameGet200ResponseDenyMacListInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerWtpProfileNameGet200ResponseDenyMacListInner.to_json())

# convert the object into a dict
wireless_controller_wtp_profile_name_get200_response_deny_mac_list_inner_dict = wireless_controller_wtp_profile_name_get200_response_deny_mac_list_inner_instance.to_dict()
# create an instance of WirelessControllerWtpProfileNameGet200ResponseDenyMacListInner from a dict
wireless_controller_wtp_profile_name_get200_response_deny_mac_list_inner_from_dict = WirelessControllerWtpProfileNameGet200ResponseDenyMacListInner.from_dict(wireless_controller_wtp_profile_name_get200_response_deny_mac_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


