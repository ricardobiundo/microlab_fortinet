# UserGroupNameGet200ResponseGuestInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Guest ID. | [optional] 
**user_id** | **str** | Guest ID. | [optional] 
**name** | **str** | Guest name. | [optional] 
**password** | **str** | Guest password. | [optional] 
**mobile_phone** | **str** | Mobile phone. | [optional] 
**sponsor** | **str** | Set the action for the sponsor guest user field. | [optional] 
**company** | **str** | Set the action for the company guest user field. | [optional] 
**email** | **str** | Email. | [optional] 
**expiration** | **str** | Expire time. | [optional] 
**comment** | **str** | Comment. | [optional] 

## Example

```python
from microlab_fortinet.models.user_group_name_get200_response_guest_inner import UserGroupNameGet200ResponseGuestInner

# TODO update the JSON string below
json = "{}"
# create an instance of UserGroupNameGet200ResponseGuestInner from a JSON string
user_group_name_get200_response_guest_inner_instance = UserGroupNameGet200ResponseGuestInner.from_json(json)
# print the JSON string representation of the object
print(UserGroupNameGet200ResponseGuestInner.to_json())

# convert the object into a dict
user_group_name_get200_response_guest_inner_dict = user_group_name_get200_response_guest_inner_instance.to_dict()
# create an instance of UserGroupNameGet200ResponseGuestInner from a dict
user_group_name_get200_response_guest_inner_from_dict = UserGroupNameGet200ResponseGuestInner.from_dict(user_group_name_get200_response_guest_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


