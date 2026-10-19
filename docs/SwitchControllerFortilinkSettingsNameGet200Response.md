# SwitchControllerFortilinkSettingsNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | FortiLink settings name. | [optional] 
**fortilink** | **str** | FortiLink interface to which this fortilink-setting belongs. | [optional] 
**inactive_timer** | **int** | Time interval(minutes) to be included in the inactive devices expiry calculation (mac age-out + inactive-time + periodic scan interval). | [optional] 
**link_down_flush** | **str** | Clear NAC and dynamic devices on switch ports on link down event.    disable:Disable clearing NAC and dynamic devices on a switch port when link down event happens.    enable:Enable clearing NAC and dynamic devices on a switch port when link down event happens. | [optional] 
**access_vlan_mode** | **str** | Intra VLAN traffic behavior with loss of connection to the FortiGate.    legacy:Backward compatible behavior.    fail-open:When connection to FortiGate is lost, traffic on the VLAN may continue directly between end points.    fail-close:When connection to FortiGate is lost, traffic between endpoints on the VLAN is blocked. | [optional] 
**nac_ports** | [**List[SwitchControllerFortilinkSettingsNameGet200ResponseNacPortsInner]**](SwitchControllerFortilinkSettingsNameGet200ResponseNacPortsInner.md) | NAC specific configuration. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_fortilink_settings_name_get200_response import SwitchControllerFortilinkSettingsNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerFortilinkSettingsNameGet200Response from a JSON string
switch_controller_fortilink_settings_name_get200_response_instance = SwitchControllerFortilinkSettingsNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerFortilinkSettingsNameGet200Response.to_json())

# convert the object into a dict
switch_controller_fortilink_settings_name_get200_response_dict = switch_controller_fortilink_settings_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerFortilinkSettingsNameGet200Response from a dict
switch_controller_fortilink_settings_name_get200_response_from_dict = SwitchControllerFortilinkSettingsNameGet200Response.from_dict(switch_controller_fortilink_settings_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


