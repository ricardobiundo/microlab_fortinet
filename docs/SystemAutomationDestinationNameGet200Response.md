# SystemAutomationDestinationNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**type** | **str** | Destination type.    fortigate:FortiGate set as destination.    ha-cluster:HA cluster set as destination. | [optional] 
**destination** | [**List[SystemAutomationDestinationNameGet200ResponseDestinationInner]**](SystemAutomationDestinationNameGet200ResponseDestinationInner.md) | Destinations. | [optional] 
**ha_group_id** | **int** | Cluster group ID set for this destination (default &#x3D; 0). | [optional] 

## Example

```python
from microlab_fortinet.models.system_automation_destination_name_get200_response import SystemAutomationDestinationNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAutomationDestinationNameGet200Response from a JSON string
system_automation_destination_name_get200_response_instance = SystemAutomationDestinationNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAutomationDestinationNameGet200Response.to_json())

# convert the object into a dict
system_automation_destination_name_get200_response_dict = system_automation_destination_name_get200_response_instance.to_dict()
# create an instance of SystemAutomationDestinationNameGet200Response from a dict
system_automation_destination_name_get200_response_from_dict = SystemAutomationDestinationNameGet200Response.from_dict(system_automation_destination_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


