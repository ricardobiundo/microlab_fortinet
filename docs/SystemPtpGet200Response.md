# SystemPtpGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable setting the FortiGate system time by synchronizing with an PTP Server.    enable:Enable synchronization with PTP Server.    disable:Disable synchronization with PTP Server. | [optional] 
**mode** | **str** | Multicast transmission or hybrid transmission.    multicast:Send PTP packets with multicast.    hybrid:Send PTP packets with unicast and multicast. | [optional] 
**delay_mechanism** | **str** | End to end delay detection or peer to peer delay detection.    E2E:End to end delay detection.    P2P:Peer to peer delay detection. | [optional] 
**request_interval** | **int** | The delay request value is the logarithmic mean interval in seconds between the delay request messages sent by the slave to the master. | [optional] 
**interface** | **str** | PTP client will reply through this interface. | [optional] 
**server_mode** | **str** | Enable/disable FortiGate PTP server mode. Your FortiGate becomes an PTP server for other devices on your network.    enable:Enable FortiGate PTP server mode.    disable:Disable FortiGate PTP server mode. | [optional] 
**server_interface** | [**List[SystemPtpGet200ResponseServerInterfaceInner]**](SystemPtpGet200ResponseServerInterfaceInner.md) | FortiGate interface(s) with PTP server mode enabled. Devices on your network can contact these interfaces for PTP services. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ptp_get200_response import SystemPtpGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPtpGet200Response from a JSON string
system_ptp_get200_response_instance = SystemPtpGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemPtpGet200Response.to_json())

# convert the object into a dict
system_ptp_get200_response_dict = system_ptp_get200_response_instance.to_dict()
# create an instance of SystemPtpGet200Response from a dict
system_ptp_get200_response_from_dict = SystemPtpGet200Response.from_dict(system_ptp_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


