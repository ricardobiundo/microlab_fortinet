# WirelessControllerVapNameGet200ResponseVlanNameInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | VLAN name. | [optional] 
**vlan_id** | **int** | VLAN IDs (maximum 8 VLAN IDs). | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_vap_name_get200_response_vlan_name_inner import WirelessControllerVapNameGet200ResponseVlanNameInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerVapNameGet200ResponseVlanNameInner from a JSON string
wireless_controller_vap_name_get200_response_vlan_name_inner_instance = WirelessControllerVapNameGet200ResponseVlanNameInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerVapNameGet200ResponseVlanNameInner.to_json())

# convert the object into a dict
wireless_controller_vap_name_get200_response_vlan_name_inner_dict = wireless_controller_vap_name_get200_response_vlan_name_inner_instance.to_dict()
# create an instance of WirelessControllerVapNameGet200ResponseVlanNameInner from a dict
wireless_controller_vap_name_get200_response_vlan_name_inner_from_dict = WirelessControllerVapNameGet200ResponseVlanNameInner.from_dict(wireless_controller_vap_name_get200_response_vlan_name_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


