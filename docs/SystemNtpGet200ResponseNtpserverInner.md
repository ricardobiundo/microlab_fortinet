# SystemNtpGet200ResponseNtpserverInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | NTP server ID. | [optional] 
**server** | **str** | IP address or hostname of the NTP Server. | [optional] 
**ntpv3** | **str** | Enable to use NTPv3 instead of NTPv4.    enable:Enable NTPv3.    disable:Disable NTPv3 (use NTPv4). | [optional] 
**authentication** | **str** | Enable/disable authentication.    enable:Enable authentication.    disable:Disable authentication. | [optional] 
**key_type** | **str** | Select NTP authentication type.    MD5:Enable MD5(NTPv3) authentication.    SHA1:Enable SHA1(NTPv4) authentication.    SHA256:Enable SHA256(NTPv4) authentication. | [optional] 
**key** | **str** | Key for MD5(NTPv3)/SHA1(NTPv4)/SHA256(NTPv4) authentication. | [optional] 
**key_id** | **int** | Key ID for authentication. | [optional] 
**ip_type** | **str** | Choose to connect to IPv4 or/and IPv6 NTP server.    IPv6:Enable look up for IPv6 NTP server.    IPv4:Enable look up for IPv4 NTP server.    Both:Enable look up for both IPv4 and IPv6 NTP server. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ntp_get200_response_ntpserver_inner import SystemNtpGet200ResponseNtpserverInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNtpGet200ResponseNtpserverInner from a JSON string
system_ntp_get200_response_ntpserver_inner_instance = SystemNtpGet200ResponseNtpserverInner.from_json(json)
# print the JSON string representation of the object
print(SystemNtpGet200ResponseNtpserverInner.to_json())

# convert the object into a dict
system_ntp_get200_response_ntpserver_inner_dict = system_ntp_get200_response_ntpserver_inner_instance.to_dict()
# create an instance of SystemNtpGet200ResponseNtpserverInner from a dict
system_ntp_get200_response_ntpserver_inner_from_dict = SystemNtpGet200ResponseNtpserverInner.from_dict(system_ntp_get200_response_ntpserver_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


