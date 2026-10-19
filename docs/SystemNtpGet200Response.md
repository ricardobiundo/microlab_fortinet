# SystemNtpGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ntpsync** | **str** | Enable/disable setting the FortiGate system time by synchronizing with an NTP Server.    enable:Enable synchronization with NTP Server.    disable:Disable synchronization with NTP Server. | [optional] 
**type** | **str** | Use the FortiGuard NTP server or any other available NTP Server.    fortiguard:Use the FortiGuard NTP server.    custom:Use any other available NTP server. | [optional] 
**syncinterval** | **int** | NTP synchronization interval (1 - 1440 min). | [optional] 
**ntpserver** | [**List[SystemNtpGet200ResponseNtpserverInner]**](SystemNtpGet200ResponseNtpserverInner.md) | Configure the FortiGate to connect to any available third-party NTP server. | [optional] 
**source_ip** | **str** | Source IP address for communication to the NTP server. | [optional] 
**source_ip6** | **str** | Source IPv6 address for communication to the NTP server. | [optional] 
**server_mode** | **str** | Enable/disable FortiGate NTP Server Mode. Your FortiGate becomes an NTP server for other devices on your network. The FortiGate relays NTP requests to its configured NTP server.    enable:Enable FortiGate NTP Server Mode.    disable:Disable FortiGate NTP Server Mode. | [optional] 
**authentication** | **str** | Enable/disable authentication.    enable:Enable authentication.    disable:Disable authentication. | [optional] 
**key_type** | **str** | Key type for authentication (MD5, SHA1, SHA256).    MD5:Use MD5 to authenticate the message.    SHA1:Use SHA1 to authenticate the message.    SHA256:Use SHA256 to authenticate the message. | [optional] 
**key** | **str** | Key for authentication. | [optional] 
**key_id** | **int** | Key ID for authentication. | [optional] 
**interface** | [**List[SystemAcmeGet200ResponseInterfaceInner]**](SystemAcmeGet200ResponseInterfaceInner.md) | FortiGate interface(s) with NTP server mode enabled. Devices on your network can contact these interfaces for NTP services. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ntp_get200_response import SystemNtpGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNtpGet200Response from a JSON string
system_ntp_get200_response_instance = SystemNtpGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemNtpGet200Response.to_json())

# convert the object into a dict
system_ntp_get200_response_dict = system_ntp_get200_response_instance.to_dict()
# create an instance of SystemNtpGet200Response from a dict
system_ntp_get200_response_from_dict = SystemNtpGet200Response.from_dict(system_ntp_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


