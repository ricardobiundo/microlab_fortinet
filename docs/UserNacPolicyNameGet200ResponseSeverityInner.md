# UserNacPolicyNameGet200ResponseSeverityInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**severity_num** | **int** | Enter multiple severity levels, where 0 &#x3D; Info, 1 &#x3D; Low, ..., 4 &#x3D; Critical | [optional] 

## Example

```python
from microlab_fortinet.models.user_nac_policy_name_get200_response_severity_inner import UserNacPolicyNameGet200ResponseSeverityInner

# TODO update the JSON string below
json = "{}"
# create an instance of UserNacPolicyNameGet200ResponseSeverityInner from a JSON string
user_nac_policy_name_get200_response_severity_inner_instance = UserNacPolicyNameGet200ResponseSeverityInner.from_json(json)
# print the JSON string representation of the object
print(UserNacPolicyNameGet200ResponseSeverityInner.to_json())

# convert the object into a dict
user_nac_policy_name_get200_response_severity_inner_dict = user_nac_policy_name_get200_response_severity_inner_instance.to_dict()
# create an instance of UserNacPolicyNameGet200ResponseSeverityInner from a dict
user_nac_policy_name_get200_response_severity_inner_from_dict = UserNacPolicyNameGet200ResponseSeverityInner.from_dict(user_nac_policy_name_get200_response_severity_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


