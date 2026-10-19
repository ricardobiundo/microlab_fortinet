# WirelessControllerHotspot20AnqpNetworkAuthTypeNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Authentication type name. | [optional] 
**auth_type** | **str** | Network authentication type.    acceptance-of-terms:Acceptance of terms and conditions.    online-enrollment:Online enrollment supported.    http-redirection:HTTP and HTTPS redirection.    dns-redirection:DNS redirection. | [optional] 
**url** | **str** | Redirect URL. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_anqp_network_auth_type_name_get200_response import WirelessControllerHotspot20AnqpNetworkAuthTypeNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20AnqpNetworkAuthTypeNameGet200Response from a JSON string
wireless_controller_hotspot20_anqp_network_auth_type_name_get200_response_instance = WirelessControllerHotspot20AnqpNetworkAuthTypeNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20AnqpNetworkAuthTypeNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_hotspot20_anqp_network_auth_type_name_get200_response_dict = wireless_controller_hotspot20_anqp_network_auth_type_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerHotspot20AnqpNetworkAuthTypeNameGet200Response from a dict
wireless_controller_hotspot20_anqp_network_auth_type_name_get200_response_from_dict = WirelessControllerHotspot20AnqpNetworkAuthTypeNameGet200Response.from_dict(wireless_controller_hotspot20_anqp_network_auth_type_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


