# UserFssoPollingIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Active Directory server ID. | [optional] 
**status** | **str** | Enable/disable polling for the status of this Active Directory server.    enable:Enable setting.    disable:Disable setting. | [optional] 
**server** | **str** | Host name or IP address of the Active Directory server. | [optional] 
**default_domain** | **str** | Default domain managed by this Active Directory server. | [optional] 
**port** | **int** | Port to communicate with this Active Directory server. | [optional] 
**user** | **str** | User name required to log into this Active Directory server. | [optional] 
**password** | **str** | Password required to log into this Active Directory server. | [optional] 
**ldap_server** | **str** | LDAP server name used in LDAP connection strings. | [optional] 
**logon_history** | **int** | Number of hours of logon history to keep, 0 means keep all history. | [optional] 
**polling_frequency** | **int** | Polling frequency (every 1 to 30 seconds). | [optional] 
**adgrp** | [**List[UserFssoPollingIdGet200ResponseAdgrpInner]**](UserFssoPollingIdGet200ResponseAdgrpInner.md) | LDAP Group Info. | [optional] 
**smbv1** | **str** | Enable/disable support of SMBv1 for Samba.    enable:Enable support of SMBv1 for Samba.    disable:Disable support of SMBv1 for Samba. | [optional] 
**smb_ntlmv1_auth** | **str** | Enable/disable support of NTLMv1 for Samba authentication.    enable:Enable support of NTLMv1 for Samba authentication.    disable:Disable support of NTLMv1 for Samba authentication. | [optional] 

## Example

```python
from microlab_fortinet.models.user_fsso_polling_id_get200_response import UserFssoPollingIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserFssoPollingIdGet200Response from a JSON string
user_fsso_polling_id_get200_response_instance = UserFssoPollingIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserFssoPollingIdGet200Response.to_json())

# convert the object into a dict
user_fsso_polling_id_get200_response_dict = user_fsso_polling_id_get200_response_instance.to_dict()
# create an instance of UserFssoPollingIdGet200Response from a dict
user_fsso_polling_id_get200_response_from_dict = UserFssoPollingIdGet200Response.from_dict(user_fsso_polling_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


