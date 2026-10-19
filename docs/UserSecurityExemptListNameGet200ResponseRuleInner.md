# UserSecurityExemptListNameGet200ResponseRuleInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**srcaddr** | [**List[UserSecurityExemptListNameGet200ResponseRuleInnerSrcaddrInner]**](UserSecurityExemptListNameGet200ResponseRuleInnerSrcaddrInner.md) | Source addresses or address groups. | [optional] 
**dstaddr** | [**List[UserSecurityExemptListNameGet200ResponseRuleInnerSrcaddrInner]**](UserSecurityExemptListNameGet200ResponseRuleInnerSrcaddrInner.md) | Destination addresses or address groups. | [optional] 
**service** | [**List[UserSecurityExemptListNameGet200ResponseRuleInnerServiceInner]**](UserSecurityExemptListNameGet200ResponseRuleInnerServiceInner.md) | Destination services. | [optional] 

## Example

```python
from microlab_fortinet.models.user_security_exempt_list_name_get200_response_rule_inner import UserSecurityExemptListNameGet200ResponseRuleInner

# TODO update the JSON string below
json = "{}"
# create an instance of UserSecurityExemptListNameGet200ResponseRuleInner from a JSON string
user_security_exempt_list_name_get200_response_rule_inner_instance = UserSecurityExemptListNameGet200ResponseRuleInner.from_json(json)
# print the JSON string representation of the object
print(UserSecurityExemptListNameGet200ResponseRuleInner.to_json())

# convert the object into a dict
user_security_exempt_list_name_get200_response_rule_inner_dict = user_security_exempt_list_name_get200_response_rule_inner_instance.to_dict()
# create an instance of UserSecurityExemptListNameGet200ResponseRuleInner from a dict
user_security_exempt_list_name_get200_response_rule_inner_from_dict = UserSecurityExemptListNameGet200ResponseRuleInner.from_dict(user_security_exempt_list_name_get200_response_rule_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


