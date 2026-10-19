# WirelessControllerMpskProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | MPSK profile name. | [optional] 
**mpsk_concurrent_clients** | **int** | Maximum number of concurrent clients that connect using the same passphrase in multiple PSK authentication (0 - 65535, default &#x3D; 0, meaning no limitation). | [optional] 
**mpsk_external_server_auth** | **str** | Enable/Disable MPSK external server authentication (default &#x3D; disable).    enable:Enable MPSK external server authentication.    disable:Disable MPSK external server authentication. | [optional] 
**mpsk_external_server** | **str** | RADIUS server to be used to authenticate MPSK users. | [optional] 
**mpsk_type** | **str** | Select the security type of keys for this profile.    wpa2-personal:WPA2 personal.    wpa3-sae:WPA3 SAE.    wpa3-sae-transition:WPA3 SAE transition. | [optional] 
**mpsk_group** | [**List[WirelessControllerMpskProfileNameGet200ResponseMpskGroupInner]**](WirelessControllerMpskProfileNameGet200ResponseMpskGroupInner.md) | List of multiple PSK groups. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_mpsk_profile_name_get200_response import WirelessControllerMpskProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerMpskProfileNameGet200Response from a JSON string
wireless_controller_mpsk_profile_name_get200_response_instance = WirelessControllerMpskProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerMpskProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_mpsk_profile_name_get200_response_dict = wireless_controller_mpsk_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerMpskProfileNameGet200Response from a dict
wireless_controller_mpsk_profile_name_get200_response_from_dict = WirelessControllerMpskProfileNameGet200Response.from_dict(wireless_controller_mpsk_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


