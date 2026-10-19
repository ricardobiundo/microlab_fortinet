# SystemInterfaceNameGet200ResponseIpv6InnerVrrp6Inner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vrid** | **int** | Virtual router identifier (1 - 255). | [optional] 
**vrgrp** | **int** | VRRP group ID (1 - 65535). | [optional] 
**vrip6** | **str** | IPv6 address of the virtual router. | [optional] 
**priority** | **int** | Priority of the virtual router (1 - 255). | [optional] 
**adv_interval** | **int** | Advertisement interval (250 - 255000 milliseconds). | [optional] 
**start_time** | **int** | Startup time (1 - 255 seconds). | [optional] 
**preempt** | **str** | Enable/disable preempt mode.    enable:Enable preempt mode.    disable:Disable preempt mode. | [optional] 
**accept_mode** | **str** | Enable/disable accept mode.    enable:Enable accept mode.    disable:Disable accept mode. | [optional] 
**vrdst6** | **str** | Monitor the route to this destination. | [optional] 
**vrdst_priority** | **int** | Priority of the virtual router when the virtual router destination becomes unreachable (0 - 254). | [optional] 
**ignore_default_route** | **str** | Enable/disable ignoring of default route when checking destination.    enable:Ignore default route when checking destination.    disable:Do not ignore default route when checking destination. | [optional] 
**status** | **str** | Enable/disable VRRP.    enable:Enable VRRP.    disable:Disable VRRP. | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_ipv6_inner_vrrp6_inner import SystemInterfaceNameGet200ResponseIpv6InnerVrrp6Inner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerVrrp6Inner from a JSON string
system_interface_name_get200_response_ipv6_inner_vrrp6_inner_instance = SystemInterfaceNameGet200ResponseIpv6InnerVrrp6Inner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseIpv6InnerVrrp6Inner.to_json())

# convert the object into a dict
system_interface_name_get200_response_ipv6_inner_vrrp6_inner_dict = system_interface_name_get200_response_ipv6_inner_vrrp6_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseIpv6InnerVrrp6Inner from a dict
system_interface_name_get200_response_ipv6_inner_vrrp6_inner_from_dict = SystemInterfaceNameGet200ResponseIpv6InnerVrrp6Inner.from_dict(system_interface_name_get200_response_ipv6_inner_vrrp6_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


