# SystemLinkMonitorNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Link monitor name. | [optional] 
**addr_mode** | **str** | Address mode (IPv4 or IPv6).    ipv4:IPv4 mode.    ipv6:IPv6 mode. | [optional] 
**srcintf** | **str** | Interface that receives the traffic to be monitored. | [optional] 
**server_config** | **str** | Mode of server configuration.    default:All servers share the same attributes.    individual:Some attributes can be specified for individual servers. | [optional] 
**server_type** | **str** | Server type (static or dynamic).    static:Static servers.    dynamic:Dynamic servers. | [optional] 
**server** | [**List[SystemLinkMonitorNameGet200ResponseServerInner]**](SystemLinkMonitorNameGet200ResponseServerInner.md) | IP address of the server(s) to be monitored. | [optional] 
**protocol** | **str** | Protocols used to monitor the server.    ping:PING link monitor.    tcp-echo:TCP echo link monitor.    udp-echo:UDP echo link monitor.    http:HTTP-GET link monitor.    https:HTTPS-GET link monitor.    twamp:TWAMP link monitor. | [optional] 
**port** | **int** | Port number of the traffic to be used to monitor the server. | [optional] 
**gateway_ip** | **str** | Gateway IP address used to probe the server. | [optional] 
**gateway_ip6** | **str** | Gateway IPv6 address used to probe the server. | [optional] 
**route** | [**List[SystemLinkMonitorNameGet200ResponseRouteInner]**](SystemLinkMonitorNameGet200ResponseRouteInner.md) | Subnet to monitor. | [optional] 
**source_ip** | **str** | Source IP address used in packet to the server. | [optional] 
**source_ip6** | **str** | Source IPv6 address used in packet to the server. | [optional] 
**http_get** | **str** | If you are monitoring an HTML server you can send an HTTP-GET request with a custom string. Use this option to define the string. | [optional] 
**http_agent** | **str** | String in the http-agent field in the HTTP header. | [optional] 
**http_match** | **str** | String that you expect to see in the HTTP-GET requests of the traffic to be monitored. | [optional] 
**interval** | **int** | Detection interval in milliseconds (20 - 3600 * 1000 msec, default &#x3D; 500). | [optional] 
**probe_timeout** | **int** | Time to wait before a probe packet is considered lost (20 - 5000 msec, default &#x3D; 500). | [optional] 
**failtime** | **int** | Number of retry attempts before the server is considered down (1 - 3600, default &#x3D; 5). | [optional] 
**recoverytime** | **int** | Number of successful responses received before server is considered recovered (1 - 3600, default &#x3D; 5). | [optional] 
**probe_count** | **int** | Number of most recent probes that should be used to calculate latency and jitter (5 - 30, default &#x3D; 30). | [optional] 
**security_mode** | **str** | Twamp controller security mode.    none:Unauthenticated mode.    authentication:Authenticated mode. | [optional] 
**password** | **str** | TWAMP controller password in authentication mode. | [optional] 
**packet_size** | **int** | Packet size of a TWAMP test session (124/158 - 1024). | [optional] 
**ha_priority** | **int** | HA election priority (1 - 50). | [optional] 
**fail_weight** | **int** | Threshold weight to trigger link failure alert. | [optional] 
**update_cascade_interface** | **str** | Enable/disable update cascade interface.    enable:Enable update cascade interface.    disable:Disable update cascade interface. | [optional] 
**update_static_route** | **str** | Enable/disable updating the static route.    enable:Enable updating the static route.    disable:Disable updating the static route. | [optional] 
**update_policy_route** | **str** | Enable/disable updating the policy route.    enable:Enable updating the policy route.    disable:Disable updating the policy route. | [optional] 
**status** | **str** | Enable/disable this link monitor.    enable:Enable this link monitor.    disable:Disable this link monitor. | [optional] 
**diffservcode** | **str** | Differentiated services code point (DSCP) in the IP header of the probe packet. | [optional] 
**class_id** | **int** | Traffic class ID. | [optional] 
**service_detection** | **str** | Only use monitor to read quality values. If enabled, static routes and cascade interfaces will not be updated.    enable:Only use monitor for service-detection.    disable:Monitor will update routes/interfaces on link failure. | [optional] 
**server_list** | [**List[SystemLinkMonitorNameGet200ResponseServerListInner]**](SystemLinkMonitorNameGet200ResponseServerListInner.md) | Servers for link-monitor to monitor. | [optional] 

## Example

```python
from microlab_fortinet.models.system_link_monitor_name_get200_response import SystemLinkMonitorNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemLinkMonitorNameGet200Response from a JSON string
system_link_monitor_name_get200_response_instance = SystemLinkMonitorNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemLinkMonitorNameGet200Response.to_json())

# convert the object into a dict
system_link_monitor_name_get200_response_dict = system_link_monitor_name_get200_response_instance.to_dict()
# create an instance of SystemLinkMonitorNameGet200Response from a dict
system_link_monitor_name_get200_response_from_dict = SystemLinkMonitorNameGet200Response.from_dict(system_link_monitor_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


