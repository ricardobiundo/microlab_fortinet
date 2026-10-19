# SwitchControllerTrafficSnifferGet200ResponseTargetPortInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**switch_id** | **str** | Managed-switch ID. | [optional] 
**description** | **str** | Description for the sniffer port entry. | [optional] 
**in_ports** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner.md) | Configure source ingress port interfaces. | [optional] 
**out_ports** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner.md) | Configure source egress port interfaces. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_traffic_sniffer_get200_response_target_port_inner import SwitchControllerTrafficSnifferGet200ResponseTargetPortInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerTrafficSnifferGet200ResponseTargetPortInner from a JSON string
switch_controller_traffic_sniffer_get200_response_target_port_inner_instance = SwitchControllerTrafficSnifferGet200ResponseTargetPortInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerTrafficSnifferGet200ResponseTargetPortInner.to_json())

# convert the object into a dict
switch_controller_traffic_sniffer_get200_response_target_port_inner_dict = switch_controller_traffic_sniffer_get200_response_target_port_inner_instance.to_dict()
# create an instance of SwitchControllerTrafficSnifferGet200ResponseTargetPortInner from a dict
switch_controller_traffic_sniffer_get200_response_target_port_inner_from_dict = SwitchControllerTrafficSnifferGet200ResponseTargetPortInner.from_dict(switch_controller_traffic_sniffer_get200_response_target_port_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


