# SystemVdomNetflowGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vdom_netflow** | **str** | Enable/disable NetFlow per VDOM.    enable:Enable NetFlow per VDOM.    disable:Disable NetFlow per VDOM. | [optional] 
**collectors** | [**List[SystemNetflowGet200ResponseCollectorsInner]**](SystemNetflowGet200ResponseCollectorsInner.md) | Netflow collectors. | [optional] 

## Example

```python
from microlab_fortinet.models.system_vdom_netflow_get200_response import SystemVdomNetflowGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVdomNetflowGet200Response from a JSON string
system_vdom_netflow_get200_response_instance = SystemVdomNetflowGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemVdomNetflowGet200Response.to_json())

# convert the object into a dict
system_vdom_netflow_get200_response_dict = system_vdom_netflow_get200_response_instance.to_dict()
# create an instance of SystemVdomNetflowGet200Response from a dict
system_vdom_netflow_get200_response_from_dict = SystemVdomNetflowGet200Response.from_dict(system_vdom_netflow_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


