# SystemInterfaceNameGet200ResponseVrrpInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vrid** | **int** | Virtual router identifier (1 - 255). | [optional] 
**version** | **str** | VRRP version.    2:VRRP version 2.    3:VRRP version 3. | [optional] 
**vrgrp** | **int** | VRRP group ID (1 - 65535). | [optional] 
**vrip** | **str** | IP address of the virtual router. | [optional] 
**priority** | **int** | Priority of the virtual router (1 - 255). | [optional] 
**adv_interval** | **int** | Advertisement interval (250 - 255000 milliseconds). | [optional] 
**start_time** | **int** | Startup time (1 - 255 seconds). | [optional] 
**preempt** | **str** | Enable/disable preempt mode.    enable:Enable preempt mode.    disable:Disable preempt mode. | [optional] 
**accept_mode** | **str** | Enable/disable accept mode.    enable:Enable accept mode.    disable:Disable accept mode. | [optional] 
**vrdst** | **str** | Monitor the route to this destination. | [optional] 
**vrdst_priority** | **int** | Priority of the virtual router when the virtual router destination becomes unreachable (0 - 254). | [optional] 
**ignore_default_route** | **str** | Enable/disable ignoring of default route when checking destination.    enable:Ignore default route when checking destination.    disable:Do not ignore default route when checking destination. | [optional] 
**status** | **str** | Enable/disable this VRRP configuration.    enable:Enable this VRRP configuration.    disable:Disable this VRRP configuration. | [optional] 
**proxy_arp** | [**List[SystemInterfaceNameGet200ResponseVrrpInnerProxyArpInner]**](SystemInterfaceNameGet200ResponseVrrpInnerProxyArpInner.md) | VRRP Proxy ARP configuration. | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_vrrp_inner import SystemInterfaceNameGet200ResponseVrrpInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseVrrpInner from a JSON string
system_interface_name_get200_response_vrrp_inner_instance = SystemInterfaceNameGet200ResponseVrrpInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseVrrpInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_vrrp_inner_dict = system_interface_name_get200_response_vrrp_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseVrrpInner from a dict
system_interface_name_get200_response_vrrp_inner_from_dict = SystemInterfaceNameGet200ResponseVrrpInner.from_dict(system_interface_name_get200_response_vrrp_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


