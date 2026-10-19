# SwitchControllerManagedSwitchSwitchIdGet200Response8021XSettingsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**local_override** | **str** | Enable to override global 802.1X settings on individual FortiSwitches.    enable:Override global 802.1X settings.    disable:Use global 802.1X settings. | [optional] 
**link_down_auth** | **str** | Authentication state to set if a link is down.    set-unauth:Interface set to unauth when down. Reauthentication is needed.    no-action:Interface reauthentication is not needed. | [optional] 
**reauth_period** | **int** | Reauthentication time interval (1 - 1440 min, default &#x3D; 60, 0 &#x3D; disable). | [optional] 
**max_reauth_attempt** | **int** | Maximum number of authentication attempts (0 - 15, default &#x3D; 3). | [optional] 
**tx_period** | **int** | 802.1X Tx period (seconds, default&#x3D;30). | [optional] 
**mab_reauth** | **str** | Enable or disable MAB reauthentication settings.    disable:Disable MAB re-authentication setttings.    enable:Enable MAB re-authentication setttings. | [optional] 
**mac_username_delimiter** | **str** | MAC authentication username delimiter (default &#x3D; hyphen).    colon:Use colon as delimiter for MAC auth username.    hyphen:Use hyphen as delimiter for MAC auth username.    none:No delimiter for MAC auth username.    single-hyphen:Use single hyphen as delimiter for MAC auth username. | [optional] 
**mac_password_delimiter** | **str** | MAC authentication password delimiter (default &#x3D; hyphen).    colon:Use colon as delimiter for MAC auth password.    hyphen:Use hyphen as delimiter for MAC auth password.    none:No delimiter for MAC auth password.    single-hyphen:Use single hyphen as delimiter for MAC auth password. | [optional] 
**mac_calling_station_delimiter** | **str** | MAC calling station delimiter (default &#x3D; hyphen).    colon:Use colon as delimiter for calling station.    hyphen:Use hyphen as delimiter for calling station.    none:No delimiter for calling station.    single-hyphen:Use single hyphen as delimiter for calling station. | [optional] 
**mac_called_station_delimiter** | **str** | MAC called station delimiter (default &#x3D; hyphen).    colon:Use colon as delimiter for called station.    hyphen:Use hyphen as delimiter for called station.    none:No delimiter for called station.    single-hyphen:Use single hyphen as delimiter for called station. | [optional] 
**mac_case** | **str** | MAC case (default &#x3D; lowercase).    lowercase:Use lowercase MAC.    uppercase:Use uppercase MAC. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response8021_x_settings_inner import SwitchControllerManagedSwitchSwitchIdGet200Response8021XSettingsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200Response8021XSettingsInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response8021_x_settings_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200Response8021XSettingsInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200Response8021XSettingsInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response8021_x_settings_inner_dict = switch_controller_managed_switch_switch_id_get200_response8021_x_settings_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200Response8021XSettingsInner from a dict
switch_controller_managed_switch_switch_id_get200_response8021_x_settings_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200Response8021XSettingsInner.from_dict(switch_controller_managed_switch_switch_id_get200_response8021_x_settings_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


