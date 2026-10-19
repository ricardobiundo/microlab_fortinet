# UserQuarantineGet200ResponseTargetsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**entry** | **str** | Quarantine entry name. | [optional] 
**description** | **str** | Description for the quarantine entry. | [optional] 
**macs** | [**List[UserQuarantineGet200ResponseTargetsInnerMacsInner]**](UserQuarantineGet200ResponseTargetsInnerMacsInner.md) | Quarantine MACs. | [optional] 

## Example

```python
from microlab_fortinet.models.user_quarantine_get200_response_targets_inner import UserQuarantineGet200ResponseTargetsInner

# TODO update the JSON string below
json = "{}"
# create an instance of UserQuarantineGet200ResponseTargetsInner from a JSON string
user_quarantine_get200_response_targets_inner_instance = UserQuarantineGet200ResponseTargetsInner.from_json(json)
# print the JSON string representation of the object
print(UserQuarantineGet200ResponseTargetsInner.to_json())

# convert the object into a dict
user_quarantine_get200_response_targets_inner_dict = user_quarantine_get200_response_targets_inner_instance.to_dict()
# create an instance of UserQuarantineGet200ResponseTargetsInner from a dict
user_quarantine_get200_response_targets_inner_from_dict = UserQuarantineGet200ResponseTargetsInner.from_dict(user_quarantine_get200_response_targets_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


