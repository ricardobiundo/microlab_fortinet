# SwitchControllerStpInstanceIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Instance ID. | [optional] 
**vlan_range** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerAllowedVlansInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponsePortsInnerAllowedVlansInner.md) | Configure VLAN range for STP instance. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_stp_instance_id_get200_response import SwitchControllerStpInstanceIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerStpInstanceIdGet200Response from a JSON string
switch_controller_stp_instance_id_get200_response_instance = SwitchControllerStpInstanceIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerStpInstanceIdGet200Response.to_json())

# convert the object into a dict
switch_controller_stp_instance_id_get200_response_dict = switch_controller_stp_instance_id_get200_response_instance.to_dict()
# create an instance of SwitchControllerStpInstanceIdGet200Response from a dict
switch_controller_stp_instance_id_get200_response_from_dict = SwitchControllerStpInstanceIdGet200Response.from_dict(switch_controller_stp_instance_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


