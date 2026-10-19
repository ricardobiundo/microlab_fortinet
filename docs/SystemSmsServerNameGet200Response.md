# SystemSmsServerNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of SMS server. | [optional] 
**mail_server** | **str** | Email-to-SMS server domain name. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sms_server_name_get200_response import SystemSmsServerNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSmsServerNameGet200Response from a JSON string
system_sms_server_name_get200_response_instance = SystemSmsServerNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSmsServerNameGet200Response.to_json())

# convert the object into a dict
system_sms_server_name_get200_response_dict = system_sms_server_name_get200_response_instance.to_dict()
# create an instance of SystemSmsServerNameGet200Response from a dict
system_sms_server_name_get200_response_from_dict = SystemSmsServerNameGet200Response.from_dict(system_sms_server_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


