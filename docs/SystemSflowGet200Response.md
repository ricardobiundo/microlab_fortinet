# SystemSflowGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**collectors** | [**List[SystemSflowGet200ResponseCollectorsInner]**](SystemSflowGet200ResponseCollectorsInner.md) | sFlow collectors. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sflow_get200_response import SystemSflowGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSflowGet200Response from a JSON string
system_sflow_get200_response_instance = SystemSflowGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSflowGet200Response.to_json())

# convert the object into a dict
system_sflow_get200_response_dict = system_sflow_get200_response_instance.to_dict()
# create an instance of SystemSflowGet200Response from a dict
system_sflow_get200_response_from_dict = SystemSflowGet200Response.from_dict(system_sflow_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


