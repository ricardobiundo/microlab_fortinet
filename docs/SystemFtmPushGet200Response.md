# SystemFtmPushGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**proxy** | **str** | Enable/disable communication to the proxy server in FortiGuard configuration.    enable:Enable communication to the proxy server in FortiGuard configuration.    disable:Disable communication to the proxy server in FortiGuard configuration. | [optional] 
**interface** | **str** | Interface of FortiToken Mobile push services server. | [optional] 
**server** | **str** | IPv4 address or domain name of FortiToken Mobile push services server. | [optional] 
**server_port** | **int** | Port to communicate with FortiToken Mobile push services server (1 - 65535, default &#x3D; 4433). | [optional] 
**server_cert** | **str** | Name of the server certificate to be used for SSL. | [optional] 
**server_ip** | **str** | IPv4 address of FortiToken Mobile push services server (format: xxx.xxx.xxx.xxx). | [optional] 
**status** | **str** | Enable/disable the use of FortiToken Mobile push services.    enable:Enable FortiToken Mobile push services.    disable:Disable FortiToken Mobile push services. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ftm_push_get200_response import SystemFtmPushGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFtmPushGet200Response from a JSON string
system_ftm_push_get200_response_instance = SystemFtmPushGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemFtmPushGet200Response.to_json())

# convert the object into a dict
system_ftm_push_get200_response_dict = system_ftm_push_get200_response_instance.to_dict()
# create an instance of SystemFtmPushGet200Response from a dict
system_ftm_push_get200_response_from_dict = SystemFtmPushGet200Response.from_dict(system_ftm_push_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


