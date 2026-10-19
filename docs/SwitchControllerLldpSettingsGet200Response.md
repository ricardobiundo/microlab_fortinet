# SwitchControllerLldpSettingsGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tx_hold** | **int** | Number of tx-intervals before local LLDP data expires (1 - 16, default &#x3D; 4). Packet TTL is tx-hold * tx-interval. | [optional] 
**tx_interval** | **int** | Frequency of LLDP PDU transmission from FortiSwitch (5 - 4095 sec, default &#x3D; 30). Packet TTL is tx-hold * tx-interval. | [optional] 
**fast_start_interval** | **int** | Frequency of LLDP PDU transmission from FortiSwitch for the first 4 packets when the link is up (2 - 5 sec, default &#x3D; 2, 0 &#x3D; disable fast start). | [optional] 
**management_interface** | **str** | Primary management interface to be advertised in LLDP and CDP PDUs.    internal:Use internal interface.    mgmt:Use management interface. | [optional] 
**device_detection** | **str** | Enable/disable dynamic detection of LLDP neighbor devices for VLAN assignment.    disable:Disable dynamic detection of LLDP neighbor devices.    enable:Enable dynamic detection of LLDP neighbor devices. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_lldp_settings_get200_response import SwitchControllerLldpSettingsGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerLldpSettingsGet200Response from a JSON string
switch_controller_lldp_settings_get200_response_instance = SwitchControllerLldpSettingsGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerLldpSettingsGet200Response.to_json())

# convert the object into a dict
switch_controller_lldp_settings_get200_response_dict = switch_controller_lldp_settings_get200_response_instance.to_dict()
# create an instance of SwitchControllerLldpSettingsGet200Response from a dict
switch_controller_lldp_settings_get200_response_from_dict = SwitchControllerLldpSettingsGet200Response.from_dict(switch_controller_lldp_settings_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


