# SystemSdnProxyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | SDN proxy name. | [optional] 
**type** | **str** | Type of SDN proxy.    general:General HTTP proxy.    fortimanager:FortiManager SDN proxy. | [optional] 
**server** | **str** | Server address of the SDN proxy. | [optional] 
**server_port** | **int** | Port number of the SDN proxy. | [optional] 
**username** | **str** | SDN proxy username. | [optional] 
**password** | **str** | SDN proxy password. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdn_proxy_name_get200_response import SystemSdnProxyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdnProxyNameGet200Response from a JSON string
system_sdn_proxy_name_get200_response_instance = SystemSdnProxyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSdnProxyNameGet200Response.to_json())

# convert the object into a dict
system_sdn_proxy_name_get200_response_dict = system_sdn_proxy_name_get200_response_instance.to_dict()
# create an instance of SystemSdnProxyNameGet200Response from a dict
system_sdn_proxy_name_get200_response_from_dict = SystemSdnProxyNameGet200Response.from_dict(system_sdn_proxy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


