# WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**index** | **int** | EAP method index. | [optional] 
**method** | **str** | EAP method type.    eap-identity:Identity.    eap-md5:MD5.    eap-tls:TLS.    eap-ttls:TTLS.    eap-peap:PEAP.    eap-sim:SIM.    eap-aka:AKA.    eap-aka-prime:AKA&#39;. | [optional] 
**auth_param** | [**List[WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInnerAuthParamInner]**](WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInnerAuthParamInner.md) | EAP auth param. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_eap_method_inner import WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInner from a JSON string
wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_eap_method_inner_instance = WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInner.to_json())

# convert the object into a dict
wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_eap_method_inner_dict = wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_eap_method_inner_instance.to_dict()
# create an instance of WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInner from a dict
wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_eap_method_inner_from_dict = WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInner.from_dict(wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_eap_method_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


