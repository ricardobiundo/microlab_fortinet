# UserSettingGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth_type** | **str** | Supported firewall policy authentication protocols/methods.    http:Allow HTTP authentication.    https:Allow HTTPS authentication.    ftp:Allow FTP authentication.    telnet:Allow TELNET authentication. | [optional] 
**auth_cert** | **str** | HTTPS server certificate for policy authentication. | [optional] 
**auth_ca_cert** | **str** | HTTPS CA certificate for policy authentication. | [optional] 
**auth_secure_http** | **str** | Enable/disable redirecting HTTP user authentication to more secure HTTPS.    enable:Enable setting.    disable:Disable setting. | [optional] 
**auth_http_basic** | **str** | Enable/disable use of HTTP basic authentication for identity-based firewall policies.    enable:Enable setting.    disable:Disable setting. | [optional] 
**auth_ssl_allow_renegotiation** | **str** | Allow/forbid SSL re-negotiation for HTTPS authentication.    enable:Allow SSL re-negotiation.    disable:Forbid SSL re-negotiation. | [optional] 
**auth_src_mac** | **str** | Enable/disable source MAC for user identity.    enable:Enable source MAC for user identity.    disable:Disable source MAC for user identity. | [optional] 
**auth_on_demand** | **str** | Always/implicitly trigger firewall authentication on demand.    always:Always trigger firewall authentication on demand.    implicitly:Implicitly trigger firewall authentication on demand. | [optional] 
**auth_timeout** | **int** | Time in minutes before the firewall user authentication timeout requires the user to re-authenticate. | [optional] 
**auth_timeout_type** | **str** | Control if authenticated users have to login again after a hard timeout, after an idle timeout, or after a session timeout.    idle-timeout:Idle timeout.    hard-timeout:Hard timeout.    new-session:New session timeout. | [optional] 
**auth_portal_timeout** | **int** | Time in minutes before captive portal user have to re-authenticate (1 - 30 min, default 3 min). | [optional] 
**radius_ses_timeout_act** | **str** | Set the RADIUS session timeout to a hard timeout or to ignore RADIUS server session timeouts.    hard-timeout:Use session timeout from RADIUS as hard-timeout.    ignore-timeout:Ignore session timeout from RADIUS. | [optional] 
**auth_blackout_time** | **int** | Time in seconds an IP address is denied access after failing to authenticate five times within one minute. | [optional] 
**auth_invalid_max** | **int** | Maximum number of failed authentication attempts before the user is blocked. | [optional] 
**auth_lockout_threshold** | **int** | Maximum number of failed login attempts before login lockout is triggered. | [optional] 
**auth_lockout_duration** | **int** | Lockout period in seconds after too many login failures. | [optional] 
**per_policy_disclaimer** | **str** | Enable/disable per policy disclaimer.    enable:Enable per policy disclaimer.    disable:Disable per policy disclaimer. | [optional] 
**auth_ports** | [**List[UserSettingGet200ResponseAuthPortsInner]**](UserSettingGet200ResponseAuthPortsInner.md) | Set up non-standard ports for authentication with HTTP, HTTPS, FTP, and TELNET. | [optional] 
**auth_ssl_min_proto_version** | **str** | Minimum supported protocol version for SSL/TLS connections (default is to follow system global setting).    default:Follow system global setting.    SSLv3:SSLv3.    TLSv1:TLSv1.    TLSv1-1:TLSv1.1.    TLSv1-2:TLSv1.2.    TLSv1-3:TLSv1.3. | [optional] 
**auth_ssl_max_proto_version** | **str** | Maximum supported protocol version for SSL/TLS connections (default is no limit).    sslv3:SSLv3.    tlsv1:TLSv1.    tlsv1-1:TLSv1.1.    tlsv1-2:TLSv1.2.    tlsv1-3:TLSv1.3. | [optional] 
**auth_ssl_sigalgs** | **str** | Set signature algorithms related to HTTPS authentication (affects TLS version &lt;&#x3D; 1.2 only, default is to enable all).    no-rsa-pss:Disable RSA-PSS signature algorithms for HTTPS authentication.    all:Enable all supported signature algorithms for HTTPS authentication. | [optional] 
**default_user_password_policy** | **str** | Default password policy to apply to all local users unless otherwise specified, as defined in config user password-policy. | [optional] 
**cors** | **str** | Enable/disable allowed origins white list for CORS.    disable:Disable allowed origins white list for CORS.    enable:Enable allowed origins white list for CORS. | [optional] 
**cors_allowed_origins** | [**List[UserSettingGet200ResponseCorsAllowedOriginsInner]**](UserSettingGet200ResponseCorsAllowedOriginsInner.md) | Allowed origins white list for CORS. | [optional] 

## Example

```python
from microlab_fortinet.models.user_setting_get200_response import UserSettingGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserSettingGet200Response from a JSON string
user_setting_get200_response_instance = UserSettingGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserSettingGet200Response.to_json())

# convert the object into a dict
user_setting_get200_response_dict = user_setting_get200_response_instance.to_dict()
# create an instance of UserSettingGet200Response from a dict
user_setting_get200_response_from_dict = UserSettingGet200Response.from_dict(user_setting_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


