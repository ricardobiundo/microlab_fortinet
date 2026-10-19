# UserPeerNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Peer name. | [optional] 
**mandatory_ca_verify** | **str** | Determine what happens to the peer if the CA certificate is not installed. Disable to automatically consider the peer certificate as valid.    enable:Enable setting.    disable:Disable setting. | [optional] 
**ca** | **str** | Name of the CA certificate. | [optional] 
**subject** | **str** | Peer certificate name constraints. | [optional] 
**cn** | **str** | Peer certificate common name. | [optional] 
**cn_type** | **str** | Peer certificate common name type.    string:Normal string.    email:Email address.    FQDN:Fully Qualified Domain Name.    ipv4:IPv4 address.    ipv6:IPv6 address. | [optional] 
**mfa_mode** | **str** | MFA mode for remote peer authentication/authorization.    none:None.    password:Specified username/password.    subject-identity:Subject identity extracted from certificate. | [optional] 
**mfa_server** | **str** | Name of a remote authenticator. Performs client access right check. | [optional] 
**mfa_username** | **str** | Unified username for remote authentication. | [optional] 
**mfa_password** | **str** | Unified password for remote authentication. This field may be left empty when RADIUS authentication is used, in which case the FortiGate will use the RADIUS username as a password.  | [optional] 
**ocsp_override_server** | **str** | Online Certificate Status Protocol (OCSP) server for certificate retrieval. | [optional] 
**two_factor** | **str** | Enable/disable two-factor authentication, applying certificate and password-based authentication.    enable:Enable 2-factor authentication.    disable:Disable 2-factor authentication. | [optional] 
**passwd** | **str** | Peer&#39;s password used for two-factor authentication. | [optional] 

## Example

```python
from microlab_fortinet.models.user_peer_name_get200_response import UserPeerNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserPeerNameGet200Response from a JSON string
user_peer_name_get200_response_instance = UserPeerNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserPeerNameGet200Response.to_json())

# convert the object into a dict
user_peer_name_get200_response_dict = user_peer_name_get200_response_instance.to_dict()
# create an instance of UserPeerNameGet200Response from a dict
user_peer_name_get200_response_from_dict = UserPeerNameGet200Response.from_dict(user_peer_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


