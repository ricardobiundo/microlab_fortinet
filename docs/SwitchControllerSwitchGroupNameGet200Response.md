# SwitchControllerSwitchGroupNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Switch group name. | [optional] 
**description** | **str** | Optional switch group description. | [optional] 
**fortilink** | **str** | FortiLink interface to which switch group members belong. | [optional] 
**members** | [**List[SwitchControllerSwitchGroupNameGet200ResponseMembersInner]**](SwitchControllerSwitchGroupNameGet200ResponseMembersInner.md) | FortiSwitch members belonging to this switch group. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_switch_group_name_get200_response import SwitchControllerSwitchGroupNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerSwitchGroupNameGet200Response from a JSON string
switch_controller_switch_group_name_get200_response_instance = SwitchControllerSwitchGroupNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerSwitchGroupNameGet200Response.to_json())

# convert the object into a dict
switch_controller_switch_group_name_get200_response_dict = switch_controller_switch_group_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerSwitchGroupNameGet200Response from a dict
switch_controller_switch_group_name_get200_response_from_dict = SwitchControllerSwitchGroupNameGet200Response.from_dict(switch_controller_switch_group_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


