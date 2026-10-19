# SwitchControllerLldpProfileNameGet200ResponseCustomTlvsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | TLV name (not sent). | [optional] 
**oui** | **str** | Organizationally unique identifier (OUI), a 3-byte hexadecimal number, for this TLV. | [optional] 
**subtype** | **int** | Organizationally defined subtype (0 - 255). | [optional] 
**information_string** | **str** | Organizationally defined information string (0 - 507 hexadecimal bytes). | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_lldp_profile_name_get200_response_custom_tlvs_inner import SwitchControllerLldpProfileNameGet200ResponseCustomTlvsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerLldpProfileNameGet200ResponseCustomTlvsInner from a JSON string
switch_controller_lldp_profile_name_get200_response_custom_tlvs_inner_instance = SwitchControllerLldpProfileNameGet200ResponseCustomTlvsInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerLldpProfileNameGet200ResponseCustomTlvsInner.to_json())

# convert the object into a dict
switch_controller_lldp_profile_name_get200_response_custom_tlvs_inner_dict = switch_controller_lldp_profile_name_get200_response_custom_tlvs_inner_instance.to_dict()
# create an instance of SwitchControllerLldpProfileNameGet200ResponseCustomTlvsInner from a dict
switch_controller_lldp_profile_name_get200_response_custom_tlvs_inner_from_dict = SwitchControllerLldpProfileNameGet200ResponseCustomTlvsInner.from_dict(switch_controller_lldp_profile_name_get200_response_custom_tlvs_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


