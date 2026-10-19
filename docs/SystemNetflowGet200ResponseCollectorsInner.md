# SystemNetflowGet200ResponseCollectorsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**collector_ip** | **str** | Collector IP. | [optional] 
**collector_port** | **int** | NetFlow collector port number. | [optional] 
**source_ip** | **str** | Source IP address for communication with the NetFlow agent. | [optional] 
**source_ip_interface** | **str** | Name of the interface used to determine the source IP for exporting packets. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_netflow_get200_response_collectors_inner import SystemNetflowGet200ResponseCollectorsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNetflowGet200ResponseCollectorsInner from a JSON string
system_netflow_get200_response_collectors_inner_instance = SystemNetflowGet200ResponseCollectorsInner.from_json(json)
# print the JSON string representation of the object
print(SystemNetflowGet200ResponseCollectorsInner.to_json())

# convert the object into a dict
system_netflow_get200_response_collectors_inner_dict = system_netflow_get200_response_collectors_inner_instance.to_dict()
# create an instance of SystemNetflowGet200ResponseCollectorsInner from a dict
system_netflow_get200_response_collectors_inner_from_dict = SystemNetflowGet200ResponseCollectorsInner.from_dict(system_netflow_get200_response_collectors_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


