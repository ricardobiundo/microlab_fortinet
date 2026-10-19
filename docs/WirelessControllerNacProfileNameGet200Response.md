# WirelessControllerNacProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**onboarding_vlan** | **str** | VLAN interface name. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_nac_profile_name_get200_response import WirelessControllerNacProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerNacProfileNameGet200Response from a JSON string
wireless_controller_nac_profile_name_get200_response_instance = WirelessControllerNacProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerNacProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_nac_profile_name_get200_response_dict = wireless_controller_nac_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerNacProfileNameGet200Response from a dict
wireless_controller_nac_profile_name_get200_response_from_dict = WirelessControllerNacProfileNameGet200Response.from_dict(wireless_controller_nac_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


