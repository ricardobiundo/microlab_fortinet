# WirelessControllerSettingGet200ResponseOffendingSsidInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**ssid_pattern** | **str** | Define offending SSID pattern (case insensitive). For example, word, word*, *word, wo*rd. | [optional] 
**action** | **str** | Actions taken for detected offending SSID.    log:Generate logs for detected offending SSID.    suppress:Suppress detected offending SSID. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_setting_get200_response_offending_ssid_inner import WirelessControllerSettingGet200ResponseOffendingSsidInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerSettingGet200ResponseOffendingSsidInner from a JSON string
wireless_controller_setting_get200_response_offending_ssid_inner_instance = WirelessControllerSettingGet200ResponseOffendingSsidInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerSettingGet200ResponseOffendingSsidInner.to_json())

# convert the object into a dict
wireless_controller_setting_get200_response_offending_ssid_inner_dict = wireless_controller_setting_get200_response_offending_ssid_inner_instance.to_dict()
# create an instance of WirelessControllerSettingGet200ResponseOffendingSsidInner from a dict
wireless_controller_setting_get200_response_offending_ssid_inner_from_dict = WirelessControllerSettingGet200ResponseOffendingSsidInner.from_dict(wireless_controller_setting_get200_response_offending_ssid_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


