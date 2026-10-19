# SwitchControllerManagedSwitchSwitchIdGet200ResponseRemoteLogInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Remote log name. | [optional] 
**status** | **str** | Enable/disable logging by FortiSwitch device to a remote syslog server.    enable:Enable logging by FortiSwitch device to a remote syslog server.    disable:Disable logging by FortiSwitch device to a remote syslog server. | [optional] 
**server** | **str** | IPv4 address of the remote syslog server. | [optional] 
**port** | **int** | Remote syslog server listening port. | [optional] 
**severity** | **str** | Severity of logs to be transferred to remote log server.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 
**csv** | **str** | Enable/disable comma-separated value (CSV) strings.    enable:Enable comma-separated value (CSV) strings.    disable:Disable comma-separated value (CSV) strings. | [optional] 
**facility** | **str** | Facility to log to remote syslog server.    kernel:Kernel messages.    user:Random user-level messages.    mail:Mail system.    daemon:System daemons.    auth:Security/authorization messages.    syslog:Messages generated internally by syslogd.    lpr:Line printer subsystem.    news:Network news subsystem.    uucp:UUCP server messages.    cron:Clock daemon.    authpriv:Security/authorization messages (private).    ftp:FTP daemon.    ntp:NTP daemon.    audit:Log audit.    alert:Log alert.    clock:Clock daemon.    local0:Reserved for local use.    local1:Reserved for local use.    local2:Reserved for local use.    local3:Reserved for local use.    local4:Reserved for local use.    local5:Reserved for local use.    local6:Reserved for local use.    local7:Reserved for local use. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_remote_log_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseRemoteLogInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseRemoteLogInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_remote_log_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseRemoteLogInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseRemoteLogInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_remote_log_inner_dict = switch_controller_managed_switch_switch_id_get200_response_remote_log_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseRemoteLogInner from a dict
switch_controller_managed_switch_switch_id_get200_response_remote_log_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseRemoteLogInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_remote_log_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


