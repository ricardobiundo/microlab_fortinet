# SwitchControllerAclIngressIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ACL ID. | [optional] 
**description** | **str** | Description for the ACL policy. | [optional] 
**action** | [**List[SwitchControllerAclIngressIdGet200ResponseActionInner]**](SwitchControllerAclIngressIdGet200ResponseActionInner.md) | ACL actions. | [optional] 
**classifier** | [**List[SwitchControllerAclIngressIdGet200ResponseClassifierInner]**](SwitchControllerAclIngressIdGet200ResponseClassifierInner.md) | ACL classifiers. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_acl_ingress_id_get200_response import SwitchControllerAclIngressIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerAclIngressIdGet200Response from a JSON string
switch_controller_acl_ingress_id_get200_response_instance = SwitchControllerAclIngressIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerAclIngressIdGet200Response.to_json())

# convert the object into a dict
switch_controller_acl_ingress_id_get200_response_dict = switch_controller_acl_ingress_id_get200_response_instance.to_dict()
# create an instance of SwitchControllerAclIngressIdGet200Response from a dict
switch_controller_acl_ingress_id_get200_response_from_dict = SwitchControllerAclIngressIdGet200Response.from_dict(switch_controller_acl_ingress_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


