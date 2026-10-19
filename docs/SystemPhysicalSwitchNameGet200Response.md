# SystemPhysicalSwitchNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**age_enable** | **str** | Enable/disable layer 2 age timer.    enable:Enable layer 2 ageing timer.    disable:Disable layer 2 ageing timer. | [optional] 
**age_val** | **int** | Layer 2 table age timer value. | [optional] 

## Example

```python
from microlab_fortinet.models.system_physical_switch_name_get200_response import SystemPhysicalSwitchNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPhysicalSwitchNameGet200Response from a JSON string
system_physical_switch_name_get200_response_instance = SystemPhysicalSwitchNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemPhysicalSwitchNameGet200Response.to_json())

# convert the object into a dict
system_physical_switch_name_get200_response_dict = system_physical_switch_name_get200_response_instance.to_dict()
# create an instance of SystemPhysicalSwitchNameGet200Response from a dict
system_physical_switch_name_get200_response_from_dict = SystemPhysicalSwitchNameGet200Response.from_dict(system_physical_switch_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


