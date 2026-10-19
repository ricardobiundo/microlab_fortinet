# SystemAutomationTriggerNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**description** | **str** | Description. | [optional] 
**trigger_type** | **str** | Trigger type.    event-based:Event based trigger.    scheduled:Scheduled trigger. | [optional] 
**event_type** | **str** | Event type.    ioc:Indicator of compromise detected.    event-log:Use log ID as trigger.    reboot:Device reboot.    low-memory:Conserve mode due to low memory.    high-cpu:High CPU usage.    license-near-expiry:License near expiration date.    local-cert-near-expiry:The local certificate near expiration date.    ha-failover:HA failover.    config-change:Configuration change.    security-rating-summary:Security rating summary.    virus-ips-db-updated:Virus and IPS database updated.    faz-event:FortiAnalyzer event.    incoming-webhook:Incoming webhook call.    fabric-event:Fabric connector event.    ips-logs:IPS logs.    anomaly-logs:Anomaly logs.    virus-logs:Virus logs.    ssh-logs:SSH logs.    webfilter-violation:Webfilter violation.    traffic-violation:Traffic violation.    stitch:Specified stitch has been triggered. | [optional] 
**vdom** | [**List[SystemAdminNameGet200ResponseVdomInner]**](SystemAdminNameGet200ResponseVdomInner.md) | Virtual domain(s) that this trigger is valid for. | [optional] 
**license_type** | **str** | License type.    forticare-support:FortiCare support license.    fortiguard-webfilter:FortiGuard web filter license.    fortiguard-antispam:FortiGuard antispam license.    fortiguard-antivirus:FortiGuard AntiVirus license.    fortiguard-ips:FortiGuard IPS license.    fortiguard-management:FortiGuard management service license.    forticloud:FortiCloud license.    any:Any license. | [optional] 
**report_type** | **str** | Security Rating report.    posture:Posture report.    coverage:Coverage report.    optimization:Optimization report    any:Any report. | [optional] 
**stitch_name** | **str** | Triggering stitch name. | [optional] 
**logid** | [**List[SystemAutomationTriggerNameGet200ResponseLogidInner]**](SystemAutomationTriggerNameGet200ResponseLogidInner.md) | Log IDs to trigger event. | [optional] 
**trigger_frequency** | **str** | Scheduled trigger frequency (default &#x3D; daily).    hourly:Run hourly.    daily:Run daily.    weekly:Run weekly.    monthly:Run monthly.    once:Run once at specified date time. | [optional] 
**trigger_weekday** | **str** | Day of week for trigger.    sunday:Sunday.    monday:Monday.    tuesday:Tuesday.    wednesday:Wednesday.    thursday:Thursday.    friday:Friday.    saturday:Saturday. | [optional] 
**trigger_day** | **int** | Day within a month to trigger. | [optional] 
**trigger_hour** | **int** | Hour of the day on which to trigger (0 - 23, default &#x3D; 1). | [optional] 
**trigger_minute** | **int** | Minute of the hour on which to trigger (0 - 59, default &#x3D; 0). | [optional] 
**trigger_datetime** | **datetime** | Trigger date and time (YYYY-MM-DD HH:MM:SS). | [optional] 
**fields** | [**List[SystemAutomationTriggerNameGet200ResponseFieldsInner]**](SystemAutomationTriggerNameGet200ResponseFieldsInner.md) | Customized trigger field settings. | [optional] 
**faz_event_name** | **str** | FortiAnalyzer event handler name. | [optional] 
**faz_event_severity** | **str** | FortiAnalyzer event severity. | [optional] 
**faz_event_tags** | **str** | FortiAnalyzer event tags. | [optional] 
**serial** | **str** | Fabric connector serial number. | [optional] 
**fabric_event_name** | **str** | Fabric connector event handler name. | [optional] 
**fabric_event_severity** | **str** | Fabric connector event severity. | [optional] 

## Example

```python
from microlab_fortinet.models.system_automation_trigger_name_get200_response import SystemAutomationTriggerNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAutomationTriggerNameGet200Response from a JSON string
system_automation_trigger_name_get200_response_instance = SystemAutomationTriggerNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAutomationTriggerNameGet200Response.to_json())

# convert the object into a dict
system_automation_trigger_name_get200_response_dict = system_automation_trigger_name_get200_response_instance.to_dict()
# create an instance of SystemAutomationTriggerNameGet200Response from a dict
system_automation_trigger_name_get200_response_from_dict = SystemAutomationTriggerNameGet200Response.from_dict(system_automation_trigger_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


