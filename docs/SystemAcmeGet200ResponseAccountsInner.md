# SystemAcmeGet200ResponseAccountsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Account id. | [optional] 
**status** | **str** | Account status. | [optional] 
**url** | **str** | Account url. | [optional] 
**ca_url** | **str** | Account ca_url. | [optional] 
**email** | **str** | Account email. | [optional] 
**eab_key_id** | **str** | External Acccount Binding Key ID. | [optional] 
**eab_key_hmac** | **str** | External Acccount Binding Key HMAC. | [optional] 
**privatekey** | **str** | Account Private Key. | [optional] 

## Example

```python
from microlab_fortinet.models.system_acme_get200_response_accounts_inner import SystemAcmeGet200ResponseAccountsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAcmeGet200ResponseAccountsInner from a JSON string
system_acme_get200_response_accounts_inner_instance = SystemAcmeGet200ResponseAccountsInner.from_json(json)
# print the JSON string representation of the object
print(SystemAcmeGet200ResponseAccountsInner.to_json())

# convert the object into a dict
system_acme_get200_response_accounts_inner_dict = system_acme_get200_response_accounts_inner_instance.to_dict()
# create an instance of SystemAcmeGet200ResponseAccountsInner from a dict
system_acme_get200_response_accounts_inner_from_dict = SystemAcmeGet200ResponseAccountsInner.from_dict(system_acme_get200_response_accounts_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


