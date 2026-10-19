# SystemSpeedTestSettingGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**latency_threshold** | **int** | Speed test latency threshold in milliseconds (0 - 2000, default &#x3D; 60) for the Auto mode. If the latency exceeds this threshold, the speed test will use the UDP protocol; otherwise, it will use the TCP protocol. | [optional] 
**multiple_tcp_stream** | **int** | Number of parallel client streams (1 - 64, default &#x3D; 4) for the TCP protocol to run during the speed test. | [optional] 

## Example

```python
from microlab_fortinet.models.system_speed_test_setting_get200_response import SystemSpeedTestSettingGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSpeedTestSettingGet200Response from a JSON string
system_speed_test_setting_get200_response_instance = SystemSpeedTestSettingGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSpeedTestSettingGet200Response.to_json())

# convert the object into a dict
system_speed_test_setting_get200_response_dict = system_speed_test_setting_get200_response_instance.to_dict()
# create an instance of SystemSpeedTestSettingGet200Response from a dict
system_speed_test_setting_get200_response_from_dict = SystemSpeedTestSettingGet200Response.from_dict(system_speed_test_setting_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


