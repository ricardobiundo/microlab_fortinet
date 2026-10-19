# SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterVrfInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | VRF entry name. | [optional] 
**switch_id** | **str** | Switch ID. | [optional] 
**vrfid** | **int** | VRF ID. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_router_vrf_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterVrfInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterVrfInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_router_vrf_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterVrfInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterVrfInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_router_vrf_inner_dict = switch_controller_managed_switch_switch_id_get200_response_router_vrf_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterVrfInner from a dict
switch_controller_managed_switch_switch_id_get200_response_router_vrf_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseRouterVrfInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_router_vrf_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


