# UserExternalIdentityProviderNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | External identity provider name. | [optional] 
**type** | **str** | External identity provider type.    ms-graph:Microsoft Graph server. | [optional] 
**version** | **str** | External identity API version.    v1.0:MS Graph REST API v1.0.    beta:MS Graph REST API beta (debug build only). | [optional] 
**url** | **str** | External identity provider URL (e.g. \&quot;https://example.com:8080/api/v1\&quot;). | [optional] 
**user_attr_name** | **str** | User attribute name in authentication query. | [optional] 
**group_attr_name** | **str** | Group attribute name in authentication query. | [optional] 
**port** | **int** | External identity provider service port number (0 to use default). | [optional] 
**source_ip** | **str** | Use this IPv4/v6 address to connect to the external identity provider. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 
**server_identity_check** | **str** | Enable/disable server&#39;s identity check against its certificate and subject alternative name(s).    disable:Do not check server&#39;s identity against its certificate and subject alternative name(s).    enable:Check server&#39;s identity against its certificate and subject alternative name(s). | [optional] 
**timeout** | **int** | Connection timeout value in seconds (default&#x3D;5). | [optional] 

## Example

```python
from microlab_fortinet.models.user_external_identity_provider_name_get200_response import UserExternalIdentityProviderNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserExternalIdentityProviderNameGet200Response from a JSON string
user_external_identity_provider_name_get200_response_instance = UserExternalIdentityProviderNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserExternalIdentityProviderNameGet200Response.to_json())

# convert the object into a dict
user_external_identity_provider_name_get200_response_dict = user_external_identity_provider_name_get200_response_instance.to_dict()
# create an instance of UserExternalIdentityProviderNameGet200Response from a dict
user_external_identity_provider_name_get200_response_from_dict = UserExternalIdentityProviderNameGet200Response.from_dict(user_external_identity_provider_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


