# SwitchControllerTrafficSnifferGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mode** | **str** | Configure traffic sniffer mode.    erspan-auto:Mirror traffic using a GRE tunnel.    rspan:Mirror traffic on a layer2 VLAN.    none:Disable traffic mirroring (sniffer). | [optional] 
**erspan_ip** | **str** | Configure ERSPAN collector IP address. | [optional] 
**target_mac** | [**List[SwitchControllerTrafficSnifferGet200ResponseTargetMacInner]**](SwitchControllerTrafficSnifferGet200ResponseTargetMacInner.md) | Sniffer MACs to filter. | [optional] 
**target_ip** | [**List[SwitchControllerTrafficSnifferGet200ResponseTargetIpInner]**](SwitchControllerTrafficSnifferGet200ResponseTargetIpInner.md) | Sniffer IPs to filter. | [optional] 
**target_port** | [**List[SwitchControllerTrafficSnifferGet200ResponseTargetPortInner]**](SwitchControllerTrafficSnifferGet200ResponseTargetPortInner.md) | Sniffer ports to filter. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_traffic_sniffer_get200_response import SwitchControllerTrafficSnifferGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerTrafficSnifferGet200Response from a JSON string
switch_controller_traffic_sniffer_get200_response_instance = SwitchControllerTrafficSnifferGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerTrafficSnifferGet200Response.to_json())

# convert the object into a dict
switch_controller_traffic_sniffer_get200_response_dict = switch_controller_traffic_sniffer_get200_response_instance.to_dict()
# create an instance of SwitchControllerTrafficSnifferGet200Response from a dict
switch_controller_traffic_sniffer_get200_response_from_dict = SwitchControllerTrafficSnifferGet200Response.from_dict(switch_controller_traffic_sniffer_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


