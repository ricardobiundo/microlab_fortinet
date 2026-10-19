# WirelessControllerHotspot20H2qpOsuProviderNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | OSU provider ID. | [optional] 
**friendly_name** | [**List[WirelessControllerHotspot20H2qpOsuProviderNameGet200ResponseFriendlyNameInner]**](WirelessControllerHotspot20H2qpOsuProviderNameGet200ResponseFriendlyNameInner.md) | OSU provider friendly name. | [optional] 
**server_uri** | **str** | Server URI. | [optional] 
**osu_method** | **str** | OSU method list.    oma-dm:OMA DM.    soap-xml-spp:SOAP XML SPP.    reserved:Reserved. | [optional] 
**osu_nai** | **str** | OSU NAI. | [optional] 
**service_description** | [**List[WirelessControllerHotspot20H2qpOsuProviderNameGet200ResponseServiceDescriptionInner]**](WirelessControllerHotspot20H2qpOsuProviderNameGet200ResponseServiceDescriptionInner.md) | OSU service name. | [optional] 
**icon** | **str** | OSU provider icon. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_h2qp_osu_provider_name_get200_response import WirelessControllerHotspot20H2qpOsuProviderNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20H2qpOsuProviderNameGet200Response from a JSON string
wireless_controller_hotspot20_h2qp_osu_provider_name_get200_response_instance = WirelessControllerHotspot20H2qpOsuProviderNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20H2qpOsuProviderNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_hotspot20_h2qp_osu_provider_name_get200_response_dict = wireless_controller_hotspot20_h2qp_osu_provider_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerHotspot20H2qpOsuProviderNameGet200Response from a dict
wireless_controller_hotspot20_h2qp_osu_provider_name_get200_response_from_dict = WirelessControllerHotspot20H2qpOsuProviderNameGet200Response.from_dict(wireless_controller_hotspot20_h2qp_osu_provider_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


