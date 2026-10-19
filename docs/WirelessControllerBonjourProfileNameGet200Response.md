# WirelessControllerBonjourProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Bonjour profile name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**micro_location** | **str** | Enable/disable Micro location for Bonjour profile (default &#x3D; disable).    enable:Enable Micro location.    disable:Disable Micro location. | [optional] 
**policy_list** | [**List[WirelessControllerBonjourProfileNameGet200ResponsePolicyListInner]**](WirelessControllerBonjourProfileNameGet200ResponsePolicyListInner.md) | Bonjour policy list. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_bonjour_profile_name_get200_response import WirelessControllerBonjourProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerBonjourProfileNameGet200Response from a JSON string
wireless_controller_bonjour_profile_name_get200_response_instance = WirelessControllerBonjourProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerBonjourProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_bonjour_profile_name_get200_response_dict = wireless_controller_bonjour_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerBonjourProfileNameGet200Response from a dict
wireless_controller_bonjour_profile_name_get200_response_from_dict = WirelessControllerBonjourProfileNameGet200Response.from_dict(wireless_controller_bonjour_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


