# SystemLinkMonitorNameGet200ResponseServerListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Server ID. | [optional] 
**dst** | **str** | IP address of the server to be monitored. | [optional] 
**protocol** | **str** | Protocols used to monitor the server.    ping:PING link monitor.    tcp-echo:TCP echo link monitor.    udp-echo:UDP echo link monitor.    http:HTTP-GET link monitor.    https:HTTPS-GET link monitor.    twamp:TWAMP link monitor. | [optional] 
**port** | **int** | Port number of the traffic to be used to monitor the server. | [optional] 
**weight** | **int** | Weight of the monitor to this dst (0 - 255). | [optional] 

## Example

```python
from microlab_fortinet.models.system_link_monitor_name_get200_response_server_list_inner import SystemLinkMonitorNameGet200ResponseServerListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemLinkMonitorNameGet200ResponseServerListInner from a JSON string
system_link_monitor_name_get200_response_server_list_inner_instance = SystemLinkMonitorNameGet200ResponseServerListInner.from_json(json)
# print the JSON string representation of the object
print(SystemLinkMonitorNameGet200ResponseServerListInner.to_json())

# convert the object into a dict
system_link_monitor_name_get200_response_server_list_inner_dict = system_link_monitor_name_get200_response_server_list_inner_instance.to_dict()
# create an instance of SystemLinkMonitorNameGet200ResponseServerListInner from a dict
system_link_monitor_name_get200_response_server_list_inner_from_dict = SystemLinkMonitorNameGet200ResponseServerListInner.from_dict(system_link_monitor_name_get200_response_server_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


