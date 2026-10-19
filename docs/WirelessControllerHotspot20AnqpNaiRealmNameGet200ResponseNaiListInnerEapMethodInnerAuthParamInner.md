# WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInnerAuthParamInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**index** | **int** | Param index. | [optional] 
**id** | **str** | ID of authentication parameter.    non-eap-inner-auth:Non-EAP inner authentication type.    inner-auth-eap:Inner authentication EAP method type.    credential:Credential type.    tunneled-credential:Tunneled EAP method credential type. | [optional] 
**val** | **str** | Value of authentication parameter.    eap-identity:EAP Identity.    eap-md5:EAP MD5.    eap-tls:EAP TLS.    eap-ttls:EAP TTLS.    eap-peap:EAP PEAP.    eap-sim:EAP SIM.    eap-aka:EAP AKA.    eap-aka-prime:EAP AKA&#39;.    non-eap-pap:Non EAP PAP.    non-eap-chap:Non EAP CHAP.    non-eap-mschap:Non EAP MSCHAP.    non-eap-mschapv2:Non EAP MSCHAPV2.    cred-sim:Credential SIM.    cred-usim:Credential USIM.    cred-nfc:Credential NFC secure element.    cred-hardware-token:Credential hardware token.    cred-softoken:Credential softoken.    cred-certificate:Credential certificate.    cred-user-pwd:Credential username password.    cred-none:Credential none.    cred-vendor-specific:Credential vendor specific.    tun-cred-sim:Tunneled credential SIM.    tun-cred-usim:Tunneled credential USIM.    tun-cred-nfc:Tunneled credential NFC secure element.    tun-cred-hardware-token:Tunneled credential hardware token.    tun-cred-softoken:Tunneled credential softoken.    tun-cred-certificate:Tunneled credential certificate.    tun-cred-user-pwd:Tunneled credential username password.    tun-cred-anonymous:Tunneled credential anonymous.    tun-cred-vendor-specific:Tunneled credential vendor specific. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_eap_method_inner_auth_param_inner import WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInnerAuthParamInner

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInnerAuthParamInner from a JSON string
wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_eap_method_inner_auth_param_inner_instance = WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInnerAuthParamInner.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInnerAuthParamInner.to_json())

# convert the object into a dict
wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_eap_method_inner_auth_param_inner_dict = wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_eap_method_inner_auth_param_inner_instance.to_dict()
# create an instance of WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInnerAuthParamInner from a dict
wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_eap_method_inner_auth_param_inner_from_dict = WirelessControllerHotspot20AnqpNaiRealmNameGet200ResponseNaiListInnerEapMethodInnerAuthParamInner.from_dict(wireless_controller_hotspot20_anqp_nai_realm_name_get200_response_nai_list_inner_eap_method_inner_auth_param_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


