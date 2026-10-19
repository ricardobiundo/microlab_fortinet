# SwitchControllerFortilinkSettingsNameGet200ResponseNacPortsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**onboarding_vlan** | **str** | Default NAC Onboarding VLAN when NAC devices are discovered. | [optional] 
**lan_segment** | **str** | Enable/disable LAN segment feature on the FortiLink interface.    enabled:Enable lan-segment on this interface.    disabled:Disable lan-segment on this interface. | [optional] 
**nac_lan_interface** | **str** | Configure NAC LAN interface. | [optional] 
**nac_segment_vlans** | [**List[SwitchControllerFortilinkSettingsNameGet200ResponseNacPortsInnerNacSegmentVlansInner]**](SwitchControllerFortilinkSettingsNameGet200ResponseNacPortsInnerNacSegmentVlansInner.md) | Configure NAC segment VLANs. | [optional] 
**parent_key** | **str** | Parent key name. | [optional] 
**member_change** | **int** | Member change flag. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_fortilink_settings_name_get200_response_nac_ports_inner import SwitchControllerFortilinkSettingsNameGet200ResponseNacPortsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerFortilinkSettingsNameGet200ResponseNacPortsInner from a JSON string
switch_controller_fortilink_settings_name_get200_response_nac_ports_inner_instance = SwitchControllerFortilinkSettingsNameGet200ResponseNacPortsInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerFortilinkSettingsNameGet200ResponseNacPortsInner.to_json())

# convert the object into a dict
switch_controller_fortilink_settings_name_get200_response_nac_ports_inner_dict = switch_controller_fortilink_settings_name_get200_response_nac_ports_inner_instance.to_dict()
# create an instance of SwitchControllerFortilinkSettingsNameGet200ResponseNacPortsInner from a dict
switch_controller_fortilink_settings_name_get200_response_nac_ports_inner_from_dict = SwitchControllerFortilinkSettingsNameGet200ResponseNacPortsInner.from_dict(switch_controller_fortilink_settings_name_get200_response_nac_ports_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


