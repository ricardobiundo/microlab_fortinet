# WirelessControllerMpskProfileNameGet200ResponseMpskGroupInnerMpskKeyInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Pre-shared key name. | [optional] 
**key_type** | **str** | Select the type of the key.    wpa2-personal:WPA2 personal.    wpa3-sae:WPA3 SAE. | [optional] 
**mac** | **str** | MAC address. | [optional] 
**passphrase** | **str** | WPA Pre-shared key. | [optional] 
**sae_password** | **str** | WPA3 SAE password. | [optional] 
**sae_pk** | **str** | Enable/disable WPA3 SAE-PK (default &#x3D; disable).    enable:Enable WPA3 SAE-PK.    disable:Disable WPA3 SAE-PK. | [optional] 
**sae_private_key** | **str** | Private key used for WPA3 SAE-PK authentication. | [optional] 
**concurrent_client_limit_type** | **str** | MPSK client limit type options.    default:Using the value in profile configuration.    unlimited:Unlimited.    specified:Specified value. | [optional] 
**concurrent_clients** | **int** | Number of clients that can connect using this pre-shared key (1 - 65535, default is 256). | [optional] 
**comment** | **str** | Comment. | [optional] 
**mpsk_schedules** | [**List[WirelessControllerArrpProfileNameGet200ResponseDarrpOptimizeSchedulesInner]**](WirelessControllerArrpProfileNameGet200ResponseDarrpOptimizeSchedulesInner.md) | Firewall schedule for MPSK passphrase. The passphrase will be effective only when at least one schedule is valid. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_mpsk_profile_name_get200_response_mpsk_group_inner_mpsk_key_inner import WirelessControllerMpskProfileNameGet200ResponseMpskGroupInnerMpskKeyInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerMpskProfileNameGet200ResponseMpskGroupInnerMpskKeyInner from a JSON string
wireless_controller_mpsk_profile_name_get200_response_mpsk_group_inner_mpsk_key_inner_instance = WirelessControllerMpskProfileNameGet200ResponseMpskGroupInnerMpskKeyInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerMpskProfileNameGet200ResponseMpskGroupInnerMpskKeyInner.to_json())

# convert the object into a dict
wireless_controller_mpsk_profile_name_get200_response_mpsk_group_inner_mpsk_key_inner_dict = wireless_controller_mpsk_profile_name_get200_response_mpsk_group_inner_mpsk_key_inner_instance.to_dict()
# create an instance of WirelessControllerMpskProfileNameGet200ResponseMpskGroupInnerMpskKeyInner from a dict
wireless_controller_mpsk_profile_name_get200_response_mpsk_group_inner_mpsk_key_inner_from_dict = WirelessControllerMpskProfileNameGet200ResponseMpskGroupInnerMpskKeyInner.from_dict(wireless_controller_mpsk_profile_name_get200_response_mpsk_group_inner_mpsk_key_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


