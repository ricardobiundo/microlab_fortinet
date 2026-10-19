# SwitchControllerManagedSwitchSwitchIdGet200ResponseStpInstanceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Instance ID. | [optional] 
**priority** | **str** | Priority.    0:0.    4096:4096.    8192:8192.    12288:12288.    16384:16384.    20480:20480.    24576:24576.    28672:28672.    32768:32768.    36864:36864.    40960:40960.    45056:45056.    49152:49152.    53248:53248.    57344:57344.    61440:61440. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_stp_instance_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseStpInstanceInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseStpInstanceInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_stp_instance_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseStpInstanceInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseStpInstanceInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_stp_instance_inner_dict = switch_controller_managed_switch_switch_id_get200_response_stp_instance_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseStpInstanceInner from a dict
switch_controller_managed_switch_switch_id_get200_response_stp_instance_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseStpInstanceInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_stp_instance_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


