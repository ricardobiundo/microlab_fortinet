# SwitchControllerAclIngressIdGet200ResponseClassifierInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dst_ip_prefix** | **str** | Destination IP address to be matched. | [optional] 
**dst_mac** | **str** | Destination MAC address to be matched. | [optional] 
**src_ip_prefix** | **str** | Source IP address to be matched. | [optional] 
**src_mac** | **str** | Source MAC address to be matched. | [optional] 
**vlan** | **int** | VLAN ID to be matched. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_acl_ingress_id_get200_response_classifier_inner import SwitchControllerAclIngressIdGet200ResponseClassifierInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerAclIngressIdGet200ResponseClassifierInner from a JSON string
switch_controller_acl_ingress_id_get200_response_classifier_inner_instance = SwitchControllerAclIngressIdGet200ResponseClassifierInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerAclIngressIdGet200ResponseClassifierInner.to_json())

# convert the object into a dict
switch_controller_acl_ingress_id_get200_response_classifier_inner_dict = switch_controller_acl_ingress_id_get200_response_classifier_inner_instance.to_dict()
# create an instance of SwitchControllerAclIngressIdGet200ResponseClassifierInner from a dict
switch_controller_acl_ingress_id_get200_response_classifier_inner_from_dict = SwitchControllerAclIngressIdGet200ResponseClassifierInner.from_dict(switch_controller_acl_ingress_id_get200_response_classifier_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


