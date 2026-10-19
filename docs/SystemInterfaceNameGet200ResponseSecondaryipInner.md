# SystemInterfaceNameGet200ResponseSecondaryipInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**ip** | **str** | Secondary IP address of the interface. | [optional] 
**secip_relay_ip** | **str** | DHCP relay IP address. | [optional] 
**allowaccess** | **str** | Management access settings for the secondary IP address.    ping:PING access.    https:HTTPS access.    ssh:SSH access.    snmp:SNMP access.    http:HTTP access.    telnet:TELNET access.    fgfm:FortiManager access.    radius-acct:RADIUS accounting access.    probe-response:Probe access.    fabric:Security Fabric access.    ftm:FTM access.    speed-test:Speed test access.    scim:System for Cross-domain Identity Management (SCIM) access. | [optional] 
**gwdetect** | **str** | Enable/disable detect gateway alive for first.    enable:Enable detect gateway alive for first.    disable:Disable detect gateway alive for first. | [optional] 
**ping_serv_status** | **int** | PING server status. | [optional] 
**detectserver** | **str** | Gateway&#39;s ping server for this IP. | [optional] 
**detectprotocol** | **str** | Protocols used to detect the server.    ping:PING.    tcp-echo:TCP echo.    udp-echo:UDP echo. | [optional] 
**ha_priority** | **int** | HA election priority for the PING server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_secondaryip_inner import SystemInterfaceNameGet200ResponseSecondaryipInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseSecondaryipInner from a JSON string
system_interface_name_get200_response_secondaryip_inner_instance = SystemInterfaceNameGet200ResponseSecondaryipInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseSecondaryipInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_secondaryip_inner_dict = system_interface_name_get200_response_secondaryip_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseSecondaryipInner from a dict
system_interface_name_get200_response_secondaryip_inner_from_dict = SystemInterfaceNameGet200ResponseSecondaryipInner.from_dict(system_interface_name_get200_response_secondaryip_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


