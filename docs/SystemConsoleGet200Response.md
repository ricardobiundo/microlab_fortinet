# SystemConsoleGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**output** | **str** | Console output mode.    standard:Standard output.    more:More page output. | [optional] 
**login** | **str** | Enable/disable serial console and FortiExplorer.    enable:Console login enable.    disable:Console login disable. | [optional] 
**fortiexplorer** | **str** | Enable/disable access for FortiExplorer.    enable:Enable FortiExplorer access.    disable:Disable FortiExplorer access. | [optional] 

## Example

```python
from microlab_fortinet.models.system_console_get200_response import SystemConsoleGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemConsoleGet200Response from a JSON string
system_console_get200_response_instance = SystemConsoleGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemConsoleGet200Response.to_json())

# convert the object into a dict
system_console_get200_response_dict = system_console_get200_response_instance.to_dict()
# create an instance of SystemConsoleGet200Response from a dict
system_console_get200_response_from_dict = SystemConsoleGet200Response.from_dict(system_console_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


