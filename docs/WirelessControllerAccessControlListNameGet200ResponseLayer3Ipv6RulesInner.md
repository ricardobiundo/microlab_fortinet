# WirelessControllerAccessControlListNameGet200ResponseLayer3Ipv6RulesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rule_id** | **int** | Rule ID (1 - 65535). | [optional] 
**comment** | **str** | Description. | [optional] 
**srcaddr** | **str** | Source IPv6 address (any | local-LAN | IPv6 address[/prefix length]), default &#x3D; any. | [optional] 
**srcport** | **int** | Source port (0 - 65535, default &#x3D; 0, meaning any). | [optional] 
**dstaddr** | **str** | Destination IPv6 address (any | local-LAN | IPv6 address[/prefix length]), default &#x3D; any. | [optional] 
**dstport** | **int** | Destination port (0 - 65535, default &#x3D; 0, meaning any). | [optional] 
**protocol** | **int** | Protocol type as defined by IANA (0 - 255, default &#x3D; 255, meaning any). | [optional] 
**action** | **str** | Policy action (allow | deny).    allow:Allows traffic matching the policy.    deny:Blocks traffic matching the policy. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_access_control_list_name_get200_response_layer3_ipv6_rules_inner import WirelessControllerAccessControlListNameGet200ResponseLayer3Ipv6RulesInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerAccessControlListNameGet200ResponseLayer3Ipv6RulesInner from a JSON string
wireless_controller_access_control_list_name_get200_response_layer3_ipv6_rules_inner_instance = WirelessControllerAccessControlListNameGet200ResponseLayer3Ipv6RulesInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerAccessControlListNameGet200ResponseLayer3Ipv6RulesInner.to_json())

# convert the object into a dict
wireless_controller_access_control_list_name_get200_response_layer3_ipv6_rules_inner_dict = wireless_controller_access_control_list_name_get200_response_layer3_ipv6_rules_inner_instance.to_dict()
# create an instance of WirelessControllerAccessControlListNameGet200ResponseLayer3Ipv6RulesInner from a dict
wireless_controller_access_control_list_name_get200_response_layer3_ipv6_rules_inner_from_dict = WirelessControllerAccessControlListNameGet200ResponseLayer3Ipv6RulesInner.from_dict(wireless_controller_access_control_list_name_get200_response_layer3_ipv6_rules_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


