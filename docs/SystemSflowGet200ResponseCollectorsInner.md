# SystemSflowGet200ResponseCollectorsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**collector_ip** | **str** | IP addresses of the sFlow collectors that sFlow agents added to interfaces in this VDOM send sFlow datagrams to. | [optional] 
**collector_port** | **int** | UDP port number used for sending sFlow datagrams (configure only if required by your sFlow collector or your network configuration) (0 - 65535, default &#x3D; 6343). | [optional] 
**source_ip** | **str** | Source IP address for sFlow agent. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sflow_get200_response_collectors_inner import SystemSflowGet200ResponseCollectorsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSflowGet200ResponseCollectorsInner from a JSON string
system_sflow_get200_response_collectors_inner_instance = SystemSflowGet200ResponseCollectorsInner.from_json(json)
# print the JSON string representation of the object
print(SystemSflowGet200ResponseCollectorsInner.to_json())

# convert the object into a dict
system_sflow_get200_response_collectors_inner_dict = system_sflow_get200_response_collectors_inner_instance.to_dict()
# create an instance of SystemSflowGet200ResponseCollectorsInner from a dict
system_sflow_get200_response_collectors_inner_from_dict = SystemSflowGet200ResponseCollectorsInner.from_dict(system_sflow_get200_response_collectors_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


