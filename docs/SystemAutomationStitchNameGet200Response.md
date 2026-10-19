# SystemAutomationStitchNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**description** | **str** | Description. | [optional] 
**status** | **str** | Enable/disable this stitch.    enable:Enable stitch.    disable:Disable stitch. | [optional] 
**trigger** | **str** | Trigger name. | [optional] 
**condition** | [**List[SystemAutomationStitchNameGet200ResponseConditionInner]**](SystemAutomationStitchNameGet200ResponseConditionInner.md) | Automation conditions. | [optional] 
**condition_logic** | **str** | Apply AND/OR logic to the specified automation conditions.    and:All specified conditions must be met.    or:At least one specified condition needs to be met. | [optional] 
**actions** | [**List[SystemAutomationStitchNameGet200ResponseActionsInner]**](SystemAutomationStitchNameGet200ResponseActionsInner.md) | Configure stitch actions. | [optional] 
**destination** | [**List[SystemAutomationStitchNameGet200ResponseDestinationInner]**](SystemAutomationStitchNameGet200ResponseDestinationInner.md) | Serial number/HA group-name of destination devices. | [optional] 

## Example

```python
from microlab_fortinet.models.system_automation_stitch_name_get200_response import SystemAutomationStitchNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAutomationStitchNameGet200Response from a JSON string
system_automation_stitch_name_get200_response_instance = SystemAutomationStitchNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAutomationStitchNameGet200Response.to_json())

# convert the object into a dict
system_automation_stitch_name_get200_response_dict = system_automation_stitch_name_get200_response_instance.to_dict()
# create an instance of SystemAutomationStitchNameGet200Response from a dict
system_automation_stitch_name_get200_response_from_dict = SystemAutomationStitchNameGet200Response.from_dict(system_automation_stitch_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


