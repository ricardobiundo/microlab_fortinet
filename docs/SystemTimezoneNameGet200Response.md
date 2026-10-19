# SystemTimezoneNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Database name of a timezone. | [optional] 

## Example

```python
from microlab_fortinet.models.system_timezone_name_get200_response import SystemTimezoneNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemTimezoneNameGet200Response from a JSON string
system_timezone_name_get200_response_instance = SystemTimezoneNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemTimezoneNameGet200Response.to_json())

# convert the object into a dict
system_timezone_name_get200_response_dict = system_timezone_name_get200_response_instance.to_dict()
# create an instance of SystemTimezoneNameGet200Response from a dict
system_timezone_name_get200_response_from_dict = SystemTimezoneNameGet200Response.from_dict(system_timezone_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


