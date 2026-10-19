# SystemTosBasedPriorityIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Item ID. | [optional] 
**tos** | **int** | Value of the ToS byte in the IP datagram header (0-15, 8: minimize delay, 4: maximize throughput, 2: maximize reliability, 1: minimize monetary cost, and 0: default service). | [optional] 
**priority** | **str** | ToS based priority level to low, medium or high (these priorities match firewall traffic shaping priorities) (default &#x3D; medium).    low:Low priority.    medium:Medium priority.    high:High priority. | [optional] 

## Example

```python
from microlab_fortinet.models.system_tos_based_priority_id_get200_response import SystemTosBasedPriorityIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemTosBasedPriorityIdGet200Response from a JSON string
system_tos_based_priority_id_get200_response_instance = SystemTosBasedPriorityIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemTosBasedPriorityIdGet200Response.to_json())

# convert the object into a dict
system_tos_based_priority_id_get200_response_dict = system_tos_based_priority_id_get200_response_instance.to_dict()
# create an instance of SystemTosBasedPriorityIdGet200Response from a dict
system_tos_based_priority_id_get200_response_from_dict = SystemTosBasedPriorityIdGet200Response.from_dict(system_tos_based_priority_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


