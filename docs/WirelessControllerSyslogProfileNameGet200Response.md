# WirelessControllerSyslogProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | WTP system log server profile name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**server_status** | **str** | Enable/disable FortiAP units to send log messages to a syslog server (default &#x3D; enable).    enable:Enable syslog server.    disable:Disable syslog server. | [optional] 
**server** | **str** | Syslog server CN domain name or IP address. | [optional] 
**server_port** | **int** | Port number of syslog server that FortiAP units send log messages to (default &#x3D; 514). | [optional] 
**server_type** | **str** | Configure syslog server type (default &#x3D; standard).    standard:Standard syslog server hosted on an server endpoint.    fortianalyzer:Syslog server hosted on a FortiAnalyzer device. | [optional] 
**log_level** | **str** | Lowest level of log messages that FortiAP units send to this server (default &#x3D; information).    emergency:Level 0    alert:Level 1    critical:Level 2    error:Level 3    warning:Level 4    notification:Level 5    information:Level 6    debugging:Level 7 | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_syslog_profile_name_get200_response import WirelessControllerSyslogProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerSyslogProfileNameGet200Response from a JSON string
wireless_controller_syslog_profile_name_get200_response_instance = WirelessControllerSyslogProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerSyslogProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_syslog_profile_name_get200_response_dict = wireless_controller_syslog_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerSyslogProfileNameGet200Response from a dict
wireless_controller_syslog_profile_name_get200_response_from_dict = WirelessControllerSyslogProfileNameGet200Response.from_dict(wireless_controller_syslog_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


