# SystemNgfwSettingsGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**match_timeout** | **int** | Number of seconds to wait before a security policy match for an idle non-TCP session (0 - 1800, default &#x3D; 300, 0 means unlimited). | [optional] 
**tcp_match_timeout** | **int** | Number of seconds to wait before a security policy match for an idle TCP session (0 - 1800, default &#x3D; 300, 0 means unlimited). | [optional] 
**tcp_halfopen_match_timeout** | **int** | Number of seconds to wait before a security policy match for a session after one peer has sent an open session packet but the other has not responded (0 - 300, default &#x3D; 8, 0 means unlimited). | [optional] 

## Example

```python
from microlab_fortinet.models.system_ngfw_settings_get200_response import SystemNgfwSettingsGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNgfwSettingsGet200Response from a JSON string
system_ngfw_settings_get200_response_instance = SystemNgfwSettingsGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemNgfwSettingsGet200Response.to_json())

# convert the object into a dict
system_ngfw_settings_get200_response_dict = system_ngfw_settings_get200_response_instance.to_dict()
# create an instance of SystemNgfwSettingsGet200Response from a dict
system_ngfw_settings_get200_response_from_dict = SystemNgfwSettingsGet200Response.from_dict(system_ngfw_settings_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


