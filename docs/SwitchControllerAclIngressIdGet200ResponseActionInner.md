# SwitchControllerAclIngressIdGet200ResponseActionInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**drop** | **str** | Enable/disable drop.    enable:Enable drop.    disable:Disable drop. | [optional] 
**count** | **str** | Enable/disable count.    enable:Enable count.    disable:Disable count. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_acl_ingress_id_get200_response_action_inner import SwitchControllerAclIngressIdGet200ResponseActionInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerAclIngressIdGet200ResponseActionInner from a JSON string
switch_controller_acl_ingress_id_get200_response_action_inner_instance = SwitchControllerAclIngressIdGet200ResponseActionInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerAclIngressIdGet200ResponseActionInner.to_json())

# convert the object into a dict
switch_controller_acl_ingress_id_get200_response_action_inner_dict = switch_controller_acl_ingress_id_get200_response_action_inner_instance.to_dict()
# create an instance of SwitchControllerAclIngressIdGet200ResponseActionInner from a dict
switch_controller_acl_ingress_id_get200_response_action_inner_from_dict = SwitchControllerAclIngressIdGet200ResponseActionInner.from_dict(switch_controller_acl_ingress_id_get200_response_action_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


