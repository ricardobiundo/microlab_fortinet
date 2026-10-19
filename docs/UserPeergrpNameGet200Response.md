# UserPeergrpNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Peer group name. | [optional] 
**member** | [**List[UserPeergrpNameGet200ResponseMemberInner]**](UserPeergrpNameGet200ResponseMemberInner.md) | Peer group members. | [optional] 

## Example

```python
from microlab_fortinet.models.user_peergrp_name_get200_response import UserPeergrpNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserPeergrpNameGet200Response from a JSON string
user_peergrp_name_get200_response_instance = UserPeergrpNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserPeergrpNameGet200Response.to_json())

# convert the object into a dict
user_peergrp_name_get200_response_dict = user_peergrp_name_get200_response_instance.to_dict()
# create an instance of UserPeergrpNameGet200Response from a dict
user_peergrp_name_get200_response_from_dict = UserPeergrpNameGet200Response.from_dict(user_peergrp_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


