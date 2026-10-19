# SystemVdomSflowGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vdom_sflow** | **str** | Enable/disable the sFlow configuration for the current VDOM.    enable:Enable sFlow for this VDOM.    disable:Disable sFlow for this VDOM. | [optional] 
**collectors** | [**List[SystemSflowGet200ResponseCollectorsInner]**](SystemSflowGet200ResponseCollectorsInner.md) | sFlow collectors. | [optional] 

## Example

```python
from microlab_fortinet.models.system_vdom_sflow_get200_response import SystemVdomSflowGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVdomSflowGet200Response from a JSON string
system_vdom_sflow_get200_response_instance = SystemVdomSflowGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemVdomSflowGet200Response.to_json())

# convert the object into a dict
system_vdom_sflow_get200_response_dict = system_vdom_sflow_get200_response_instance.to_dict()
# create an instance of SystemVdomSflowGet200Response from a dict
system_vdom_sflow_get200_response_from_dict = SystemVdomSflowGet200Response.from_dict(system_vdom_sflow_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


