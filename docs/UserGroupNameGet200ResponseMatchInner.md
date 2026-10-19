# UserGroupNameGet200ResponseMatchInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**server_name** | **str** | Name of remote auth server. | [optional] 
**group_name** | **str** | Name of matching user or group on remote authentication server or SCIM. | [optional] 

## Example

```python
from microlab_fortinet.models.user_group_name_get200_response_match_inner import UserGroupNameGet200ResponseMatchInner

# TODO update the JSON string below
json = "{}"
# create an instance of UserGroupNameGet200ResponseMatchInner from a JSON string
user_group_name_get200_response_match_inner_instance = UserGroupNameGet200ResponseMatchInner.from_json(json)
# print the JSON string representation of the object
print(UserGroupNameGet200ResponseMatchInner.to_json())

# convert the object into a dict
user_group_name_get200_response_match_inner_dict = user_group_name_get200_response_match_inner_instance.to_dict()
# create an instance of UserGroupNameGet200ResponseMatchInner from a dict
user_group_name_get200_response_match_inner_from_dict = UserGroupNameGet200ResponseMatchInner.from_dict(user_group_name_get200_response_match_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


