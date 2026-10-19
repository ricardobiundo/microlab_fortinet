# SystemInterfaceNameGet200ResponseTaggingInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Tagging entry name. | [optional] 
**category** | **str** | Tag category. | [optional] 
**tags** | [**List[SystemInterfaceNameGet200ResponseTaggingInnerTagsInner]**](SystemInterfaceNameGet200ResponseTaggingInnerTagsInner.md) | Tags. | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_tagging_inner import SystemInterfaceNameGet200ResponseTaggingInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseTaggingInner from a JSON string
system_interface_name_get200_response_tagging_inner_instance = SystemInterfaceNameGet200ResponseTaggingInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseTaggingInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_tagging_inner_dict = system_interface_name_get200_response_tagging_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseTaggingInner from a dict
system_interface_name_get200_response_tagging_inner_from_dict = SystemInterfaceNameGet200ResponseTaggingInner.from_dict(system_interface_name_get200_response_tagging_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


