# SystemAutoupdateScheduleGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable scheduled updates.    enable:Enable setting.    disable:Disable setting. | [optional] 
**frequency** | **str** | Update frequency.    every:Time interval.    daily:Every day.    weekly:Every week.    automatic:Update automatically within every one hour period. | [optional] 
**time** | **str** | Update time. | [optional] 
**day** | **str** | Update day.    Sunday:Update every Sunday.    Monday:Update every Monday.    Tuesday:Update every Tuesday.    Wednesday:Update every Wednesday.    Thursday:Update every Thursday.    Friday:Update every Friday.    Saturday:Update every Saturday. | [optional] 

## Example

```python
from microlab_fortinet.models.system_autoupdate_schedule_get200_response import SystemAutoupdateScheduleGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAutoupdateScheduleGet200Response from a JSON string
system_autoupdate_schedule_get200_response_instance = SystemAutoupdateScheduleGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAutoupdateScheduleGet200Response.to_json())

# convert the object into a dict
system_autoupdate_schedule_get200_response_dict = system_autoupdate_schedule_get200_response_instance.to_dict()
# create an instance of SystemAutoupdateScheduleGet200Response from a dict
system_autoupdate_schedule_get200_response_from_dict = SystemAutoupdateScheduleGet200Response.from_dict(system_autoupdate_schedule_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


