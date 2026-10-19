# SystemReplacemsgGroupNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Group name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**group_type** | **str** | Group type.    default:Per-vdom replacement messages.    utm:For use with UTM settings in firewall policies.    auth:For use with authentication pages in firewall policies. | [optional] 
**mail** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**http** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**webproxy** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**ftp** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**fortiguard_wf** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**spam** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**alertmail** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**admin** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**auth** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**sslvpn** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**nac_quar** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**traffic_quota** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**utm** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**custom_message** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**icap** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 
**automation** | [**List[SystemReplacemsgAdminMsgTypeGet200Response]**](SystemReplacemsgAdminMsgTypeGet200Response.md) | Replacement message table entries. | [optional] 

## Example

```python
from microlab_fortinet.models.system_replacemsg_group_name_get200_response import SystemReplacemsgGroupNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemReplacemsgGroupNameGet200Response from a JSON string
system_replacemsg_group_name_get200_response_instance = SystemReplacemsgGroupNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemReplacemsgGroupNameGet200Response.to_json())

# convert the object into a dict
system_replacemsg_group_name_get200_response_dict = system_replacemsg_group_name_get200_response_instance.to_dict()
# create an instance of SystemReplacemsgGroupNameGet200Response from a dict
system_replacemsg_group_name_get200_response_from_dict = SystemReplacemsgGroupNameGet200Response.from_dict(system_replacemsg_group_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


