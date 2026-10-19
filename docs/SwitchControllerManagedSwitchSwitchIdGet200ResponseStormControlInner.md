# SwitchControllerManagedSwitchSwitchIdGet200ResponseStormControlInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**local_override** | **str** | Enable to override global FortiSwitch storm control settings for this FortiSwitch.    enable:Override global storm control settings.    disable:Use global storm control settings. | [optional] 
**rate** | **int** | Rate in packets per second at which storm control drops excess traffic(0-10000000, default&#x3D;500, drop-all&#x3D;0). | [optional] 
**burst_size_level** | **int** | Increase level to handle bursty traffic (0 - 4, default &#x3D; 0). | [optional] 
**unknown_unicast** | **str** | Enable/disable storm control to drop unknown unicast traffic.    enable:Drop unknown unicast traffic.    disable:Allow unknown unicast traffic. | [optional] 
**unknown_multicast** | **str** | Enable/disable storm control to drop unknown multicast traffic.    enable:Drop unknown multicast traffic.    disable:Allow unknown multicast traffic. | [optional] 
**broadcast** | **str** | Enable/disable storm control to drop broadcast traffic.    enable:Drop broadcast traffic.    disable:Allow broadcast traffic. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_storm_control_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseStormControlInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseStormControlInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_storm_control_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseStormControlInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseStormControlInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_storm_control_inner_dict = switch_controller_managed_switch_switch_id_get200_response_storm_control_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseStormControlInner from a dict
switch_controller_managed_switch_switch_id_get200_response_storm_control_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseStormControlInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_storm_control_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


