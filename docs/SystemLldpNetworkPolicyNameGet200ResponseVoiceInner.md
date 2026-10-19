# SystemLldpNetworkPolicyNameGet200ResponseVoiceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable advertising this policy.    disable:Disable advertising this LLDP network policy.    enable:Enable advertising this LLDP network policy. | [optional] 
**tag** | **str** | Advertise tagged or untagged traffic.    none:Advertise that untagged frames should be used.    dot1q:Advertise that 802.1Q (VLAN) tagging should be used.    dot1p:Advertise that 802.1P priority tagging (VLAN 0) should be used. | [optional] 
**vlan** | **int** | 802.1Q VLAN ID to advertise (1 - 4094). | [optional] 
**priority** | **int** | 802.1P CoS/PCP to advertise (0 - 7; from lowest to highest priority). | [optional] 
**dscp** | **int** | Differentiated Services Code Point (DSCP) value to advertise. | [optional] 

## Example

```python
from microlab_fortinet.models.system_lldp_network_policy_name_get200_response_voice_inner import SystemLldpNetworkPolicyNameGet200ResponseVoiceInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemLldpNetworkPolicyNameGet200ResponseVoiceInner from a JSON string
system_lldp_network_policy_name_get200_response_voice_inner_instance = SystemLldpNetworkPolicyNameGet200ResponseVoiceInner.from_json(json)
# print the JSON string representation of the object
print(SystemLldpNetworkPolicyNameGet200ResponseVoiceInner.to_json())

# convert the object into a dict
system_lldp_network_policy_name_get200_response_voice_inner_dict = system_lldp_network_policy_name_get200_response_voice_inner_instance.to_dict()
# create an instance of SystemLldpNetworkPolicyNameGet200ResponseVoiceInner from a dict
system_lldp_network_policy_name_get200_response_voice_inner_from_dict = SystemLldpNetworkPolicyNameGet200ResponseVoiceInner.from_dict(system_lldp_network_policy_name_get200_response_voice_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


