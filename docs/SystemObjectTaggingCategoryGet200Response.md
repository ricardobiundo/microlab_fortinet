# SystemObjectTaggingCategoryGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**category** | **str** | Tag Category. | [optional] 
**address** | **str** | Address.    disable:Disable.    mandatory:Mandatory.    optional:Optional. | [optional] 
**device** | **str** | Device.    disable:Disable.    mandatory:Mandatory.    optional:Optional. | [optional] 
**interface** | **str** | Interface.    disable:Disable.    mandatory:Mandatory.    optional:Optional. | [optional] 
**multiple** | **str** | Allow multiple tag selection.    enable:Enable multi-tagging.    disable:Disable multi-tagging. | [optional] 
**color** | **int** | Color of icon on the GUI. | [optional] 
**tags** | [**List[SystemInterfaceNameGet200ResponseTaggingInnerTagsInner]**](SystemInterfaceNameGet200ResponseTaggingInnerTagsInner.md) | Tags. | [optional] 

## Example

```python
from microlab_fortinet.models.system_object_tagging_category_get200_response import SystemObjectTaggingCategoryGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemObjectTaggingCategoryGet200Response from a JSON string
system_object_tagging_category_get200_response_instance = SystemObjectTaggingCategoryGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemObjectTaggingCategoryGet200Response.to_json())

# convert the object into a dict
system_object_tagging_category_get200_response_dict = system_object_tagging_category_get200_response_instance.to_dict()
# create an instance of SystemObjectTaggingCategoryGet200Response from a dict
system_object_tagging_category_get200_response_from_dict = SystemObjectTaggingCategoryGet200Response.from_dict(system_object_tagging_category_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


