# SystemSpeedTestServerNameGet200ResponseHostInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Server host ID. | [optional] 
**ip** | **str** | Server host IPv4 address. | [optional] 
**port** | **int** | Server host port number to communicate with client. | [optional] 
**user** | **str** | Speed test host user name. | [optional] 
**password** | **str** | Speed test host password. | [optional] 
**longitude** | **str** | Speed test host longitude. | [optional] 
**latitude** | **str** | Speed test host latitude. | [optional] 
**distance** | **int** | Speed test host distance. | [optional] 

## Example

```python
from microlab_fortinet.models.system_speed_test_server_name_get200_response_host_inner import SystemSpeedTestServerNameGet200ResponseHostInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSpeedTestServerNameGet200ResponseHostInner from a JSON string
system_speed_test_server_name_get200_response_host_inner_instance = SystemSpeedTestServerNameGet200ResponseHostInner.from_json(json)
# print the JSON string representation of the object
print(SystemSpeedTestServerNameGet200ResponseHostInner.to_json())

# convert the object into a dict
system_speed_test_server_name_get200_response_host_inner_dict = system_speed_test_server_name_get200_response_host_inner_instance.to_dict()
# create an instance of SystemSpeedTestServerNameGet200ResponseHostInner from a dict
system_speed_test_server_name_get200_response_host_inner_from_dict = SystemSpeedTestServerNameGet200ResponseHostInner.from_dict(system_speed_test_server_name_get200_response_host_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


