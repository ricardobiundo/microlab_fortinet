# SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Mirror name. | [optional] 
**status** | **str** | Active/inactive mirror configuration.    active:Activate mirror configuration.    inactive:Deactivate mirror configuration. | [optional] 
**switching_packet** | **str** | Enable/disable switching functionality when mirroring.    enable:Enable switching functionality when mirroring.    disable:Disable switching functionality when mirroring. | [optional] 
**dst** | **str** | Destination port. | [optional] 
**src_ingress** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner.md) | Source ingress interfaces. | [optional] 
**src_egress** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInnerSrcIngressInner.md) | Source egress interfaces. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_mirror_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_mirror_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_mirror_inner_dict = switch_controller_managed_switch_switch_id_get200_response_mirror_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInner from a dict
switch_controller_managed_switch_switch_id_get200_response_mirror_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseMirrorInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_mirror_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


