# SystemAutoInstallGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auto_install_config** | **str** | Enable/disable auto install the config in USB disk.    enable:Enable config.    disable:Disable config. | [optional] 
**auto_install_image** | **str** | Enable/disable auto install the image in USB disk.    enable:Enable config.    disable:Disable config. | [optional] 
**default_config_file** | **str** | Default config file name in USB disk. | [optional] 
**default_image_file** | **str** | Default image file name in USB disk. | [optional] 

## Example

```python
from microlab_fortinet.models.system_auto_install_get200_response import SystemAutoInstallGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAutoInstallGet200Response from a JSON string
system_auto_install_get200_response_instance = SystemAutoInstallGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAutoInstallGet200Response.to_json())

# convert the object into a dict
system_auto_install_get200_response_dict = system_auto_install_get200_response_instance.to_dict()
# create an instance of SystemAutoInstallGet200Response from a dict
system_auto_install_get200_response_from_dict = SystemAutoInstallGet200Response.from_dict(system_auto_install_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


