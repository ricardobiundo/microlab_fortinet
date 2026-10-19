# WirelessControllerHotspot20H2qpConnCapabilityNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Connection capability name. | [optional] 
**icmp_port** | **str** | Set ICMP port service status.    closed:The port is not open for communication.    open:The port is open for communication.    unknown:The port may or may not be open for communication. | [optional] 
**ftp_port** | **str** | Set FTP port service status.    closed:The port is not open for communication.    open:The port is open for communication.    unknown:The port may or may not be open for communication. | [optional] 
**ssh_port** | **str** | Set SSH port service status.    closed:The port is not open for communication.    open:The port is open for communication.    unknown:The port may or may not be open for communication. | [optional] 
**http_port** | **str** | Set HTTP port service status.    closed:The port is not open for communication.    open:The port is open for communication.    unknown:The port may or may not be open for communication. | [optional] 
**tls_port** | **str** | Set TLS VPN (HTTPS) port service status.    closed:The port is not open for communication.    open:The port is open for communication.    unknown:The port may or may not be open for communication. | [optional] 
**pptp_vpn_port** | **str** | Set Point to Point Tunneling Protocol (PPTP) VPN port service status.    closed:The port is not open for communication.    open:The port is open for communication.    unknown:The port may or may not be open for communication. | [optional] 
**voip_tcp_port** | **str** | Set VoIP TCP port service status.    closed:The port is not open for communication.    open:The port is open for communication.    unknown:The port may or may not be open for communication. | [optional] 
**voip_udp_port** | **str** | Set VoIP UDP port service status.    closed:The port is not open for communication.    open:The port is open for communication.    unknown:The port may or may not be open for communication. | [optional] 
**ikev2_port** | **str** | Set IKEv2 port service for IPsec VPN status.    closed:The port is not open for communication.    open:The port is open for communication.    unknown:The port may or may not be open for communication. | [optional] 
**ikev2_xx_port** | **str** | Set UDP port 4500 (which may be used by IKEv2 for IPsec VPN) service status.    closed:The port is not open for communication.    open:The port is open for communication.    unknown:The port may or may not be open for communication. | [optional] 
**esp_port** | **str** | Set ESP port service (used by IPsec VPNs) status.    closed:The port is not open for communication.    open:The port is open for communication.    unknown:The port may or may not be open for communication. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_hotspot20_h2qp_conn_capability_name_get200_response import WirelessControllerHotspot20H2qpConnCapabilityNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerHotspot20H2qpConnCapabilityNameGet200Response from a JSON string
wireless_controller_hotspot20_h2qp_conn_capability_name_get200_response_instance = WirelessControllerHotspot20H2qpConnCapabilityNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerHotspot20H2qpConnCapabilityNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_hotspot20_h2qp_conn_capability_name_get200_response_dict = wireless_controller_hotspot20_h2qp_conn_capability_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerHotspot20H2qpConnCapabilityNameGet200Response from a dict
wireless_controller_hotspot20_h2qp_conn_capability_name_get200_response_from_dict = WirelessControllerHotspot20H2qpConnCapabilityNameGet200Response.from_dict(wireless_controller_hotspot20_h2qp_conn_capability_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


