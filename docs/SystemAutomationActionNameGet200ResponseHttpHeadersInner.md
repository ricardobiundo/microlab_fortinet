# SystemAutomationActionNameGet200ResponseHttpHeadersInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Entry ID. | [optional] 
**key** | **str** | Request header key. | [optional] 
**value** | **str** | Request header value. | [optional] 

## Example

```python
from microlab_fortinet.models.system_automation_action_name_get200_response_http_headers_inner import SystemAutomationActionNameGet200ResponseHttpHeadersInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAutomationActionNameGet200ResponseHttpHeadersInner from a JSON string
system_automation_action_name_get200_response_http_headers_inner_instance = SystemAutomationActionNameGet200ResponseHttpHeadersInner.from_json(json)
# print the JSON string representation of the object
print(SystemAutomationActionNameGet200ResponseHttpHeadersInner.to_json())

# convert the object into a dict
system_automation_action_name_get200_response_http_headers_inner_dict = system_automation_action_name_get200_response_http_headers_inner_instance.to_dict()
# create an instance of SystemAutomationActionNameGet200ResponseHttpHeadersInner from a dict
system_automation_action_name_get200_response_http_headers_inner_from_dict = SystemAutomationActionNameGet200ResponseHttpHeadersInner.from_dict(system_automation_action_name_get200_response_http_headers_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


