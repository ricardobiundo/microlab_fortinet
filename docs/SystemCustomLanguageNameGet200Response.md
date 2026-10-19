# SystemCustomLanguageNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**filename** | **str** | Custom language file path. | [optional] 
**comments** | **str** | Comment. | [optional] 

## Example

```python
from microlab_fortinet.models.system_custom_language_name_get200_response import SystemCustomLanguageNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemCustomLanguageNameGet200Response from a JSON string
system_custom_language_name_get200_response_instance = SystemCustomLanguageNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemCustomLanguageNameGet200Response.to_json())

# convert the object into a dict
system_custom_language_name_get200_response_dict = system_custom_language_name_get200_response_instance.to_dict()
# create an instance of SystemCustomLanguageNameGet200Response from a dict
system_custom_language_name_get200_response_from_dict = SystemCustomLanguageNameGet200Response.from_dict(system_custom_language_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


