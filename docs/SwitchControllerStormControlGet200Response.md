# SwitchControllerStormControlGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rate** | **int** | Rate in packets per second at which storm control drops excess traffic(0-10000000, default&#x3D;500, drop-all&#x3D;0). | [optional] 
**burst_size_level** | **int** | Increase level to handle bursty traffic (0 - 4, default &#x3D; 0). | [optional] 
**unknown_unicast** | **str** | Enable/disable storm control to drop unknown unicast traffic.    enable:Enable unknown unicast storm control.    disable:Disable unknown unicast storm control. | [optional] 
**unknown_multicast** | **str** | Enable/disable storm control to drop unknown multicast traffic.    enable:Enable unknown multicast storm control.    disable:Disable unknown multicast storm control. | [optional] 
**broadcast** | **str** | Enable/disable storm control to drop broadcast traffic.    enable:Enable broadcast storm control.    disable:Disable broadcast storm control. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_storm_control_get200_response import SwitchControllerStormControlGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerStormControlGet200Response from a JSON string
switch_controller_storm_control_get200_response_instance = SwitchControllerStormControlGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerStormControlGet200Response.to_json())

# convert the object into a dict
switch_controller_storm_control_get200_response_dict = switch_controller_storm_control_get200_response_instance.to_dict()
# create an instance of SwitchControllerStormControlGet200Response from a dict
switch_controller_storm_control_get200_response_from_dict = SwitchControllerStormControlGet200Response.from_dict(switch_controller_storm_control_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


