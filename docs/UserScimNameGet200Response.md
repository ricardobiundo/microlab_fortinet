# UserScimNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | SCIM client name. | [optional] 
**id** | **int** | SCIM client ID. | [optional] 
**status** | **str** | Enable/disable System for Cross-domain Identity Management (SCIM).    enable:Enable System for Cross-domain Identity Management (SCIM).    disable:Disable System for Cross-domain Identity Management (SCIM). | [optional] 
**base_url** | **str** | Server URL to receive SCIM create, read, update, delete (CRUD) requests. | [optional] 
**auth_method** | **str** | TLS client authentication methods (default &#x3D; bearer token).    token:Bearer token.    base:Base. | [optional] 
**token_certificate** | **str** | Certificate for token verification. | [optional] 
**secret** | **str** | Secret for token verification or base authentication. | [optional] 
**certificate** | **str** | Certificate for client verification during TLS handshake. | [optional] 
**client_identity_check** | **str** | Enable/disable client identity check.    enable:Enable client identity check.    disable:Disable client identity check. | [optional] 
**cascade** | **str** | Enable/disable to follow SCIM users/groups changes in IDP.    disable:Disable setting.    enable:Enable setting. | [optional] 

## Example

```python
from microlab_fortinet.models.user_scim_name_get200_response import UserScimNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserScimNameGet200Response from a JSON string
user_scim_name_get200_response_instance = UserScimNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserScimNameGet200Response.to_json())

# convert the object into a dict
user_scim_name_get200_response_dict = user_scim_name_get200_response_instance.to_dict()
# create an instance of UserScimNameGet200Response from a dict
user_scim_name_get200_response_from_dict = UserScimNameGet200Response.from_dict(user_scim_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


