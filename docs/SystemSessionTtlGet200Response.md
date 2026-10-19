# SystemSessionTtlGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**default** | **str** | Default timeout. | [optional] 
**port** | [**List[SystemSessionTtlGet200ResponsePortInner]**](SystemSessionTtlGet200ResponsePortInner.md) | Session TTL port. | [optional] 

## Example

```python
from microlab_fortinet.models.system_session_ttl_get200_response import SystemSessionTtlGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSessionTtlGet200Response from a JSON string
system_session_ttl_get200_response_instance = SystemSessionTtlGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSessionTtlGet200Response.to_json())

# convert the object into a dict
system_session_ttl_get200_response_dict = system_session_ttl_get200_response_instance.to_dict()
# create an instance of SystemSessionTtlGet200Response from a dict
system_session_ttl_get200_response_from_dict = SystemSessionTtlGet200Response.from_dict(system_session_ttl_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


