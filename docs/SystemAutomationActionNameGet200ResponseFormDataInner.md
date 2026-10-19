# SystemAutomationActionNameGet200ResponseFormDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Entry ID. | [optional] 
**key** | **str** | Key of the part of Multipart/form-data. | [optional] 
**value** | **str** | Value of the part of Multipart/form-data. | [optional] 

## Example

```python
from microlab_fortinet.models.system_automation_action_name_get200_response_form_data_inner import SystemAutomationActionNameGet200ResponseFormDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAutomationActionNameGet200ResponseFormDataInner from a JSON string
system_automation_action_name_get200_response_form_data_inner_instance = SystemAutomationActionNameGet200ResponseFormDataInner.from_json(json)
# print the JSON string representation of the object
print(SystemAutomationActionNameGet200ResponseFormDataInner.to_json())

# convert the object into a dict
system_automation_action_name_get200_response_form_data_inner_dict = system_automation_action_name_get200_response_form_data_inner_instance.to_dict()
# create an instance of SystemAutomationActionNameGet200ResponseFormDataInner from a dict
system_automation_action_name_get200_response_form_data_inner_from_dict = SystemAutomationActionNameGet200ResponseFormDataInner.from_dict(system_automation_action_name_get200_response_form_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


