# SystemSwitchInterfaceNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Interface name (name cannot be in use by any other interfaces, VLANs, or inter-VDOM links). | [optional] 
**vdom** | **str** | VDOM that the software switch belongs to. | [optional] 
**span_dest_port** | **str** | SPAN destination port name. All traffic on the SPAN source ports is echoed to the SPAN destination port. | [optional] 
**span_source_port** | [**List[SystemInterfaceNameGet200ResponseMemberInner]**](SystemInterfaceNameGet200ResponseMemberInner.md) | Physical interface name. Port spanning echoes all traffic on the SPAN source ports to the SPAN destination port. | [optional] 
**member** | [**List[SystemAcmeGet200ResponseInterfaceInner]**](SystemAcmeGet200ResponseInterfaceInner.md) | Names of the interfaces that belong to the virtual switch. | [optional] 
**type** | **str** | Type of switch based on functionality: switch for normal functionality, or hub to duplicate packets to all port members.    switch:Switch for normal switch functionality (available in NAT mode only).    hub:Hub to duplicate packets to all member ports. | [optional] 
**intra_switch_policy** | **str** | Allow any traffic between switch interfaces or require firewall policies to allow traffic between switch interfaces.    implicit:Traffic between switch members is implicitly allowed.    explicit:Traffic between switch members must match firewall policies. | [optional] 
**mac_ttl** | **int** | Duration for which MAC addresses are held in the ARP table (300 - 8640000 sec, default &#x3D; 300). | [optional] 
**span** | **str** | Enable/disable port spanning. Port spanning echoes traffic received by the software switch to the span destination port.    disable:Disable port spanning.    enable:Enable port spanning. | [optional] 
**span_direction** | **str** | The direction in which the SPAN port operates, either: rx, tx, or both.    rx:Copies only received packets from source SPAN ports to the destination SPAN port.    tx:Copies only transmitted packets from source SPAN ports to the destination SPAN port.    both:Copies both received and transmitted packets from source SPAN ports to the destination SPAN port. | [optional] 

## Example

```python
from microlab_fortinet.models.system_switch_interface_name_get200_response import SystemSwitchInterfaceNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSwitchInterfaceNameGet200Response from a JSON string
system_switch_interface_name_get200_response_instance = SystemSwitchInterfaceNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSwitchInterfaceNameGet200Response.to_json())

# convert the object into a dict
system_switch_interface_name_get200_response_dict = system_switch_interface_name_get200_response_instance.to_dict()
# create an instance of SystemSwitchInterfaceNameGet200Response from a dict
system_switch_interface_name_get200_response_from_dict = SystemSwitchInterfaceNameGet200Response.from_dict(system_switch_interface_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


