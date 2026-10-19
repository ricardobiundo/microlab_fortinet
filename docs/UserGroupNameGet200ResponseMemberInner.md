# UserGroupNameGet200ResponseMemberInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Group member name. | [optional] 

## Example

```python
from microlab_fortinet.models.user_group_name_get200_response_member_inner import UserGroupNameGet200ResponseMemberInner

# TODO update the JSON string below
json = "{}"
# create an instance of UserGroupNameGet200ResponseMemberInner from a JSON string
user_group_name_get200_response_member_inner_instance = UserGroupNameGet200ResponseMemberInner.from_json(json)
# print the JSON string representation of the object
print(UserGroupNameGet200ResponseMemberInner.to_json())

# convert the object into a dict
user_group_name_get200_response_member_inner_dict = user_group_name_get200_response_member_inner_instance.to_dict()
# create an instance of UserGroupNameGet200ResponseMemberInner from a dict
user_group_name_get200_response_member_inner_from_dict = UserGroupNameGet200ResponseMemberInner.from_dict(user_group_name_get200_response_member_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


