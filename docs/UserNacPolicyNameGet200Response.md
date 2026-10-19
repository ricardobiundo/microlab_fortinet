# UserNacPolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | NAC policy name. | [optional] 
**description** | **str** | Description for the NAC policy matching pattern. | [optional] 
**category** | **str** | Category of NAC policy.    device:Device category.    firewall-user:Firewall user category.    ems-tag:EMS Tag category.    fortivoice-tag:FortiVoice Tag category.    vulnerability:Vulnerability category. | [optional] 
**status** | **str** | Enable/disable NAC policy.    enable:Enable NAC policy.    disable:Disable NAC policy. | [optional] 
**match_type** | **str** | Match and retain the devices based on the type.    dynamic:Matched devices will be removed on dynamic events like link-down,device-inactivity,switch-offline.    override:Matched devices will be retained until the match-period. | [optional] 
**match_period** | **int** | Number of days the matched devices will be retained (0 - always retain) | [optional] 
**match_remove** | **str** | Options to remove the matched override devices.    default:Remove the matched override devices based on the match period.    link-down:Remove the matched override devices based on switch port link down event. | [optional] 
**mac** | **str** | NAC policy matching MAC address. | [optional] 
**hw_vendor** | **str** | NAC policy matching hardware vendor. | [optional] 
**type** | **str** | NAC policy matching type. | [optional] 
**family** | **str** | NAC policy matching family. | [optional] 
**os** | **str** | NAC policy matching operating system. | [optional] 
**hw_version** | **str** | NAC policy matching hardware version. | [optional] 
**sw_version** | **str** | NAC policy matching software version. | [optional] 
**host** | **str** | NAC policy matching host. | [optional] 
**user** | **str** | NAC policy matching user. | [optional] 
**src** | **str** | NAC policy matching source. | [optional] 
**user_group** | **str** | NAC policy matching user group. | [optional] 
**ems_tag** | **str** | NAC policy matching EMS tag. | [optional] 
**fortivoice_tag** | **str** | NAC policy matching FortiVoice tag. | [optional] 
**severity** | [**List[UserNacPolicyNameGet200ResponseSeverityInner]**](UserNacPolicyNameGet200ResponseSeverityInner.md) | NAC policy matching devices vulnerability severity lists. | [optional] 
**switch_fortilink** | **str** | FortiLink interface for which this NAC policy belongs to. | [optional] 
**switch_group** | [**List[UserNacPolicyNameGet200ResponseSwitchGroupInner]**](UserNacPolicyNameGet200ResponseSwitchGroupInner.md) | List of managed FortiSwitch groups on which NAC policy can be applied. | [optional] 
**switch_mac_policy** | **str** | Switch MAC policy action to be applied on the matched NAC policy. | [optional] 
**firewall_address** | **str** | Dynamic firewall address to associate MAC which match this policy. | [optional] 
**ssid_policy** | **str** | SSID policy to be applied on the matched NAC policy. | [optional] 

## Example

```python
from microlab_fortinet.models.user_nac_policy_name_get200_response import UserNacPolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserNacPolicyNameGet200Response from a JSON string
user_nac_policy_name_get200_response_instance = UserNacPolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserNacPolicyNameGet200Response.to_json())

# convert the object into a dict
user_nac_policy_name_get200_response_dict = user_nac_policy_name_get200_response_instance.to_dict()
# create an instance of UserNacPolicyNameGet200Response from a dict
user_nac_policy_name_get200_response_from_dict = UserNacPolicyNameGet200Response.from_dict(user_nac_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


