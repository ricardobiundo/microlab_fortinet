# UserLdapNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | LDAP server entry name. | [optional] 
**server** | **str** | LDAP server CN domain name or IP. | [optional] 
**secondary_server** | **str** | Secondary LDAP server CN domain name or IP. | [optional] 
**tertiary_server** | **str** | Tertiary LDAP server CN domain name or IP. | [optional] 
**status_ttl** | **int** | Time for which server reachability is cached so that when a server is unreachable, it will not be retried for at least this period of time (0 &#x3D; cache disabled, default &#x3D; 300). | [optional] 
**server_identity_check** | **str** | Enable/disable LDAP server identity check (verify server domain name/IP address against the server certificate).    enable:Enable server identity check.    disable:Disable server identity check. | [optional] 
**source_ip** | **str** | FortiGate IP address to be used for communication with the LDAP server. | [optional] 
**source_ip_interface** | **str** | Source interface for communication with the LDAP server. | [optional] 
**source_port** | **int** | Source port to be used for communication with the LDAP server. | [optional] 
**cnid** | **str** | Common name identifier for the LDAP server. The common name identifier for most LDAP servers is \&quot;cn\&quot;. | [optional] 
**dn** | **str** | Distinguished name used to look up entries on the LDAP server. | [optional] 
**type** | **str** | Authentication type for LDAP searches.    simple:Simple password authentication without search.    anonymous:Bind using anonymous user search.    regular:Bind using username/password and then search. | [optional] 
**two_factor** | **str** | Enable/disable two-factor authentication.    disable:disable two-factor authentication.    fortitoken-cloud:FortiToken Cloud Service. | [optional] 
**two_factor_authentication** | **str** | Authentication method by FortiToken Cloud.    fortitoken:FortiToken authentication.    email:Email one time password.    sms:SMS one time password. | [optional] 
**two_factor_notification** | **str** | Notification method for user activation by FortiToken Cloud.    email:Email notification for activation code.    sms:SMS notification for activation code. | [optional] 
**two_factor_filter** | **str** | Filter used to synchronize users to FortiToken Cloud. | [optional] 
**username** | **str** | Username (full DN) for initial binding. | [optional] 
**password** | **str** | Password for initial binding. | [optional] 
**group_member_check** | **str** | Group member checking methods.    user-attr:User attribute checking.    group-object:Group object checking.    posix-group-object:POSIX group object checking. | [optional] 
**group_search_base** | **str** | Search base used for group searching. | [optional] 
**group_object_filter** | **str** | Filter used for group searching. | [optional] 
**group_filter** | **str** | Filter used for group matching. | [optional] 
**secure** | **str** | Port to be used for authentication.    disable:No SSL.    starttls:Use StartTLS.    ldaps:Use LDAPS. | [optional] 
**ssl_min_proto_version** | **str** | Minimum supported protocol version for SSL/TLS connections (default is to follow system global setting).    default:Follow system global setting.    SSLv3:SSLv3.    TLSv1:TLSv1.    TLSv1-1:TLSv1.1.    TLSv1-2:TLSv1.2.    TLSv1-3:TLSv1.3. | [optional] 
**ca_cert** | **str** | CA certificate name. | [optional] 
**port** | **int** | Port to be used for communication with the LDAP server (default &#x3D; 389). | [optional] 
**password_expiry_warning** | **str** | Enable/disable password expiry warnings.    enable:Enable password expiry warnings.    disable:Disable password expiry warnings. | [optional] 
**password_renewal** | **str** | Enable/disable online password renewal.    enable:Enable online password renewal.    disable:Disable online password renewal. | [optional] 
**member_attr** | **str** | Name of attribute from which to get group membership. | [optional] 
**account_key_processing** | **str** | Account key processing operation. The FortiGate will keep either the whole domain or strip the domain from the subject identity.    same:Same as subject identity field.    strip:Strip domain string from subject identity field. | [optional] 
**account_key_cert_field** | **str** | Define subject identity field in certificate for user access right checking.    othername:Other name in SAN.    rfc822name:RFC822 email address in SAN.    dnsname:DNS name in SAN.    cn:CN in subject. | [optional] 
**account_key_filter** | **str** | Account key filter, using the UPN as the search filter. | [optional] 
**search_type** | **str** | Search type.    recursive:Recursively retrieve the user-group chain information of a user in a particular Microsoft AD domain. | [optional] 
**client_cert_auth** | **str** | Enable/disable using client certificate for TLS authentication.    enable:Enable using client certificate for TLS authentication.    disable:Disable using client certificate for TLS authentication. | [optional] 
**client_cert** | **str** | Client certificate name. | [optional] 
**obtain_user_info** | **str** | Enable/disable obtaining of user information.    enable:Enable obtaining of user information.    disable:Disable obtaining of user information. | [optional] 
**user_info_exchange_server** | **str** | MS Exchange server from which to fetch user information. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 
**antiphish** | **str** | Enable/disable AntiPhishing credential backend.    enable:Enable AntiPhishing credential backend.    disable:Disable AntiPhishing credential backend. | [optional] 
**password_attr** | **str** | Name of attribute to get password hash. | [optional] 

## Example

```python
from microlab_fortinet.models.user_ldap_name_get200_response import UserLdapNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserLdapNameGet200Response from a JSON string
user_ldap_name_get200_response_instance = UserLdapNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserLdapNameGet200Response.to_json())

# convert the object into a dict
user_ldap_name_get200_response_dict = user_ldap_name_get200_response_instance.to_dict()
# create an instance of UserLdapNameGet200Response from a dict
user_ldap_name_get200_response_from_dict = UserLdapNameGet200Response.from_dict(user_ldap_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


