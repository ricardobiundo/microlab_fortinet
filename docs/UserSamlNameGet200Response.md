# UserSamlNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | SAML server entry name. | [optional] 
**cert** | **str** | Certificate to sign SAML messages. | [optional] 
**entity_id** | **str** | SP entity ID. | [optional] 
**single_sign_on_url** | **str** | SP single sign-on URL. | [optional] 
**single_logout_url** | **str** | SP single logout URL. | [optional] 
**idp_entity_id** | **str** | IDP entity ID. | [optional] 
**idp_single_sign_on_url** | **str** | IDP single sign-on URL. | [optional] 
**idp_single_logout_url** | **str** | IDP single logout url. | [optional] 
**idp_cert** | **str** | IDP Certificate name. | [optional] 
**scim_client** | **str** | SCIM client name. | [optional] 
**scim_user_attr_type** | **str** | User attribute type used to match SCIM users (default &#x3D; user-name).    user-name:User name.    display-name:Display name.    external-id:External ID.    email:Email. | [optional] 
**scim_group_attr_type** | **str** | Group attribute type used to match SCIM groups (default &#x3D; display-name).    display-name:Display name.    external-id:External ID. | [optional] 
**user_name** | **str** | User name in assertion statement. | [optional] 
**group_name** | **str** | Group name in assertion statement. | [optional] 
**digest_method** | **str** | Digest method algorithm.    sha1:Digest Method Algorithm is SHA1.    sha256:Digest Method Algorithm is SHA256. | [optional] 
**require_signed_resp_and_asrt** | **str** | Require both response and assertion from IDP to be signed when FGT acts as SP (default &#x3D; disable).    enable:Both response and assertion must be signed and valid.    disable:At least one of response or assertion must be signed and valid. | [optional] 
**limit_relaystate** | **str** | Enable/disable limiting of relay-state parameter when it exceeds SAML 2.0 specification limits (80 bytes).    enable:Enable limiting of relay-state parameter when it exceeds SAML 2.0 specification limits (80 bytes).    disable:Disable limiting of relay-state parameter when it exceeds SAML 2.0 specification limits (80 bytes). | [optional] 
**clock_tolerance** | **int** | Clock skew tolerance in seconds (0 - 300, default &#x3D; 15, 0 &#x3D; no tolerance). | [optional] 
**adfs_claim** | **str** | Enable/disable ADFS Claim for user/group attribute in assertion statement (default &#x3D; disable).    enable:Enable ADFS Claim for user/group attribute in assertion statement.    disable:Disable ADFS Claim for user/group attribute in assertion statement. | [optional] 
**user_claim_type** | **str** | User name claim in assertion statement.    email:E-mail address of the user.    given-name:Given name of the user.    name:Unique name of the user.    upn:User principal name (UPN) of the user.    common-name:Common name of the user.    email-adfs-1x:E-mail address of the user when interoperating with AD FS 1.1 or ADFS 1.0.    group:Group that the user is a member of.    upn-adfs-1x:User principal name (UPN) of the user.    role:Role that the user has.    sur-name:Surname of the user    ppid:Private identifier of the user.    name-identifier:SAML name identifier of the user.    authentication-method:Method used to authenticate the user.    deny-only-group-sid:Deny-only group SID of the user.    deny-only-primary-sid:Deny-only primary SID of the user.    deny-only-primary-group-sid:Deny-only primary group SID of the user.    group-sid:Group SID of the user.    primary-group-sid:Primary group SID of the user.    primary-sid:Primary SID of the user.    windows-account-name:Domain account name of the user in the form of &lt;domain&gt;\\&lt;user&gt;. | [optional] 
**group_claim_type** | **str** | Group claim in assertion statement.    email:E-mail address of the user.    given-name:Given name of the user.    name:Unique name of the user.    upn:User principal name (UPN) of the user.    common-name:Common name of the user.    email-adfs-1x:E-mail address of the user when interoperating with AD FS 1.1 or ADFS 1.0.    group:Group that the user is a member of.    upn-adfs-1x:User principal name (UPN) of the user.    role:Role that the user has.    sur-name:Surname of the user    ppid:Private identifier of the user.    name-identifier:SAML name identifier of the user.    authentication-method:Method used to authenticate the user.    deny-only-group-sid:Deny-only group SID of the user.    deny-only-primary-sid:Deny-only primary SID of the user.    deny-only-primary-group-sid:Deny-only primary group SID of the user.    group-sid:Group SID of the user.    primary-group-sid:Primary group SID of the user.    primary-sid:Primary SID of the user.    windows-account-name:Domain account name of the user in the form of &lt;domain&gt;\\&lt;user&gt;. | [optional] 
**reauth** | **str** | Enable/disable signalling of IDP to force user re-authentication (default &#x3D; disable).    enable:Enable signalling of IDP to force user re-authentication.    disable:Disable signalling of IDP to force user re-authentication. | [optional] 

## Example

```python
from microlab_fortinet.models.user_saml_name_get200_response import UserSamlNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserSamlNameGet200Response from a JSON string
user_saml_name_get200_response_instance = UserSamlNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserSamlNameGet200Response.to_json())

# convert the object into a dict
user_saml_name_get200_response_dict = user_saml_name_get200_response_instance.to_dict()
# create an instance of UserSamlNameGet200Response from a dict
user_saml_name_get200_response_from_dict = UserSamlNameGet200Response.from_dict(user_saml_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


