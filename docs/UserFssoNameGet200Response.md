# UserFssoNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**type** | **str** | Server type.    default:All other unspecified types of servers.    fortinac:FortiNAC server. | [optional] 
**server** | **str** | Domain name or IP address of the first FSSO collector agent. | [optional] 
**port** | **int** | Port of the first FSSO collector agent. | [optional] 
**password** | **str** | Password of the first FSSO collector agent. | [optional] 
**server2** | **str** | Domain name or IP address of the second FSSO collector agent. | [optional] 
**port2** | **int** | Port of the second FSSO collector agent. | [optional] 
**password2** | **str** | Password of the second FSSO collector agent. | [optional] 
**server3** | **str** | Domain name or IP address of the third FSSO collector agent. | [optional] 
**port3** | **int** | Port of the third FSSO collector agent. | [optional] 
**password3** | **str** | Password of the third FSSO collector agent. | [optional] 
**server4** | **str** | Domain name or IP address of the fourth FSSO collector agent. | [optional] 
**port4** | **int** | Port of the fourth FSSO collector agent. | [optional] 
**password4** | **str** | Password of the fourth FSSO collector agent. | [optional] 
**server5** | **str** | Domain name or IP address of the fifth FSSO collector agent. | [optional] 
**port5** | **int** | Port of the fifth FSSO collector agent. | [optional] 
**password5** | **str** | Password of the fifth FSSO collector agent. | [optional] 
**logon_timeout** | **int** | Interval in minutes to keep logons after FSSO server down. | [optional] 
**ldap_server** | **str** | LDAP server to get group information. | [optional] 
**group_poll_interval** | **int** | Interval in minutes within to fetch groups from FSSO server, or unset to disable. | [optional] 
**ldap_poll** | **str** | Enable/disable automatic fetching of groups from LDAP server.    enable:Enable automatic fetching of groups from LDAP server.    disable:Disable automatic fetching of groups from LDAP server. | [optional] 
**ldap_poll_interval** | **int** | Interval in minutes within to fetch groups from LDAP server. | [optional] 
**ldap_poll_filter** | **str** | Filter used to fetch groups. | [optional] 
**user_info_server** | **str** | LDAP server to get user information. | [optional] 
**ssl** | **str** | Enable/disable use of SSL.    enable:Enable use of SSL.    disable:Disable use of SSL. | [optional] 
**sni** | **str** | Server Name Indication. | [optional] 
**ssl_server_host_ip_check** | **str** | Enable/disable server host/IP verification.    enable:Enable server host/IP verification.    disable:Disable server host/IP verification. | [optional] 
**ssl_trusted_cert** | **str** | Trusted server certificate or CA certificate. | [optional] 
**source_ip** | **str** | Source IP for communications to FSSO agent. | [optional] 
**source_ip6** | **str** | IPv6 source for communications to FSSO agent. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.user_fsso_name_get200_response import UserFssoNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserFssoNameGet200Response from a JSON string
user_fsso_name_get200_response_instance = UserFssoNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserFssoNameGet200Response.to_json())

# convert the object into a dict
user_fsso_name_get200_response_dict = user_fsso_name_get200_response_instance.to_dict()
# create an instance of UserFssoNameGet200Response from a dict
user_fsso_name_get200_response_from_dict = UserFssoNameGet200Response.from_dict(user_fsso_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


