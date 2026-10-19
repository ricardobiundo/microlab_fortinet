# SystemAdminNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | User name. | [optional] 
**vdom** | [**List[SystemAdminNameGet200ResponseVdomInner]**](SystemAdminNameGet200ResponseVdomInner.md) | Virtual domain(s) that the administrator can access. | [optional] 
**remote_auth** | **str** | Enable/disable authentication using a remote RADIUS, LDAP, or TACACS+ server.    enable:Enable remote authentication.    disable:Disable remote authentication. | [optional] 
**remote_group** | **str** | User group name used for remote auth. | [optional] 
**wildcard** | **str** | Enable/disable wildcard RADIUS authentication.    enable:Enable username wildcard.    disable:Disable username wildcard. | [optional] 
**password** | **str** | Admin user password. | [optional] 
**peer_auth** | **str** | Set to enable peer certificate authentication (for HTTPS admin access).    enable:Enable peer.    disable:Disable peer. | [optional] 
**peer_group** | **str** | Name of peer group defined under config user group which has PKI members. Used for peer certificate authentication (for HTTPS admin access). | [optional] 
**trusthost1** | **str** | Any IPv4 address or subnet address and netmask from which the administrator can connect to the FortiGate unit. Default allows access from any IPv4 address. | [optional] 
**trusthost2** | **str** | Any IPv4 address or subnet address and netmask from which the administrator can connect to the FortiGate unit. Default allows access from any IPv4 address. | [optional] 
**trusthost3** | **str** | Any IPv4 address or subnet address and netmask from which the administrator can connect to the FortiGate unit. Default allows access from any IPv4 address. | [optional] 
**trusthost4** | **str** | Any IPv4 address or subnet address and netmask from which the administrator can connect to the FortiGate unit. Default allows access from any IPv4 address. | [optional] 
**trusthost5** | **str** | Any IPv4 address or subnet address and netmask from which the administrator can connect to the FortiGate unit. Default allows access from any IPv4 address. | [optional] 
**trusthost6** | **str** | Any IPv4 address or subnet address and netmask from which the administrator can connect to the FortiGate unit. Default allows access from any IPv4 address. | [optional] 
**trusthost7** | **str** | Any IPv4 address or subnet address and netmask from which the administrator can connect to the FortiGate unit. Default allows access from any IPv4 address. | [optional] 
**trusthost8** | **str** | Any IPv4 address or subnet address and netmask from which the administrator can connect to the FortiGate unit. Default allows access from any IPv4 address. | [optional] 
**trusthost9** | **str** | Any IPv4 address or subnet address and netmask from which the administrator can connect to the FortiGate unit. Default allows access from any IPv4 address. | [optional] 
**trusthost10** | **str** | Any IPv4 address or subnet address and netmask from which the administrator can connect to the FortiGate unit. Default allows access from any IPv4 address. | [optional] 
**ip6_trusthost1** | **str** | Any IPv6 address from which the administrator can connect to the FortiGate unit. Default allows access from any IPv6 address. | [optional] 
**ip6_trusthost2** | **str** | Any IPv6 address from which the administrator can connect to the FortiGate unit. Default allows access from any IPv6 address. | [optional] 
**ip6_trusthost3** | **str** | Any IPv6 address from which the administrator can connect to the FortiGate unit. Default allows access from any IPv6 address. | [optional] 
**ip6_trusthost4** | **str** | Any IPv6 address from which the administrator can connect to the FortiGate unit. Default allows access from any IPv6 address. | [optional] 
**ip6_trusthost5** | **str** | Any IPv6 address from which the administrator can connect to the FortiGate unit. Default allows access from any IPv6 address. | [optional] 
**ip6_trusthost6** | **str** | Any IPv6 address from which the administrator can connect to the FortiGate unit. Default allows access from any IPv6 address. | [optional] 
**ip6_trusthost7** | **str** | Any IPv6 address from which the administrator can connect to the FortiGate unit. Default allows access from any IPv6 address. | [optional] 
**ip6_trusthost8** | **str** | Any IPv6 address from which the administrator can connect to the FortiGate unit. Default allows access from any IPv6 address. | [optional] 
**ip6_trusthost9** | **str** | Any IPv6 address from which the administrator can connect to the FortiGate unit. Default allows access from any IPv6 address. | [optional] 
**ip6_trusthost10** | **str** | Any IPv6 address from which the administrator can connect to the FortiGate unit. Default allows access from any IPv6 address. | [optional] 
**accprofile** | **str** | Access profile for this administrator. Access profiles control administrator access to FortiGate features. | [optional] 
**allow_remove_admin_session** | **str** | Enable/disable allow admin session to be removed by privileged admin users.    enable:Enable allow-remove option.    disable:Disable allow-remove option. | [optional] 
**comments** | **str** | Comment. | [optional] 
**ssh_public_key1** | **str** | Public key of an SSH client. The client is authenticated without being asked for credentials. Create the public-private key pair in the SSH client application. | [optional] 
**ssh_public_key2** | **str** | Public key of an SSH client. The client is authenticated without being asked for credentials. Create the public-private key pair in the SSH client application. | [optional] 
**ssh_public_key3** | **str** | Public key of an SSH client. The client is authenticated without being asked for credentials. Create the public-private key pair in the SSH client application. | [optional] 
**ssh_certificate** | **str** | Select the certificate to be used by the FortiGate for authentication with an SSH client. | [optional] 
**schedule** | **str** | Firewall schedule used to restrict when the administrator can log in. No schedule means no restrictions. | [optional] 
**accprofile_override** | **str** | Enable to use the name of an access profile provided by the remote authentication server to control the FortiGate features that this administrator can access.    enable:Enable access profile override.    disable:Disable access profile override. | [optional] 
**vdom_override** | **str** | Enable to use the names of VDOMs provided by the remote authentication server to control the VDOMs that this administrator can access.    enable:Enable VDOM override.    disable:Disable VDOM override. | [optional] 
**password_expire** | **datetime** | Password expire time. | [optional] 
**force_password_change** | **str** | Enable/disable force password change on next login.    enable:Enable force password change on next login.    disable:Disable force password change on next login. | [optional] 
**two_factor** | **str** | Enable/disable two-factor authentication.    disable:Disable two-factor authentication.    fortitoken:Use FortiToken or FortiToken mobile two-factor authentication.    fortitoken-cloud:FortiToken Cloud Service.    email:Send a two-factor authentication code to the configured email-to email address.    sms:Send a two-factor authentication code to the configured sms-server and sms-phone. | [optional] 
**two_factor_authentication** | **str** | Authentication method by FortiToken Cloud.    fortitoken:FortiToken authentication.    email:Email one time password.    sms:SMS one time password. | [optional] 
**two_factor_notification** | **str** | Notification method for user activation by FortiToken Cloud.    email:Email notification for activation code.    sms:SMS notification for activation code. | [optional] 
**fortitoken** | **str** | This administrator&#39;s FortiToken serial number. | [optional] 
**email_to** | **str** | This administrator&#39;s email address. | [optional] 
**sms_server** | **str** | Send SMS messages using the FortiGuard SMS server or a custom server.    fortiguard:Send SMS by FortiGuard.    custom:Send SMS by custom server. | [optional] 
**sms_custom_server** | **str** | Custom SMS server to send SMS messages to. | [optional] 
**sms_phone** | **str** | Phone number on which the administrator receives SMS messages. | [optional] 
**guest_auth** | **str** | Enable/disable guest authentication.    disable:Disable guest authentication.    enable:Enable guest authentication. | [optional] 
**guest_usergroups** | [**List[SystemAdminNameGet200ResponseGuestUsergroupsInner]**](SystemAdminNameGet200ResponseGuestUsergroupsInner.md) | Select guest user groups. | [optional] 
**guest_lang** | **str** | Guest management portal language. | [optional] 
**status** | **str** | print admin status information | [optional] 
**list** | **str** | print admin list information | [optional] 

## Example

```python
from microlab_fortinet.models.system_admin_name_get200_response import SystemAdminNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAdminNameGet200Response from a JSON string
system_admin_name_get200_response_instance = SystemAdminNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAdminNameGet200Response.to_json())

# convert the object into a dict
system_admin_name_get200_response_dict = system_admin_name_get200_response_instance.to_dict()
# create an instance of SystemAdminNameGet200Response from a dict
system_admin_name_get200_response_from_dict = SystemAdminNameGet200Response.from_dict(system_admin_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


