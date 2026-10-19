# SystemSpeedTestServerNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Speed test server name. | [optional] 
**timestamp** | **int** | Speed test server timestamp. | [optional] 
**host** | [**List[SystemSpeedTestServerNameGet200ResponseHostInner]**](SystemSpeedTestServerNameGet200ResponseHostInner.md) | Hosts of the server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_speed_test_server_name_get200_response import SystemSpeedTestServerNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSpeedTestServerNameGet200Response from a JSON string
system_speed_test_server_name_get200_response_instance = SystemSpeedTestServerNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSpeedTestServerNameGet200Response.to_json())

# convert the object into a dict
system_speed_test_server_name_get200_response_dict = system_speed_test_server_name_get200_response_instance.to_dict()
# create an instance of SystemSpeedTestServerNameGet200Response from a dict
system_speed_test_server_name_get200_response_from_dict = SystemSpeedTestServerNameGet200Response.from_dict(system_speed_test_server_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


