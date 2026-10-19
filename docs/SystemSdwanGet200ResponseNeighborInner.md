# SystemSdwanGet200ResponseNeighborInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip** | **str** | IP/IPv6 address of neighbor or neighbor-group name. | [optional] 
**member** | [**List[SystemSdwanGet200ResponseHealthCheckInnerMembersInner]**](SystemSdwanGet200ResponseHealthCheckInnerMembersInner.md) | Member sequence number list. | [optional] 
**service_id** | **int** | SD-WAN service ID to work with the neighbor. | [optional] 
**minimum_sla_meet_members** | **int** | Minimum number of members which meet SLA when the neighbor is preferred. | [optional] 
**mode** | **str** | What metric to select the neighbor.    sla:Select neighbor based on SLA link quality.    speedtest:Select neighbor based on the speedtest status. | [optional] 
**role** | **str** | Role of neighbor.    standalone:Standalone neighbor.    primary:Primary neighbor.    secondary:Secondary neighbor. | [optional] 
**route_metric** | **str** | Route-metric of neighbor.    preferable:Select neighbor based on its hc to match bgp preferable/unpreferable route_map.    priority:Select neighbor based on its members&#39; priority-in-sla/priority-out-sla value. | [optional] 
**health_check** | **str** | SD-WAN health-check name. | [optional] 
**sla_id** | **int** | SLA ID. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdwan_get200_response_neighbor_inner import SystemSdwanGet200ResponseNeighborInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdwanGet200ResponseNeighborInner from a JSON string
system_sdwan_get200_response_neighbor_inner_instance = SystemSdwanGet200ResponseNeighborInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdwanGet200ResponseNeighborInner.to_json())

# convert the object into a dict
system_sdwan_get200_response_neighbor_inner_dict = system_sdwan_get200_response_neighbor_inner_instance.to_dict()
# create an instance of SystemSdwanGet200ResponseNeighborInner from a dict
system_sdwan_get200_response_neighbor_inner_from_dict = SystemSdwanGet200ResponseNeighborInner.from_dict(system_sdwan_get200_response_neighbor_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


