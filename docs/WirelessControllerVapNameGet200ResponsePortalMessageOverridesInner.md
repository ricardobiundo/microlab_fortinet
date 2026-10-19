# WirelessControllerVapNameGet200ResponsePortalMessageOverridesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth_disclaimer_page** | **str** | Override auth-disclaimer-page message with message from portal-message-overrides group. | [optional] 
**auth_reject_page** | **str** | Override auth-reject-page message with message from portal-message-overrides group. | [optional] 
**auth_login_page** | **str** | Override auth-login-page message with message from portal-message-overrides group. | [optional] 
**auth_login_failed_page** | **str** | Override auth-login-failed-page message with message from portal-message-overrides group. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_vap_name_get200_response_portal_message_overrides_inner import WirelessControllerVapNameGet200ResponsePortalMessageOverridesInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerVapNameGet200ResponsePortalMessageOverridesInner from a JSON string
wireless_controller_vap_name_get200_response_portal_message_overrides_inner_instance = WirelessControllerVapNameGet200ResponsePortalMessageOverridesInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerVapNameGet200ResponsePortalMessageOverridesInner.to_json())

# convert the object into a dict
wireless_controller_vap_name_get200_response_portal_message_overrides_inner_dict = wireless_controller_vap_name_get200_response_portal_message_overrides_inner_instance.to_dict()
# create an instance of WirelessControllerVapNameGet200ResponsePortalMessageOverridesInner from a dict
wireless_controller_vap_name_get200_response_portal_message_overrides_inner_from_dict = WirelessControllerVapNameGet200ResponsePortalMessageOverridesInner.from_dict(wireless_controller_vap_name_get200_response_portal_message_overrides_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


