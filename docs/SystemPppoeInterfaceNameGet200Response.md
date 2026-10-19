# SystemPppoeInterfaceNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the PPPoE interface. | [optional] 
**dial_on_demand** | **str** | Enable/disable dial on demand to dial the PPPoE interface when packets are routed to the PPPoE interface.    enable:Enable dial on demand.    disable:Disable dial on demand. | [optional] 
**ipv6** | **str** | Enable/disable IPv6 Control Protocol (IPv6CP).    enable:Enable IPv6CP.    disable:Disable IPv6CP. | [optional] 
**device** | **str** | Name for the physical interface. | [optional] 
**username** | **str** | User name. | [optional] 
**password** | **str** | Enter the password. | [optional] 
**pppoe_egress_cos** | **str** | CoS in VLAN tag for outgoing PPPoE/PPP packets.    cos0:CoS 0.    cos1:CoS 1.    cos2:CoS 2.    cos3:CoS 3.    cos4:CoS 4.    cos5:CoS 5.    cos6:CoS 6.    cos7:CoS 7. | [optional] 
**auth_type** | **str** | PPP authentication type to use.    auto:Automatically choose the authentication method.    pap:PAP authentication.    chap:CHAP authentication.    mschapv1:MS-CHAPv1 authentication.    mschapv2:MS-CHAPv2 authentication. | [optional] 
**ipunnumbered** | **str** | PPPoE unnumbered IP. | [optional] 
**pppoe_unnumbered_negotiate** | **str** | Enable/disable PPPoE unnumbered negotiation.    enable:Enable PPPoE unnumbered negotiation.    disable:Disable PPPoE unnumbered negotiation. | [optional] 
**idle_timeout** | **int** | PPPoE auto disconnect after idle timeout (0-4294967295 sec). | [optional] 
**multilink** | **str** | Enable/disable PPP multilink support.    enable:Enable PPP multilink support.    disable:Disable PPP multilink support. | [optional] 
**mrru** | **int** | PPP MRRU (296 - 65535, default &#x3D; 1500). | [optional] 
**disc_retry_timeout** | **int** | PPPoE discovery init timeout value in (0-4294967295 sec). | [optional] 
**padt_retry_timeout** | **int** | PPPoE terminate timeout value in (0-4294967295 sec). | [optional] 
**service_name** | **str** | PPPoE service name. | [optional] 
**ac_name** | **str** | PPPoE AC name. | [optional] 
**lcp_echo_interval** | **int** | Time in seconds between PPPoE Link Control Protocol (LCP) echo requests. | [optional] 
**lcp_max_echo_fails** | **int** | Maximum missed LCP echo messages before disconnect. | [optional] 

## Example

```python
from microlab_fortinet.models.system_pppoe_interface_name_get200_response import SystemPppoeInterfaceNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPppoeInterfaceNameGet200Response from a JSON string
system_pppoe_interface_name_get200_response_instance = SystemPppoeInterfaceNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemPppoeInterfaceNameGet200Response.to_json())

# convert the object into a dict
system_pppoe_interface_name_get200_response_dict = system_pppoe_interface_name_get200_response_instance.to_dict()
# create an instance of SystemPppoeInterfaceNameGet200Response from a dict
system_pppoe_interface_name_get200_response_from_dict = SystemPppoeInterfaceNameGet200Response.from_dict(system_pppoe_interface_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


