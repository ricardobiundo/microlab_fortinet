# SwitchControllerFlowTrackingGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sample_mode** | **str** | Configure sample mode for the flow tracking.    local:Set local mode which samples on the specific switch port.    perimeter:Set perimeter mode which samples on all switch fabric ports and fortilink port at the ingress.    device-ingress:Set device -ingress mode which samples across all switch ports at the ingress. | [optional] 
**sample_rate** | **int** | Configure sample rate for the perimeter and device-ingress sampling(0 - 99999). | [optional] 
**format** | **str** | Configure flow tracking protocol.    netflow1:Netflow version 1 sampling.    netflow5:Netflow version 5 sampling.    netflow9:Netflow version 9 sampling.    ipfix:Ipfix sampling. | [optional] 
**collectors** | [**List[SwitchControllerFlowTrackingGet200ResponseCollectorsInner]**](SwitchControllerFlowTrackingGet200ResponseCollectorsInner.md) | Configure collectors for the flow. | [optional] 
**level** | **str** | Configure flow tracking level.    vlan:Collects srcip/dstip/srcport/dstport/protocol/tos/vlan from the sample packet.    ip:Collects srcip/dstip from the sample packet.    port:Collects srcip/dstip/srcport/dstport/protocol from the sample packet.    proto:Collects srcip/dstip/protocol from the sample packet.    mac:Collects smac/dmac from the sample packet. | [optional] 
**max_export_pkt_size** | **int** | Configure flow max export packet size (512-9216, default&#x3D;512 bytes). | [optional] 
**template_export_period** | **int** | Configure template export period (1-60, default&#x3D;5 minutes). | [optional] 
**timeout_general** | **int** | Configure flow session general timeout (60-604800, default&#x3D;3600 seconds). | [optional] 
**timeout_icmp** | **int** | Configure flow session ICMP timeout (60-604800, default&#x3D;300 seconds). | [optional] 
**timeout_max** | **int** | Configure flow session max timeout (60-604800, default&#x3D;604800 seconds). | [optional] 
**timeout_tcp** | **int** | Configure flow session TCP timeout (60-604800, default&#x3D;3600 seconds). | [optional] 
**timeout_tcp_fin** | **int** | Configure flow session TCP FIN timeout (60-604800, default&#x3D;300 seconds). | [optional] 
**timeout_tcp_rst** | **int** | Configure flow session TCP RST timeout (60-604800, default&#x3D;120 seconds). | [optional] 
**timeout_udp** | **int** | Configure flow session UDP timeout (60-604800, default&#x3D;300 seconds). | [optional] 
**aggregates** | [**List[SwitchControllerFlowTrackingGet200ResponseAggregatesInner]**](SwitchControllerFlowTrackingGet200ResponseAggregatesInner.md) | Configure aggregates in which all traffic sessions matching the IP Address will be grouped into the same flow. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_flow_tracking_get200_response import SwitchControllerFlowTrackingGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerFlowTrackingGet200Response from a JSON string
switch_controller_flow_tracking_get200_response_instance = SwitchControllerFlowTrackingGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerFlowTrackingGet200Response.to_json())

# convert the object into a dict
switch_controller_flow_tracking_get200_response_dict = switch_controller_flow_tracking_get200_response_instance.to_dict()
# create an instance of SwitchControllerFlowTrackingGet200Response from a dict
switch_controller_flow_tracking_get200_response_from_dict = SwitchControllerFlowTrackingGet200Response.from_dict(switch_controller_flow_tracking_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


