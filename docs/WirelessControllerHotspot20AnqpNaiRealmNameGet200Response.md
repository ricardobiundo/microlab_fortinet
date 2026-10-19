# WirelessControllerHotspot20AnqpNaiRealmNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | NAI realm list name. | [optional] 
**nai_list** | [**List[WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInner]**](WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInner.md) | NAI list. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_anqp_nai_realm_name_get200_response import WirelessControllerHotspot20AnqpNaiRealmNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20AnqpNaiRealmNameGet200Response from a JSON string
wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_instance = WirelessControllerHotspot20AnqpNaiRealmNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20AnqpNaiRealmNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_dict = wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerHotspot20AnqpNaiRealmNameGet200Response from a dict
wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_from_dict = WirelessControllerHotspot20AnqpNaiRealmNameGet200Response.from_dict(wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


