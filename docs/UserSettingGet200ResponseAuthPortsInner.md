# UserSettingGet200ResponseAuthPortsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**type** | **str** | Service type.    http:HTTP service.    https:HTTPS service.    ftp:FTP service.    telnet:TELNET service. | [optional] 
**port** | **int** | Non-standard port for firewall user authentication. | [optional] 

## Example

```python
from microlab_fortinet.models.user_setting_get200_response_auth_ports_inner import UserSettingGet200ResponseAuthPortsInner

# TODO update the JSON string below
json = "{}"
# create an instance of UserSettingGet200ResponseAuthPortsInner from a JSON string
user_setting_get200_response_auth_ports_inner_instance = UserSettingGet200ResponseAuthPortsInner.from_json(json)
# print the JSON string representation of the object
print(UserSettingGet200ResponseAuthPortsInner.to_json())

# convert the object into a dict
user_setting_get200_response_auth_ports_inner_dict = user_setting_get200_response_auth_ports_inner_instance.to_dict()
# create an instance of UserSettingGet200ResponseAuthPortsInner from a dict
user_setting_get200_response_auth_ports_inner_from_dict = UserSettingGet200ResponseAuthPortsInner.from_dict(user_setting_get200_response_auth_ports_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


