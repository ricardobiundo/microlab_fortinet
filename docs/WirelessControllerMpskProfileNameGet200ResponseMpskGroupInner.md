# WirelessControllerMpskProfileNameGet200ResponseMpskGroupInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | MPSK group name. | [optional] 
**vlan_type** | **str** | MPSK group VLAN options.    no-vlan:No VLAN.    fixed-vlan:Fixed VLAN ID. | [optional] 
**vlan_id** | **int** | Optional VLAN ID. | [optional] 
**mpsk_key** | [**List[WirelessControllerMpskProfileNameGet200ResponseMpskGroupInnerMpskKeyInner]**](WirelessControllerMpskProfileNameGet200ResponseMpskGroupInnerMpskKeyInner.md) | List of multiple PSK entries. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_mpsk_profile_name_get200_response_mpsk_group_inner import WirelessControllerMpskProfileNameGet200ResponseMpskGroupInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerMpskProfileNameGet200ResponseMpskGroupInner from a JSON string
wireless_controller_mpsk_profile_name_get200_response_mpsk_group_inner_instance = WirelessControllerMpskProfileNameGet200ResponseMpskGroupInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerMpskProfileNameGet200ResponseMpskGroupInner.to_json())

# convert the object into a dict
wireless_controller_mpsk_profile_name_get200_response_mpsk_group_inner_dict = wireless_controller_mpsk_profile_name_get200_response_mpsk_group_inner_instance.to_dict()
# create an instance of WirelessControllerMpskProfileNameGet200ResponseMpskGroupInner from a dict
wireless_controller_mpsk_profile_name_get200_response_mpsk_group_inner_from_dict = WirelessControllerMpskProfileNameGet200ResponseMpskGroupInner.from_dict(wireless_controller_mpsk_profile_name_get200_response_mpsk_group_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


