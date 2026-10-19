# WirelessControllerApStatusIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | AP ID. | [optional] 
**bssid** | **str** | Access Point&#39;s (AP&#39;s) BSSID. | [optional] 
**ssid** | **str** | Access Point&#39;s (AP&#39;s) SSID. | [optional] 
**status** | **str** | Access Point&#39;s (AP&#39;s) status: rogue, accepted, or suppressed.    rogue:Rogue AP.    accepted:Accepted AP.    suppressed:Suppressed AP. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_ap_status_id_get200_response import WirelessControllerApStatusIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerApStatusIdGet200Response from a JSON string
wireless_controller_ap_status_id_get200_response_instance = WirelessControllerApStatusIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerApStatusIdGet200Response.to_json())

# convert the object into a dict
wireless_controller_ap_status_id_get200_response_dict = wireless_controller_ap_status_id_get200_response_instance.to_dict()
# create an instance of WirelessControllerApStatusIdGet200Response from a dict
wireless_controller_ap_status_id_get200_response_from_dict = WirelessControllerApStatusIdGet200Response.from_dict(wireless_controller_ap_status_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


