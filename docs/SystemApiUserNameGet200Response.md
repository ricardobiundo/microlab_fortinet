# SystemApiUserNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | User name. | [optional] 
**comments** | **str** | Comment. | [optional] 
**api_key** | **str** | Admin user password. | [optional] 
**accprofile** | **str** | Admin user access profile. | [optional] 
**vdom** | [**List[SystemAdminNameGet200ResponseVdomInner]**](SystemAdminNameGet200ResponseVdomInner.md) | Virtual domains. | [optional] 
**schedule** | **str** | Schedule name. | [optional] 
**cors_allow_origin** | **str** | Value for Access-Control-Allow-Origin on API responses. Avoid using &#39;*&#39; if possible. | [optional] 
**peer_auth** | **str** | Enable/disable peer authentication.    enable:Enable peer.    disable:Disable peer. | [optional] 
**peer_group** | **str** | Peer group name. | [optional] 
**trusthost** | [**List[SystemApiUserNameGet200ResponseTrusthostInner]**](SystemApiUserNameGet200ResponseTrusthostInner.md) | Trusthost. | [optional] 

## Example

```python
from microlab_fortinet.models.system_api_user_name_get200_response import SystemApiUserNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemApiUserNameGet200Response from a JSON string
system_api_user_name_get200_response_instance = SystemApiUserNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemApiUserNameGet200Response.to_json())

# convert the object into a dict
system_api_user_name_get200_response_dict = system_api_user_name_get200_response_instance.to_dict()
# create an instance of SystemApiUserNameGet200Response from a dict
system_api_user_name_get200_response_from_dict = SystemApiUserNameGet200Response.from_dict(system_api_user_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


