# SwitchControllerAclGroupNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Group name. | [optional] 
**ingress** | [**List[SwitchControllerAclGroupNameGet200ResponseIngressInner]**](SwitchControllerAclGroupNameGet200ResponseIngressInner.md) | Configure ingress ACL policies in group. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_acl_group_name_get200_response import SwitchControllerAclGroupNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerAclGroupNameGet200Response from a JSON string
switch_controller_acl_group_name_get200_response_instance = SwitchControllerAclGroupNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerAclGroupNameGet200Response.to_json())

# convert the object into a dict
switch_controller_acl_group_name_get200_response_dict = switch_controller_acl_group_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerAclGroupNameGet200Response from a dict
switch_controller_acl_group_name_get200_response_from_dict = SwitchControllerAclGroupNameGet200Response.from_dict(switch_controller_acl_group_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


