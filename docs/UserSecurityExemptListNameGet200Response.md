# UserSecurityExemptListNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the exempt list. | [optional] 
**description** | **str** | Description. | [optional] 
**rule** | [**List[UserSecurityExemptListNameGet200ResponseRuleInner]**](UserSecurityExemptListNameGet200ResponseRuleInner.md) | Configure rules for exempting users from captive portal authentication. | [optional] 

## Example

```python
from microlab_fortinet.models.user_security_exempt_list_name_get200_response import UserSecurityExemptListNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserSecurityExemptListNameGet200Response from a JSON string
user_security_exempt_list_name_get200_response_instance = UserSecurityExemptListNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserSecurityExemptListNameGet200Response.to_json())

# convert the object into a dict
user_security_exempt_list_name_get200_response_dict = user_security_exempt_list_name_get200_response_instance.to_dict()
# create an instance of UserSecurityExemptListNameGet200Response from a dict
user_security_exempt_list_name_get200_response_from_dict = UserSecurityExemptListNameGet200Response.from_dict(user_security_exempt_list_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


