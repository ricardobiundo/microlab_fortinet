# SystemNdProxyGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable neighbor discovery proxy.    enable:Enable neighbor discovery proxy.    disable:Disable neighbor discovery proxy. | [optional] 
**member** | [**List[SystemAcmeGet200ResponseInterfaceInner]**](SystemAcmeGet200ResponseInterfaceInner.md) | Interfaces using the neighbor discovery proxy. | [optional] 

## Example

```python
from microlab_fortinet.models.system_nd_proxy_get200_response import SystemNdProxyGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNdProxyGet200Response from a JSON string
system_nd_proxy_get200_response_instance = SystemNdProxyGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemNdProxyGet200Response.to_json())

# convert the object into a dict
system_nd_proxy_get200_response_dict = system_nd_proxy_get200_response_instance.to_dict()
# create an instance of SystemNdProxyGet200Response from a dict
system_nd_proxy_get200_response_from_dict = SystemNdProxyGet200Response.from_dict(system_nd_proxy_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


