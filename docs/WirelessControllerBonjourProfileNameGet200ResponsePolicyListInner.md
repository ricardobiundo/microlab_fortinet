# WirelessControllerBonjourProfileNameGet200ResponsePolicyListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**policy_id** | **int** | Policy ID. | [optional] 
**description** | **str** | Description. | [optional] 
**from_vlan** | **str** | VLAN ID from which the Bonjour service is advertised (0 - 4094, default &#x3D; 0). | [optional] 
**to_vlan** | **str** | VLAN ID to which the Bonjour service is made available (0 - 4094, default &#x3D; all). | [optional] 
**services** | **str** | Bonjour services for the VLAN connecting to the Bonjour network.    all:All services.    airplay:AirPlay.    afp:AFP (Apple File Sharing).    bit-torrent:BitTorrent.    ftp:FTP.    ichat:iChat.    itunes:iTunes.    printers:Printers.    samba:Samba.    scanners:Scanners.    ssh:SSH.    chromecast:ChromeCast.    miracast:Miracast. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_bonjour_profile_name_get200_response_policy_list_inner import WirelessControllerBonjourProfileNameGet200ResponsePolicyListInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerBonjourProfileNameGet200ResponsePolicyListInner from a JSON string
wireless_controller_bonjour_profile_name_get200_response_policy_list_inner_instance = WirelessControllerBonjourProfileNameGet200ResponsePolicyListInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerBonjourProfileNameGet200ResponsePolicyListInner.to_json())

# convert the object into a dict
wireless_controller_bonjour_profile_name_get200_response_policy_list_inner_dict = wireless_controller_bonjour_profile_name_get200_response_policy_list_inner_instance.to_dict()
# create an instance of WirelessControllerBonjourProfileNameGet200ResponsePolicyListInner from a dict
wireless_controller_bonjour_profile_name_get200_response_policy_list_inner_from_dict = WirelessControllerBonjourProfileNameGet200ResponsePolicyListInner.from_dict(wireless_controller_bonjour_profile_name_get200_response_policy_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


