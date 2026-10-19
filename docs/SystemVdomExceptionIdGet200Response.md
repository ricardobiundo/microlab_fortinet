# SystemVdomExceptionIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Index (1 - 4096). | [optional] 
**object** | **str** | Name of the configuration object that can be configured independently for all VDOMs.    log.fortianalyzer.setting:log.fortianalyzer.setting    log.fortianalyzer.override-setting:log.fortianalyzer.override-setting    log.fortianalyzer2.setting:log.fortianalyzer2.setting    log.fortianalyzer2.override-setting:log.fortianalyzer2.override-setting    log.fortianalyzer3.setting:log.fortianalyzer3.setting    log.fortianalyzer3.override-setting:log.fortianalyzer3.override-setting    log.fortianalyzer-cloud.setting:log.fortianalyzer-cloud.setting    log.fortianalyzer-cloud.override-setting:log.fortianalyzer-cloud.override-setting    log.syslogd.setting:log.syslogd.setting    log.syslogd.override-setting:log.syslogd.override-setting    log.syslogd2.setting:log.syslogd2.setting    log.syslogd2.override-setting:log.syslogd2.override-setting    log.syslogd3.setting:log.syslogd3.setting    log.syslogd3.override-setting:log.syslogd3.override-setting    log.syslogd4.setting:log.syslogd4.setting    log.syslogd4.override-setting:log.syslogd4.override-setting    system.gre-tunnel:system.gre-tunnel    system.central-management:system.central-management    system.csf:system.csf    user.radius:user.radius    system.interface:system.interface    log.syslogd.setting:log.syslogd.setting    log.syslogd.override-setting:log.syslogd.override-setting    firewall.address:firewall.address    system.snmp.sysinfo:system.snmp.sysinfo | [optional] 
**scope** | **str** | Determine whether the configuration object can be configured separately for all VDOMs or if some VDOMs share the same configuration.    all:Object configuration independent for all VDOMs.    inclusive:Object configuration independent for the listed VDOMs. Other VDOMs use the global configuration.    exclusive:Use the global object configuration for the listed VDOMs. Other VDOMs can be configured independently. | [optional] 
**vdom** | [**List[SystemSnmpCommunityIdGet200ResponseVdomsInner]**](SystemSnmpCommunityIdGet200ResponseVdomsInner.md) | Names of the VDOMs. | [optional] 

## Example

```python
from microlab_fortinet.models.system_vdom_exception_id_get200_response import SystemVdomExceptionIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVdomExceptionIdGet200Response from a JSON string
system_vdom_exception_id_get200_response_instance = SystemVdomExceptionIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemVdomExceptionIdGet200Response.to_json())

# convert the object into a dict
system_vdom_exception_id_get200_response_dict = system_vdom_exception_id_get200_response_instance.to_dict()
# create an instance of SystemVdomExceptionIdGet200Response from a dict
system_vdom_exception_id_get200_response_from_dict = SystemVdomExceptionIdGet200Response.from_dict(system_vdom_exception_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


