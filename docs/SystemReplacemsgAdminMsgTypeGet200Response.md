# SystemReplacemsgAdminMsgTypeGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**msg_type** | **str** | Message type. | [optional] 
**buffer** | **str** | Message string. | [optional] 
**header** | **str** | Header flag.    none:No header type.    http:HTTP    8bit:8 bit. | [optional] 
**format** | **str** | Format flag.    none:No format type.    text:Text format.    html:HTML format. | [optional] 

## Example

```python
from microlab_fortinet.models.system_replacemsg_admin_msg_type_get200_response import SystemReplacemsgAdminMsgTypeGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemReplacemsgAdminMsgTypeGet200Response from a JSON string
system_replacemsg_admin_msg_type_get200_response_instance = SystemReplacemsgAdminMsgTypeGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemReplacemsgAdminMsgTypeGet200Response.to_json())

# convert the object into a dict
system_replacemsg_admin_msg_type_get200_response_dict = system_replacemsg_admin_msg_type_get200_response_instance.to_dict()
# create an instance of SystemReplacemsgAdminMsgTypeGet200Response from a dict
system_replacemsg_admin_msg_type_get200_response_from_dict = SystemReplacemsgAdminMsgTypeGet200Response.from_dict(system_replacemsg_admin_msg_type_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


