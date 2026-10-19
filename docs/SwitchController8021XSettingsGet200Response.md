# SwitchController8021XSettingsGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**link_down_auth** | **str** | Interface-reauthentication state to set if a link is down.    set-unauth:Interface set to unauth when down. Reauthentication is needed.    no-action:Interface reauthentication is not needed. | [optional] 
**reauth_period** | **int** | Period of time to allow for reauthentication (1 - 1440 sec, default &#x3D; 60, 0 &#x3D; disable reauthentication). | [optional] 
**max_reauth_attempt** | **int** | Maximum number of authentication attempts (0 - 15, default &#x3D; 3). | [optional] 
**tx_period** | **int** | 802.1X Tx period (seconds, default&#x3D;30). | [optional] 
**mab_reauth** | **str** | Enable/disable MAB re-authentication.    disable:Disable MAB re-authentication.    enable:Enable MAB re-authentication. | [optional] 
**mac_username_delimiter** | **str** | MAC authentication username delimiter (default &#x3D; hyphen).    colon:Use colon as delimiter for MAC auth username.    hyphen:Use hyphen as delimiter for MAC auth username.    none:No delimiter for MAC auth username.    single-hyphen:Use single hyphen as delimiter for MAC auth username. | [optional] 
**mac_password_delimiter** | **str** | MAC authentication password delimiter (default &#x3D; hyphen).    colon:Use colon as delimiter for MAC auth password.    hyphen:Use hyphen as delimiter for MAC auth password.    none:No delimiter for MAC auth password.    single-hyphen:Use single hyphen as delimiter for MAC auth password. | [optional] 
**mac_calling_station_delimiter** | **str** | MAC calling station delimiter (default &#x3D; hyphen).    colon:Use colon as delimiter for calling station.    hyphen:Use hyphen as delimiter for calling station.    none:No delimiter for calling station.    single-hyphen:Use single hyphen as delimiter for calling station. | [optional] 
**mac_called_station_delimiter** | **str** | MAC called station delimiter (default &#x3D; hyphen).    colon:Use colon as delimiter for called station.    hyphen:Use hyphen as delimiter for called station.    none:No delimiter for called station.    single-hyphen:Use single hyphen as delimiter for called station. | [optional] 
**mac_case** | **str** | MAC case (default &#x3D; lowercase).    lowercase:Use lowercase MAC.    uppercase:Use uppercase MAC. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller8021_x_settings_get200_response import SwitchController8021XSettingsGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchController8021XSettingsGet200Response from a JSON string
switch_controller8021_x_settings_get200_response_instance = SwitchController8021XSettingsGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchController8021XSettingsGet200Response.to_json())

# convert the object into a dict
switch_controller8021_x_settings_get200_response_dict = switch_controller8021_x_settings_get200_response_instance.to_dict()
# create an instance of SwitchController8021XSettingsGet200Response from a dict
switch_controller8021_x_settings_get200_response_from_dict = SwitchController8021XSettingsGet200Response.from_dict(switch_controller8021_x_settings_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


