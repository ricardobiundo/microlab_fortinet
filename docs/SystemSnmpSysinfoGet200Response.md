# SystemSnmpSysinfoGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable SNMP.    enable:Enable setting.    disable:Disable setting. | [optional] 
**engine_id_type** | **str** | Local SNMP engineID type (text/hex/mac).    text:Text format.    hex:Octets format.    mac:MAC address format. | [optional] 
**engine_id** | **str** | Local SNMP engineID string (maximum 27 characters). | [optional] 
**description** | **str** | System description. | [optional] 
**contact_info** | **str** | Contact information. | [optional] 
**location** | **str** | System location. | [optional] 
**trap_high_cpu_threshold** | **int** | CPU usage when trap is sent. | [optional] 
**trap_low_memory_threshold** | **int** | Memory usage when trap is sent. | [optional] 
**trap_log_full_threshold** | **int** | Log disk usage when trap is sent. | [optional] 
**trap_free_memory_threshold** | **int** | Free memory usage when trap is sent. | [optional] 
**trap_freeable_memory_threshold** | **int** | Freeable memory usage when trap is sent. | [optional] 
**append_index** | **str** | Enable/disable allowance of appending vdom or interface index in some RFC tables.    enable:Enable setting.    disable:Disable setting. | [optional] 
**non_mgmt_vdom_query** | **str** | Enable/disable allowance of SNMPv3 query from non-management vdoms.    enable:Enable setting.    disable:Disable setting. | [optional] 

## Example

```python
from microlab_fortinet.models.system_snmp_sysinfo_get200_response import SystemSnmpSysinfoGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSnmpSysinfoGet200Response from a JSON string
system_snmp_sysinfo_get200_response_instance = SystemSnmpSysinfoGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSnmpSysinfoGet200Response.to_json())

# convert the object into a dict
system_snmp_sysinfo_get200_response_dict = system_snmp_sysinfo_get200_response_instance.to_dict()
# create an instance of SystemSnmpSysinfoGet200Response from a dict
system_snmp_sysinfo_get200_response_from_dict = SystemSnmpSysinfoGet200Response.from_dict(system_snmp_sysinfo_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


