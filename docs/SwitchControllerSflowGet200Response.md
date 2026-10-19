# SwitchControllerSflowGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**collector_ip** | **str** | Collector IP. | [optional] 
**collector_port** | **int** | SFlow collector port (0 - 65535). | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_sflow_get200_response import SwitchControllerSflowGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerSflowGet200Response from a JSON string
switch_controller_sflow_get200_response_instance = SwitchControllerSflowGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerSflowGet200Response.to_json())

# convert the object into a dict
switch_controller_sflow_get200_response_dict = switch_controller_sflow_get200_response_instance.to_dict()
# create an instance of SwitchControllerSflowGet200Response from a dict
switch_controller_sflow_get200_response_from_dict = SwitchControllerSflowGet200Response.from_dict(switch_controller_sflow_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


