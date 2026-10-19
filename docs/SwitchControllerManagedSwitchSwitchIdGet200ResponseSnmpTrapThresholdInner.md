# SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpTrapThresholdInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**trap_high_cpu_threshold** | **int** | CPU usage when trap is sent. | [optional] 
**trap_low_memory_threshold** | **int** | Memory usage when trap is sent. | [optional] 
**trap_log_full_threshold** | **int** | Log disk usage when trap is sent. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_snmp_trap_threshold_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpTrapThresholdInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpTrapThresholdInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_snmp_trap_threshold_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpTrapThresholdInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpTrapThresholdInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_snmp_trap_threshold_inner_dict = switch_controller_managed_switch_switch_id_get200_response_snmp_trap_threshold_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpTrapThresholdInner from a dict
switch_controller_managed_switch_switch_id_get200_response_snmp_trap_threshold_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseSnmpTrapThresholdInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_snmp_trap_threshold_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


