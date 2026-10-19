# SystemSessionTtlGet200ResponsePortInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Table entry ID. | [optional] 
**protocol** | **int** | Protocol (0 - 255). | [optional] 
**start_port** | **int** | Start port number. | [optional] 
**end_port** | **int** | End port number. | [optional] 
**timeout** | **str** | Session timeout (TTL). | [optional] 
**refresh_direction** | **str** | Configure refresh direction.    both:Refresh both directions.    outgoing:Refresh outgoing direction (original).    incoming:Refresh incoming direction (reply). | [optional] 

## Example

```python
from microlab_fortinet.models.system_session_ttl_get200_response_port_inner import SystemSessionTtlGet200ResponsePortInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSessionTtlGet200ResponsePortInner from a JSON string
system_session_ttl_get200_response_port_inner_instance = SystemSessionTtlGet200ResponsePortInner.from_json(json)
# print the JSON string representation of the object
print(SystemSessionTtlGet200ResponsePortInner.to_json())

# convert the object into a dict
system_session_ttl_get200_response_port_inner_dict = system_session_ttl_get200_response_port_inner_instance.to_dict()
# create an instance of SystemSessionTtlGet200ResponsePortInner from a dict
system_session_ttl_get200_response_port_inner_from_dict = SystemSessionTtlGet200ResponsePortInner.from_dict(system_session_ttl_get200_response_port_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


