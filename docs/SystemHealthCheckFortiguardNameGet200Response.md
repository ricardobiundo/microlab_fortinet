# SystemHealthCheckFortiguardNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Status check or predefined health-check targets name. | [optional] 
**server** | **str** | Status check or predefined health-check domain name. | [optional] 
**obsolete** | **int** | Indicates whether Health Check service can be used. | [optional] 
**protocol** | **str** | Protocol name.    ping:Use PING to test the link with the server.    tcp-echo:Use TCP echo to test the link with the server.    udp-echo:Use UDP echo to test the link with the server.    http:Use HTTP-GET to test the link with the server.    https:Use HTTPS-GET to test the link with the server.    twamp:Use TWAMP to test the link with the server.    dns:Use DNS query to test the link with the server.    tcp-connect:Use a full TCP connection to test the link with the server.    ftp:Use FTP to test the link with the server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_health_check_fortiguard_name_get200_response import SystemHealthCheckFortiguardNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemHealthCheckFortiguardNameGet200Response from a JSON string
system_health_check_fortiguard_name_get200_response_instance = SystemHealthCheckFortiguardNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemHealthCheckFortiguardNameGet200Response.to_json())

# convert the object into a dict
system_health_check_fortiguard_name_get200_response_dict = system_health_check_fortiguard_name_get200_response_instance.to_dict()
# create an instance of SystemHealthCheckFortiguardNameGet200Response from a dict
system_health_check_fortiguard_name_get200_response_from_dict = SystemHealthCheckFortiguardNameGet200Response.from_dict(system_health_check_fortiguard_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


