# SystemVdomNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | VDOM name. | [optional] 
**short_name** | **str** | VDOM short name. | [optional] 
**vcluster_id** | **int** | Virtual cluster ID (0 - 4294967295). | [optional] 
**flag** | **int** | Flag. | [optional] 

## Example

```python
from microlab_fortinet.models.system_vdom_name_get200_response import SystemVdomNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVdomNameGet200Response from a JSON string
system_vdom_name_get200_response_instance = SystemVdomNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemVdomNameGet200Response.to_json())

# convert the object into a dict
system_vdom_name_get200_response_dict = system_vdom_name_get200_response_instance.to_dict()
# create an instance of SystemVdomNameGet200Response from a dict
system_vdom_name_get200_response_from_dict = SystemVdomNameGet200Response.from_dict(system_vdom_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


