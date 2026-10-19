# WirelessControllerWagProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Tunnel profile name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**tunnel_type** | **str** | Tunnel type.    l2tpv3:L2TPV3 Ethernet Pseudowire.    gre:GRE Ethernet tunnel. | [optional] 
**wag_ip** | **str** | IP Address of the wireless access gateway. | [optional] 
**wag_port** | **int** | UDP port of the wireless access gateway. | [optional] 
**ping_interval** | **int** | Interval between two tunnel monitoring echo packets (1 - 65535 sec, default &#x3D; 1). | [optional] 
**ping_number** | **int** | Number of the tunnel monitoring echo packets (1 - 65535, default &#x3D; 5). | [optional] 
**return_packet_timeout** | **int** | Window of time for the return packets from the tunnel&#39;s remote end (1 - 65535 sec, default &#x3D; 160). | [optional] 
**dhcp_ip_addr** | **str** | IP address of the monitoring DHCP request packet sent through the tunnel. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_wag_profile_name_get200_response import WirelessControllerWagProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerWagProfileNameGet200Response from a JSON string
wireless_controller_wag_profile_name_get200_response_instance = WirelessControllerWagProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerWagProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_wag_profile_name_get200_response_dict = wireless_controller_wag_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerWagProfileNameGet200Response from a dict
wireless_controller_wag_profile_name_get200_response_from_dict = WirelessControllerWagProfileNameGet200Response.from_dict(wireless_controller_wag_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


