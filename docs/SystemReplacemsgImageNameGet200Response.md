# SystemReplacemsgImageNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Image name. | [optional] 
**image_type** | **str** | Image type.    gif:GIF image.    jpg:JPEG image.    tiff:TIFF image.    png:PNG image. | [optional] 
**image_base64** | **str** | Image data. | [optional] 

## Example

```python
from microlab_fortinet.models.system_replacemsg_image_name_get200_response import SystemReplacemsgImageNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemReplacemsgImageNameGet200Response from a JSON string
system_replacemsg_image_name_get200_response_instance = SystemReplacemsgImageNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemReplacemsgImageNameGet200Response.to_json())

# convert the object into a dict
system_replacemsg_image_name_get200_response_dict = system_replacemsg_image_name_get200_response_instance.to_dict()
# create an instance of SystemReplacemsgImageNameGet200Response from a dict
system_replacemsg_image_name_get200_response_from_dict = SystemReplacemsgImageNameGet200Response.from_dict(system_replacemsg_image_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


