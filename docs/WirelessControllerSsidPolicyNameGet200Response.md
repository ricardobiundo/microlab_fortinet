# WirelessControllerSsidPolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**description** | **str** | Description. | [optional] 
**vlan** | **str** | VLAN interface name. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_ssid_policy_name_get200_response import WirelessControllerSsidPolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerSsidPolicyNameGet200Response from a JSON string
wireless_controller_ssid_policy_name_get200_response_instance = WirelessControllerSsidPolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerSsidPolicyNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_ssid_policy_name_get200_response_dict = wireless_controller_ssid_policy_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerSsidPolicyNameGet200Response from a dict
wireless_controller_ssid_policy_name_get200_response_from_dict = WirelessControllerSsidPolicyNameGet200Response.from_dict(wireless_controller_ssid_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


