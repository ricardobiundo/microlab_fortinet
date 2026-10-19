# SystemDscpBasedPriorityIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Item ID. | [optional] 
**ds** | **int** | DSCP(DiffServ) DS value (0 - 63). | [optional] 
**priority** | **str** | DSCP based priority level.    low:Low priority.    medium:Medium priority.    high:High priority. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dscp_based_priority_id_get200_response import SystemDscpBasedPriorityIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDscpBasedPriorityIdGet200Response from a JSON string
system_dscp_based_priority_id_get200_response_instance = SystemDscpBasedPriorityIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemDscpBasedPriorityIdGet200Response.to_json())

# convert the object into a dict
system_dscp_based_priority_id_get200_response_dict = system_dscp_based_priority_id_get200_response_instance.to_dict()
# create an instance of SystemDscpBasedPriorityIdGet200Response from a dict
system_dscp_based_priority_id_get200_response_from_dict = SystemDscpBasedPriorityIdGet200Response.from_dict(system_dscp_based_priority_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


