# WirelessControllerHotspot20AnqpIpAddressTypeNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | IP type name. | [optional] 
**ipv6_address_type** | **str** | IPv6 address type.    not-available:Address type not available.    available:Address type available.    not-known:Availability of the address type not known. | [optional] 
**ipv4_address_type** | **str** | IPv4 address type.    not-available:Address type not available.    public:Public IPv4 address available.    port-restricted:Port-restricted IPv4 address available.    single-NATed-private:Single NATed private IPv4 address available.    double-NATed-private:Double NATed private IPv4 address available.    port-restricted-and-single-NATed:Port-restricted IPv4 address and single NATed IPv4 address available.    port-restricted-and-double-NATed:Port-restricted IPv4 address and double NATed IPv4 address available.    not-known:Availability of the address type is not known. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_anqp_ip_address_type_name_get200_response import WirelessControllerHotspot20AnqpIpAddressTypeNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20AnqpIpAddressTypeNameGet200Response from a JSON string
wireless_controller_hotspot20_anqp_ip_address_type_name_get200_response_instance = WirelessControllerHotspot20AnqpIpAddressTypeNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20AnqpIpAddressTypeNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_hotspot20_anqp_ip_address_type_name_get200_response_dict = wireless_controller_hotspot20_anqp_ip_address_type_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerHotspot20AnqpIpAddressTypeNameGet200Response from a dict
wireless_controller_hotspot20_anqp_ip_address_type_name_get200_response_from_dict = WirelessControllerHotspot20AnqpIpAddressTypeNameGet200Response.from_dict(wireless_controller_hotspot20_anqp_ip_address_type_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


