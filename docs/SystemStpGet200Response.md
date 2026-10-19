# SystemStpGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**switch_priority** | **str** | STP switch priority; the lower the number the higher the priority (select from 0, 4096, 8192, 12288, 16384, 20480, 24576, 28672, 32768, 36864, 40960, 45056, 49152, 53248, and 57344).    0:0    4096:4096    8192:8192    12288:12288    16384:16384    20480:20480    24576:24576    28672:28672    32768:32768    36864:36864    40960:40960    45056:45056    49152:49152    53248:53248    57344:57344 | [optional] 
**hello_time** | **int** | Hello time (1 - 10 sec, default &#x3D; 2). | [optional] 
**forward_delay** | **int** | Forward delay (4 - 30 sec, default &#x3D; 15). | [optional] 
**max_age** | **int** | Maximum packet age (6 - 40 sec, default &#x3D; 20). | [optional] 
**max_hops** | **int** | Maximum number of hops (1 - 40, default &#x3D; 20). | [optional] 
**list** | **str** | Display STP status. | [optional] 

## Example

```python
from microlab_fortinet.models.system_stp_get200_response import SystemStpGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemStpGet200Response from a JSON string
system_stp_get200_response_instance = SystemStpGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemStpGet200Response.to_json())

# convert the object into a dict
system_stp_get200_response_dict = system_stp_get200_response_instance.to_dict()
# create an instance of SystemStpGet200Response from a dict
system_stp_get200_response_from_dict = SystemStpGet200Response.from_dict(system_stp_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


