# SystemAlarmGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable alarm.    enable:Enable alarm.    disable:Disable alarm. | [optional] 
**audible** | **str** | Enable/disable audible alarm.    enable:Enable audible alarm.    disable:Disable audible alarm. | [optional] 
**groups** | [**List[SystemAlarmGet200ResponseGroupsInner]**](SystemAlarmGet200ResponseGroupsInner.md) | Alarm groups. | [optional] 

## Example

```python
from microlab_fortinet.models.system_alarm_get200_response import SystemAlarmGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAlarmGet200Response from a JSON string
system_alarm_get200_response_instance = SystemAlarmGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAlarmGet200Response.to_json())

# convert the object into a dict
system_alarm_get200_response_dict = system_alarm_get200_response_instance.to_dict()
# create an instance of SystemAlarmGet200Response from a dict
system_alarm_get200_response_from_dict = SystemAlarmGet200Response.from_dict(system_alarm_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


