# WirelessControllerAccessControlListNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | AP access control list name. | [optional] 
**comment** | **str** | Description. | [optional] 
**layer3_ipv4_rules** | [**List[WirelessControllerAccessControlListNameGet200ResponseLayer3Ipv4RulesInner]**](WirelessControllerAccessControlListNameGet200ResponseLayer3Ipv4RulesInner.md) | AP ACL layer3 ipv4 rule list. | [optional] 
**layer3_ipv6_rules** | [**List[WirelessControllerAccessControlListNameGet200ResponseLayer3Ipv6RulesInner]**](WirelessControllerAccessControlListNameGet200ResponseLayer3Ipv6RulesInner.md) | AP ACL layer3 ipv6 rule list. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_access_control_list_name_get200_response import WirelessControllerAccessControlListNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerAccessControlListNameGet200Response from a JSON string
wireless_controller_access_control_list_name_get200_response_instance = WirelessControllerAccessControlListNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerAccessControlListNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_access_control_list_name_get200_response_dict = wireless_controller_access_control_list_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerAccessControlListNameGet200Response from a dict
wireless_controller_access_control_list_name_get200_response_from_dict = WirelessControllerAccessControlListNameGet200Response.from_dict(wireless_controller_access_control_list_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


