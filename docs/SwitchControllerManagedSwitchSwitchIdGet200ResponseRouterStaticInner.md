# SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterStaticInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Entry sequence number. | [optional] 
**switch_id** | **str** | Switch ID. | [optional] 
**blackhole** | **str** | Enable/disable blackhole on this route.    disable:Disable blackhole on this route.    enable:Enable blackhole on this route. | [optional] 
**comment** | **str** | Comment. | [optional] 
**device** | **str** | Gateway out interface. | [optional] 
**distance** | **int** | Administrative distance for the route (1 - 255, default &#x3D; 10). | [optional] 
**dst** | **str** | Destination ip and mask for this route. | [optional] 
**dynamic_gateway** | **str** | Enable/disable dynamic gateway.    disable:Disable dynamic gateway on this route.    enable:Disable dynamic gateway on this route. | [optional] 
**gateway** | **str** | Gateway ip for this route. | [optional] 
**status** | **str** | Enable/disable route status.    disable:Disable route status.    enable:Enable route status. | [optional] 
**vrf** | **str** | VRF for this route. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_router_static_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterStaticInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterStaticInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_router_static_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterStaticInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterStaticInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_router_static_inner_dict = switch_controller_managed_switch_switch_id_get200_response_router_static_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterStaticInner from a dict
switch_controller_managed_switch_switch_id_get200_response_router_static_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterStaticInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_router_static_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


