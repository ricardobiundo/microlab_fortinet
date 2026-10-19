# SystemAutoScriptNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Auto script name. | [optional] 
**interval** | **int** | Repeat interval in seconds. | [optional] 
**repeat** | **int** | Number of times to repeat this script (0 &#x3D; infinite). | [optional] 
**start** | **str** | Script starting mode.    manual:Starting manually.    auto:Starting automatically. | [optional] 
**script** | **str** | List of FortiOS CLI commands to repeat. | [optional] 
**output_size** | **int** | Number of megabytes to limit script output to (10 - 1024, default &#x3D; 10). | [optional] 
**timeout** | **int** | Maximum running time for this script in seconds (0 &#x3D; no timeout). | [optional] 

## Example

```python
from microlab_fortinet.models.system_auto_script_name_get200_response import SystemAutoScriptNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAutoScriptNameGet200Response from a JSON string
system_auto_script_name_get200_response_instance = SystemAutoScriptNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAutoScriptNameGet200Response.to_json())

# convert the object into a dict
system_auto_script_name_get200_response_dict = system_auto_script_name_get200_response_instance.to_dict()
# create an instance of SystemAutoScriptNameGet200Response from a dict
system_auto_script_name_get200_response_from_dict = SystemAutoScriptNameGet200Response.from_dict(system_auto_script_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


