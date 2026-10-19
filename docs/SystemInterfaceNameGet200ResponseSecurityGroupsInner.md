# SystemInterfaceNameGet200ResponseSecurityGroupsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Names of user groups that can authenticate with the captive portal. | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_security_groups_inner import SystemInterfaceNameGet200ResponseSecurityGroupsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseSecurityGroupsInner from a JSON string
system_interface_name_get200_response_security_groups_inner_instance = SystemInterfaceNameGet200ResponseSecurityGroupsInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseSecurityGroupsInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_security_groups_inner_dict = system_interface_name_get200_response_security_groups_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseSecurityGroupsInner from a dict
system_interface_name_get200_response_security_groups_inner_from_dict = SystemInterfaceNameGet200ResponseSecurityGroupsInner.from_dict(system_interface_name_get200_response_security_groups_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


