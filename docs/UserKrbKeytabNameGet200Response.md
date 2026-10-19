# UserKrbKeytabNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Kerberos keytab entry name. | [optional] 
**pac_data** | **str** | Enable/disable parsing PAC data in the ticket.    enable:Enable parsing PAC data in the ticket.    disable:Disable parsing PAC data in the ticket. | [optional] 
**principal** | **str** | Kerberos service principal. For example, HTTP/myfgt.example.com@example.com. | [optional] 
**ldap_server** | [**List[UserDomainControllerNameGet200ResponseLdapServerInner]**](UserDomainControllerNameGet200ResponseLdapServerInner.md) | LDAP server name(s). | [optional] 
**keytab** | **str** | Base64 coded keytab file containing a pre-shared key. | [optional] 

## Example

```python
from microlab_fortinet.models.user_krb_keytab_name_get200_response import UserKrbKeytabNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserKrbKeytabNameGet200Response from a JSON string
user_krb_keytab_name_get200_response_instance = UserKrbKeytabNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserKrbKeytabNameGet200Response.to_json())

# convert the object into a dict
user_krb_keytab_name_get200_response_dict = user_krb_keytab_name_get200_response_instance.to_dict()
# create an instance of UserKrbKeytabNameGet200Response from a dict
user_krb_keytab_name_get200_response_from_dict = UserKrbKeytabNameGet200Response.from_dict(user_krb_keytab_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


