# WirelessControllerVapNameGet200ResponseVlanPoolInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**wtp_group** | [**List[WirelessControllerVapNameGet200ResponseVlanPoolInnerWtpGroupInner]**](WirelessControllerVapNameGet200ResponseVlanPoolInnerWtpGroupInner.md) | WTP group list(maximum 16 WTP groups). | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_vap_name_get200_response_vlan_pool_inner import WirelessControllerVapNameGet200ResponseVlanPoolInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerVapNameGet200ResponseVlanPoolInner from a JSON string
wireless_controller_vap_name_get200_response_vlan_pool_inner_instance = WirelessControllerVapNameGet200ResponseVlanPoolInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerVapNameGet200ResponseVlanPoolInner.to_json())

# convert the object into a dict
wireless_controller_vap_name_get200_response_vlan_pool_inner_dict = wireless_controller_vap_name_get200_response_vlan_pool_inner_instance.to_dict()
# create an instance of WirelessControllerVapNameGet200ResponseVlanPoolInner from a dict
wireless_controller_vap_name_get200_response_vlan_pool_inner_from_dict = WirelessControllerVapNameGet200ResponseVlanPoolInner.from_dict(wireless_controller_vap_name_get200_response_vlan_pool_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


