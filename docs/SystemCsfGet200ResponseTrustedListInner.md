# SystemCsfGet200ResponseTrustedListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**authorization_type** | **str** | Authorization type.    serial:Verify downstream by serial number.    certificate:Verify downstream by certificate. | [optional] 
**serial** | **str** | Serial. | [optional] 
**certificate** | **str** | Certificate. | [optional] 
**action** | **str** | Security fabric authorization action.    accept:Accept authorization request.    deny:Deny authorization request. | [optional] 
**ha_members** | **str** | HA members. | [optional] 
**downstream_authorization** | **str** | Trust authorizations by this node&#39;s administrator.    enable:Enable downstream authorization.    disable:Disable downstream authorization. | [optional] 
**index** | **int** | Index of the downstream in tree. | [optional] 

## Example

```python
from microlab_fortinet.models.system_csf_get200_response_trusted_list_inner import SystemCsfGet200ResponseTrustedListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemCsfGet200ResponseTrustedListInner from a JSON string
system_csf_get200_response_trusted_list_inner_instance = SystemCsfGet200ResponseTrustedListInner.from_json(json)
# print the JSON string representation of the object
print(SystemCsfGet200ResponseTrustedListInner.to_json())

# convert the object into a dict
system_csf_get200_response_trusted_list_inner_dict = system_csf_get200_response_trusted_list_inner_instance.to_dict()
# create an instance of SystemCsfGet200ResponseTrustedListInner from a dict
system_csf_get200_response_trusted_list_inner_from_dict = SystemCsfGet200ResponseTrustedListInner.from_dict(system_csf_get200_response_trusted_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


