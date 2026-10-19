# SystemProbeResponseGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**port** | **int** | Port number to response. | [optional] 
**http_probe_value** | **str** | Value to respond to the monitoring server. | [optional] 
**ttl_mode** | **str** | Mode for TWAMP packet TTL modification.    reinit:Reinitialize TTL.    decrease:Decrease TTL.    retain:Retain TTL. | [optional] 
**mode** | **str** | SLA response mode.    none:Disable probe.    http-probe:HTTP probe.    twamp:Two way active measurement protocol. | [optional] 
**security_mode** | **str** | TWAMP responder security mode.    none:Unauthenticated mode.    authentication:Authenticated mode. | [optional] 
**password** | **str** | TWAMP responder password in authentication mode. | [optional] 
**timeout** | **int** | An inactivity timer for a twamp test session. | [optional] 

## Example

```python
from microlab_fortinet.models.system_probe_response_get200_response import SystemProbeResponseGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemProbeResponseGet200Response from a JSON string
system_probe_response_get200_response_instance = SystemProbeResponseGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemProbeResponseGet200Response.to_json())

# convert the object into a dict
system_probe_response_get200_response_dict = system_probe_response_get200_response_instance.to_dict()
# create an instance of SystemProbeResponseGet200Response from a dict
system_probe_response_get200_response_from_dict = SystemProbeResponseGet200Response.from_dict(system_probe_response_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


