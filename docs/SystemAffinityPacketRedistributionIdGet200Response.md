# SystemAffinityPacketRedistributionIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID of the packet redistribution setting. | [optional] 
**interface** | **str** | Physical interface name on which to perform packet redistribution. | [optional] 
**rxqid** | **int** | ID of the receive queue (when the interface has multiple queues) on which to perform packet redistribution (255 &#x3D; all queues). | [optional] 
**round_robin** | **str** | Enable/disable round-robin redistribution to multiple CPUs.    enable:Enable round-robin redistribution.    disable:Disable round-robin redistribution. | [optional] 
**affinity_cpumask** | **str** | Hexadecimal cpumask, empty value means all CPUs. | [optional] 

## Example

```python
from microlab_fortinet.models.system_affinity_packet_redistribution_id_get200_response import SystemAffinityPacketRedistributionIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAffinityPacketRedistributionIdGet200Response from a JSON string
system_affinity_packet_redistribution_id_get200_response_instance = SystemAffinityPacketRedistributionIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAffinityPacketRedistributionIdGet200Response.to_json())

# convert the object into a dict
system_affinity_packet_redistribution_id_get200_response_dict = system_affinity_packet_redistribution_id_get200_response_instance.to_dict()
# create an instance of SystemAffinityPacketRedistributionIdGet200Response from a dict
system_affinity_packet_redistribution_id_get200_response_from_dict = SystemAffinityPacketRedistributionIdGet200Response.from_dict(system_affinity_packet_redistribution_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


