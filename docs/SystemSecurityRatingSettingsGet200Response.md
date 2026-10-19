# SystemSecurityRatingSettingsGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**override_sync** | **str** | Enable/disable overriding Security Rating control settings synced from the Security Fabric&#39;s root FortiGate.    enable:Enable overriding the Security Rating control settings synced from the Security Fabric root FortiGate.    disable:Disable overriding the Security Rating control settings synced from the Security Fabric root FortiGate. | [optional] 

## Example

```python
from microlab_fortinet.models.system_security_rating_settings_get200_response import SystemSecurityRatingSettingsGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSecurityRatingSettingsGet200Response from a JSON string
system_security_rating_settings_get200_response_instance = SystemSecurityRatingSettingsGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSecurityRatingSettingsGet200Response.to_json())

# convert the object into a dict
system_security_rating_settings_get200_response_dict = system_security_rating_settings_get200_response_instance.to_dict()
# create an instance of SystemSecurityRatingSettingsGet200Response from a dict
system_security_rating_settings_get200_response_from_dict = SystemSecurityRatingSettingsGet200Response.from_dict(system_security_rating_settings_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


