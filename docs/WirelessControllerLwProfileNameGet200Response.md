# WirelessControllerLwProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | LoRaWAN profile name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**lw_protocol** | **str** | Configure LoRaWAN protocol (default &#x3D; basics-station)    basics-station:Configure LoRaWAN protocol to Basics Station.    packet-forwarder:Configure LoRaWAN protocol to UDP Packet Forwarder. | [optional] 
**cups_server** | **str** | CUPS (Configuration and Update Server) domain name or IP address of LoRaWAN device. | [optional] 
**cups_server_port** | **int** | CUPS Port value of LoRaWAN device. | [optional] 
**cups_api_key** | **str** | CUPS API key of LoRaWAN device. | [optional] 
**tc_server** | **str** | TC (Traffic Controller) domain name or IP address of LoRaWAN device. | [optional] 
**tc_server_port** | **int** | TC Port value of LoRaWAN device. | [optional] 
**tc_api_key** | **str** | TC API key of LoRaWAN device. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_lw_profile_name_get200_response import WirelessControllerLwProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerLwProfileNameGet200Response from a JSON string
wireless_controller_lw_profile_name_get200_response_instance = WirelessControllerLwProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerLwProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_lw_profile_name_get200_response_dict = wireless_controller_lw_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerLwProfileNameGet200Response from a dict
wireless_controller_lw_profile_name_get200_response_from_dict = WirelessControllerLwProfileNameGet200Response.from_dict(wireless_controller_lw_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


