# SystemSsoForticloudAdminNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | FortiCloud SSO admin name. | [optional] 
**accprofile** | **str** | FortiCloud SSO admin user access profile. Permission is set to read-only without a FortiGate Cloud Central Management license. | [optional] 
**vdom** | [**List[SystemAdminNameGet200ResponseVdomInner]**](SystemAdminNameGet200ResponseVdomInner.md) | Virtual domain(s) that the administrator can access. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sso_forticloud_admin_name_get200_response import SystemSsoForticloudAdminNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSsoForticloudAdminNameGet200Response from a JSON string
system_sso_forticloud_admin_name_get200_response_instance = SystemSsoForticloudAdminNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSsoForticloudAdminNameGet200Response.to_json())

# convert the object into a dict
system_sso_forticloud_admin_name_get200_response_dict = system_sso_forticloud_admin_name_get200_response_instance.to_dict()
# create an instance of SystemSsoForticloudAdminNameGet200Response from a dict
system_sso_forticloud_admin_name_get200_response_from_dict = SystemSsoForticloudAdminNameGet200Response.from_dict(system_sso_forticloud_admin_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


