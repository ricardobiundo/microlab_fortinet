# SystemAliasNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Alias command name. | [optional] 
**command** | **str** | Command list to execute. | [optional] 

## Example

```python
from microlab_fortinet.models.system_alias_name_get200_response import SystemAliasNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAliasNameGet200Response from a JSON string
system_alias_name_get200_response_instance = SystemAliasNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAliasNameGet200Response.to_json())

# convert the object into a dict
system_alias_name_get200_response_dict = system_alias_name_get200_response_instance.to_dict()
# create an instance of SystemAliasNameGet200Response from a dict
system_alias_name_get200_response_from_dict = SystemAliasNameGet200Response.from_dict(system_alias_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


