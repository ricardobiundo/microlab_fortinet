# UserLocalNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Local user name. | [optional] 
**id** | **int** | User ID. | [optional] 
**status** | **str** | Enable/disable allowing the local user to authenticate with the FortiGate unit.    enable:Enable user.    disable:Disable user. | [optional] 
**type** | **str** | Authentication method.    password:Password authentication.    radius:RADIUS server authentication.    tacacs+:TACACS+ server authentication.    ldap:LDAP server authentication.    saml:SAML server authentication. | [optional] 
**passwd** | **str** | User&#39;s password. | [optional] 
**ldap_server** | **str** | Name of LDAP server with which the user must authenticate. | [optional] 
**radius_server** | **str** | Name of RADIUS server with which the user must authenticate. | [optional] 
**tacacs_server** | **str** | Name of TACACS+ server with which the user must authenticate. | [optional] 
**saml_server** | **str** | Name of SAML server with which the user must authenticate. | [optional] 
**two_factor** | **str** | Enable/disable two-factor authentication.    disable:disable    fortitoken:FortiToken    fortitoken-cloud:FortiToken Cloud Service.    email:Email authentication code.    sms:SMS authentication code. | [optional] 
**two_factor_authentication** | **str** | Authentication method by FortiToken Cloud.    fortitoken:FortiToken authentication.    email:Email one time password.    sms:SMS one time password. | [optional] 
**two_factor_notification** | **str** | Notification method for user activation by FortiToken Cloud.    email:Email notification for activation code.    sms:SMS notification for activation code. | [optional] 
**fortitoken** | **str** | Two-factor recipient&#39;s FortiToken serial number. | [optional] 
**email_to** | **str** | Two-factor recipient&#39;s email address. | [optional] 
**sms_server** | **str** | Send SMS through FortiGuard or other external server.    fortiguard:Send SMS by FortiGuard.    custom:Send SMS by custom server. | [optional] 
**sms_custom_server** | **str** | Two-factor recipient&#39;s SMS server. | [optional] 
**sms_phone** | **str** | Two-factor recipient&#39;s mobile phone number. | [optional] 
**passwd_policy** | **str** | Password policy to apply to this user, as defined in config user password-policy. | [optional] 
**passwd_time** | **str** | Time of the last password update. | [optional] 
**authtimeout** | **int** | Time in minutes before the authentication timeout for a user is reached. | [optional] 
**workstation** | **str** | Name of the remote user workstation, if you want to limit the user to authenticate only from a particular workstation. | [optional] 
**auth_concurrent_override** | **str** | Enable/disable overriding the policy-auth-concurrent under config system global.    enable:Enable auth-concurrent-override.    disable:Disable auth-concurrent-override. | [optional] 
**auth_concurrent_value** | **int** | Maximum number of concurrent logins permitted from the same user. | [optional] 
**ppk_secret** | **str** | IKEv2 Postquantum Preshared Key (ASCII string or hexadecimal encoded with a leading 0x). | [optional] 
**ppk_identity** | **str** | IKEv2 Postquantum Preshared Key Identity. | [optional] 
**qkd_profile** | **str** | Quantum Key Distribution (QKD) profile. | [optional] 
**username_sensitivity** | **str** | Enable/disable case and accent sensitivity when performing username matching (accents are stripped and case is ignored when disabled).    disable:Ignore case and accents. Username at prompt not required to match case or accents.    enable:Do not ignore case and accents. Username at prompt must be an exact match. | [optional] 

## Example

```python
from microlab_fortinet.models.user_local_name_get200_response import UserLocalNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserLocalNameGet200Response from a JSON string
user_local_name_get200_response_instance = UserLocalNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserLocalNameGet200Response.to_json())

# convert the object into a dict
user_local_name_get200_response_dict = user_local_name_get200_response_instance.to_dict()
# create an instance of UserLocalNameGet200Response from a dict
user_local_name_get200_response_from_dict = UserLocalNameGet200Response.from_dict(user_local_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


