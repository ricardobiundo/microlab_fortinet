# WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | NAI realm name. | [optional] 
**encoding** | **str** | Enable/disable format in accordance with IETF RFC 4282.    disable:Disable format in accordance with IETF RFC 4282.    enable:Enable format in accordance with IETF RFC 4282. | [optional] 
**nai_realm** | **str** | Configure NAI realms (delimited by a semi-colon character). | [optional] 
**eap_method** | [**List[WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInner]**](WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInner.md) | EAP Methods. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner import WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInner from a JSON string
wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_instance = WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInner.to_json())

# convert the object into a dict
wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_dict = wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_instance.to_dict()
# create an instance of WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInner from a dict
wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_from_dict = WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInner.from_dict(wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


