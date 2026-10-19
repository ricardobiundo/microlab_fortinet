# SystemInterfaceNameGet200ResponsePhySettingInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**signal_ok_threshold** | **int** | Configure the signal strength value at which the FortiGate unit detects that the receiving signal is idle or that data is not being received. Zero means idle detection is disabled. Higher values mean the signal strength must be higher in order for the FortiGate unit to consider the interface is not idle (0 - 12, default &#x3D; 0). | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_phy_setting_inner import SystemInterfaceNameGet200ResponsePhySettingInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponsePhySettingInner from a JSON string
system_interface_name_get200_response_phy_setting_inner_instance = SystemInterfaceNameGet200ResponsePhySettingInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponsePhySettingInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_phy_setting_inner_dict = system_interface_name_get200_response_phy_setting_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponsePhySettingInner from a dict
system_interface_name_get200_response_phy_setting_inner_from_dict = SystemInterfaceNameGet200ResponsePhySettingInner.from_dict(system_interface_name_get200_response_phy_setting_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


