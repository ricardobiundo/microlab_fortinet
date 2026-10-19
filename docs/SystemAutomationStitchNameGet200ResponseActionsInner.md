# SystemAutomationStitchNameGet200ResponseActionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Entry ID. | [optional] 
**action** | **str** | Action name. | [optional] 
**delay** | **int** | Delay before execution (in seconds). | [optional] 
**required** | **str** | Required in action chain.    enable:Required in action chain.    disable:Not required in action chain. | [optional] 

## Example

```python
from microlab_fortinet.models.system_automation_stitch_name_get200_response_actions_inner import SystemAutomationStitchNameGet200ResponseActionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAutomationStitchNameGet200ResponseActionsInner from a JSON string
system_automation_stitch_name_get200_response_actions_inner_instance = SystemAutomationStitchNameGet200ResponseActionsInner.from_json(json)
# print the JSON string representation of the object
print(SystemAutomationStitchNameGet200ResponseActionsInner.to_json())

# convert the object into a dict
system_automation_stitch_name_get200_response_actions_inner_dict = system_automation_stitch_name_get200_response_actions_inner_instance.to_dict()
# create an instance of SystemAutomationStitchNameGet200ResponseActionsInner from a dict
system_automation_stitch_name_get200_response_actions_inner_from_dict = SystemAutomationStitchNameGet200ResponseActionsInner.from_dict(system_automation_stitch_name_get200_response_actions_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


