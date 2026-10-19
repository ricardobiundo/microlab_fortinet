# SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**switch_id** | **str** | Switch ID. | [optional] 
**status** | **str** | Enable/disable this DHCP configuration.    disable:Do not use this DHCP server configuration.    enable:Use this DHCP server configuration. | [optional] 
**lease_time** | **int** | Lease time in seconds, 0 means unlimited. | [optional] 
**dns_service** | **str** | Options for assigning DNS servers to DHCP clients.    local:IP address of the interface the DHCP server is added to becomes the client&#39;s DNS server IP address.    default:Clients are assigned the FortiGate&#39;s configured DNS servers.    specify:Specify up to 3 DNS servers in the DHCP server configuration. | [optional] 
**dns_server1** | **str** | DNS server 1. | [optional] 
**dns_server2** | **str** | DNS server 2. | [optional] 
**dns_server3** | **str** | DNS server 3. | [optional] 
**ntp_service** | **str** | Options for assigning Network Time Protocol (NTP) servers to DHCP clients.    local:IP address of the interface the DHCP server is added to becomes the client&#39;s NTP server IP address.    default:Clients are assigned the FortiGate&#39;s configured NTP servers.    specify:Specify up to 3 NTP servers in the DHCP server configuration. | [optional] 
**ntp_server1** | **str** | NTP server 1. | [optional] 
**ntp_server2** | **str** | NTP server 2. | [optional] 
**ntp_server3** | **str** | NTP server 3. | [optional] 
**default_gateway** | **str** | Default gateway IP address assigned by the DHCP server. | [optional] 
**netmask** | **str** | Netmask assigned by the DHCP server. | [optional] 
**interface** | **str** | DHCP server can assign IP configurations to clients connected to this interface. | [optional] 
**ip_range** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInnerIpRangeInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInnerIpRangeInner.md) | DHCP IP range configuration. | [optional] 
**options** | [**List[SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInnerOptionsInner]**](SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInnerOptionsInner.md) | DHCP options. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_managed_switch_switch_id_get200_response_system_dhcp_server_inner import SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInner from a JSON string
switch_controller_managed_switch_switch_id_get200_response_system_dhcp_server_inner_instance = SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInner.to_json())

# convert the object into a dict
switch_controller_managed_switch_switch_id_get200_response_system_dhcp_server_inner_dict = switch_controller_managed_switch_switch_id_get200_response_system_dhcp_server_inner_instance.to_dict()
# create an instance of SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInner from a dict
switch_controller_managed_switch_switch_id_get200_response_system_dhcp_server_inner_from_dict = SwitchControllerManagedSwitchSwitchIdGet200ResponseSystemDhcpServerInner.from_dict(switch_controller_managed_switch_switch_id_get200_response_system_dhcp_server_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


