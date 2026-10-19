# SystemAffinityInterruptIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID of the interrupt affinity setting. | [optional] 
**interrupt** | **str** | Interrupt name. | [optional] 
**affinity_cpumask** | **str** | Affinity setting (64-bit hexadecimal value in the format of 0xxxxxxxxxxxxxxxxx). | [optional] 
**default_affinity_cpumask** | **str** | Default affinity setting (64-bit hexadecimal value in the format of 0xxxxxxxxxxxxxxxxx). | [optional] 

## Example

```python
from microlab_fortinet.models.system_affinity_interrupt_id_get200_response import SystemAffinityInterruptIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAffinityInterruptIdGet200Response from a JSON string
system_affinity_interrupt_id_get200_response_instance = SystemAffinityInterruptIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAffinityInterruptIdGet200Response.to_json())

# convert the object into a dict
system_affinity_interrupt_id_get200_response_dict = system_affinity_interrupt_id_get200_response_instance.to_dict()
# create an instance of SystemAffinityInterruptIdGet200Response from a dict
system_affinity_interrupt_id_get200_response_from_dict = SystemAffinityInterruptIdGet200Response.from_dict(system_affinity_interrupt_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


