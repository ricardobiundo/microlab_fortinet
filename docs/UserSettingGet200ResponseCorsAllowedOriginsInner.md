# UserSettingGet200ResponseCorsAllowedOriginsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Allowed origin for CORS. | [optional] 

## Example

```python
from microlab_fortinet.models.user_setting_get200_response_cors_allowed_origins_inner import UserSettingGet200ResponseCorsAllowedOriginsInner

# TODO update the JSON string below
json = "{}"
# create an instance of UserSettingGet200ResponseCorsAllowedOriginsInner from a JSON string
user_setting_get200_response_cors_allowed_origins_inner_instance = UserSettingGet200ResponseCorsAllowedOriginsInner.from_json(json)
# print the JSON string representation of the object
print(UserSettingGet200ResponseCorsAllowedOriginsInner.to_json())

# convert the object into a dict
user_setting_get200_response_cors_allowed_origins_inner_dict = user_setting_get200_response_cors_allowed_origins_inner_instance.to_dict()
# create an instance of UserSettingGet200ResponseCorsAllowedOriginsInner from a dict
user_setting_get200_response_cors_allowed_origins_inner_from_dict = UserSettingGet200ResponseCorsAllowedOriginsInner.from_dict(user_setting_get200_response_cors_allowed_origins_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


