# SwitchControllerInitialConfigVlansGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**optional_vlans** | **str** | Auto-generate pre-configured VLANs upon switch discovery.    enable:Enable auto-generated VLANs.    disable:Disable auto-generated VLANs. | [optional] 
**default_vlan** | **str** | Default VLAN (native) assigned to all switch ports upon discovery. | [optional] 
**quarantine** | **str** | VLAN for quarantined traffic. | [optional] 
**rspan** | **str** | VLAN for RSPAN/ERSPAN mirrored traffic. | [optional] 
**voice** | **str** | VLAN dedicated for voice devices. | [optional] 
**video** | **str** | VLAN dedicated for video devices. | [optional] 
**nac** | **str** | VLAN for NAC onboarding devices. | [optional] 
**nac_segment** | **str** | VLAN for NAC segment primary interface. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_initial_config_vlans_get200_response import SwitchControllerInitialConfigVlansGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerInitialConfigVlansGet200Response from a JSON string
switch_controller_initial_config_vlans_get200_response_instance = SwitchControllerInitialConfigVlansGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerInitialConfigVlansGet200Response.to_json())

# convert the object into a dict
switch_controller_initial_config_vlans_get200_response_dict = switch_controller_initial_config_vlans_get200_response_instance.to_dict()
# create an instance of SwitchControllerInitialConfigVlansGet200Response from a dict
switch_controller_initial_config_vlans_get200_response_from_dict = SwitchControllerInitialConfigVlansGet200Response.from_dict(switch_controller_initial_config_vlans_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


