# SystemFortisandboxGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable FortiSandbox.    enable:Enable FortiSandbox.    disable:Disable FortiSandbox. | [optional] 
**forticloud** | **str** | Enable/disable FortiSandbox Cloud.    enable:Enable FortiSandbox Cloud.    disable:Disable FortiSandbox Cloud. | [optional] 
**inline_scan** | **str** | Enable/disable FortiSandbox inline scan.    enable:Enable FortiSandbox inline scan.    disable:Disable FortiSandbox inline scan. | [optional] 
**server** | **str** | Server IP address or FQDN of the remote FortiSandbox. | [optional] 
**source_ip** | **str** | Source IP address for communications to FortiSandbox. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 
**enc_algorithm** | **str** | Configure the level of SSL protection for secure communication with FortiSandbox.    default:SSL communication with high and medium encryption algorithms.    high:SSL communication with high encryption algorithms.    low:SSL communication with low encryption algorithms. | [optional] 
**ssl_min_proto_version** | **str** | Minimum supported protocol version for SSL/TLS connections (default is to follow system global setting).    default:Follow system global setting.    SSLv3:SSLv3.    TLSv1:TLSv1.    TLSv1-1:TLSv1.1.    TLSv1-2:TLSv1.2.    TLSv1-3:TLSv1.3. | [optional] 
**email** | **str** | Notifier email address. | [optional] 
**ca** | **str** | The CA that signs remote FortiSandbox certificate, empty for no check. | [optional] 
**cn** | **str** | The CN of remote server certificate, case sensitive, empty for no check. | [optional] 
**certificate_verification** | **str** | Enable/disable identity verification of FortiSandbox by use of certificate.    enable:Enable identity verification of FortiSandbox by use of certificate.    disable:Disable identity verification of FortiSandbox by use of certificate. | [optional] 

## Example

```python
from microlab_fortinet.models.system_fortisandbox_get200_response import SystemFortisandboxGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFortisandboxGet200Response from a JSON string
system_fortisandbox_get200_response_instance = SystemFortisandboxGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemFortisandboxGet200Response.to_json())

# convert the object into a dict
system_fortisandbox_get200_response_dict = system_fortisandbox_get200_response_instance.to_dict()
# create an instance of SystemFortisandboxGet200Response from a dict
system_fortisandbox_get200_response_from_dict = SystemFortisandboxGet200Response.from_dict(system_fortisandbox_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


