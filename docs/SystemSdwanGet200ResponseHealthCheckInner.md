# SystemSdwanGet200ResponseHealthCheckInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Status check or health check name. | [optional] 
**fortiguard** | **str** | Enable/disable use of FortiGuard predefined server.    disable:Disable use of FortiGuard predefined server.    enable:Enable use of FortiGuard predefined server. | [optional] 
**fortiguard_name** | **str** | Predefined health-check target name. | [optional] 
**probe_packets** | **str** | Enable/disable transmission of probe packets.    disable:Disable transmission of probe packets.    enable:Enable transmission of probe packets. | [optional] 
**addr_mode** | **str** | Address mode (IPv4 or IPv6).    ipv4:IPv4 mode.    ipv6:IPv6 mode. | [optional] 
**system_dns** | **str** | Enable/disable system DNS as the probe server.    disable:Disable system DNS as the probe server.    enable:Enable system DNS as the probe server. | [optional] 
**server** | **str** | IP address or FQDN name of the server. | [optional] 
**detect_mode** | **str** | The mode determining how to detect the server.    active:The probes are sent actively.    passive:The traffic measures health without probes.    prefer-passive:The probes are sent in case of no new traffic.    remote:Link health obtained from remote peers.    agent-based:Traffic health is measured from the fabric connectors. | [optional] 
**protocol** | **str** | Protocol used to determine if the FortiGate can communicate with the server.    ping:Use PING to test the link with the server.    tcp-echo:Use TCP echo to test the link with the server.    udp-echo:Use UDP echo to test the link with the server.    http:Use HTTP-GET to test the link with the server.    https:Use HTTPS-GET to test the link with the server.    twamp:Use TWAMP to test the link with the server.    dns:Use DNS query to test the link with the server.    tcp-connect:Use a full TCP connection to test the link with the server.    ftp:Use FTP to test the link with the server. | [optional] 
**port** | **int** | Port number used to communicate with the server over the selected protocol (0 - 65535, default &#x3D; 0, auto select. http, tcp-connect: 80, udp-echo, tcp-echo: 7, dns: 53, ftp: 21, twamp: 862). | [optional] 
**quality_measured_method** | **str** | Method to measure the quality of tcp-connect.    half-open:Measure the round trip between syn and ack.    half-close:Measure the round trip between fin and ack. | [optional] 
**security_mode** | **str** | Twamp controller security mode.    none:Unauthenticated mode.    authentication:Authenticated mode. | [optional] 
**user** | **str** | The user name to access probe server. | [optional] 
**password** | **str** | TWAMP controller password in authentication mode. | [optional] 
**packet_size** | **int** | Packet size of a TWAMP test session. (124/158 - 1024) | [optional] 
**ha_priority** | **int** | HA election priority (1 - 50). | [optional] 
**ftp_mode** | **str** | FTP mode.    passive:The FTP health-check initiates and establishes the data connection.    port:The FTP server initiates and establishes the data connection. | [optional] 
**ftp_file** | **str** | Full path and file name on the FTP server to download for FTP health-check to probe. | [optional] 
**http_get** | **str** | URL used to communicate with the server if the protocol if the protocol is HTTP. | [optional] 
**http_agent** | **str** | String in the http-agent field in the HTTP header. | [optional] 
**http_match** | **str** | Response string expected from the server if the protocol is HTTP. | [optional] 
**dns_request_domain** | **str** | Fully qualified domain name to resolve for the DNS probe. | [optional] 
**dns_match_ip** | **str** | Response IP expected from DNS server if the protocol is DNS. | [optional] 
**interval** | **int** | Status check interval in milliseconds, or the time between attempting to connect to the server (20 - 3600*1000 msec, default &#x3D; 500). | [optional] 
**probe_timeout** | **int** | Time to wait before a probe packet is considered lost (20 - 3600*1000 msec, default &#x3D; 500). | [optional] 
**agent_probe_timeout** | **int** | Time to wait before a probe packet is considered lost when detect-mode is agent (5000 - 3600*1000 msec, default &#x3D; 60000). | [optional] 
**remote_probe_timeout** | **int** | Time to wait before a probe packet is considered lost when detect-mode is remote (20 - 3600*1000 msec, default &#x3D; 5000). | [optional] 
**failtime** | **int** | Number of failures before server is considered lost (1 - 3600, default &#x3D; 5). | [optional] 
**recoverytime** | **int** | Number of successful responses received before server is considered recovered (1 - 3600, default &#x3D; 5). | [optional] 
**probe_count** | **int** | Number of most recent probes that should be used to calculate latency and jitter (5 - 30, default &#x3D; 30). | [optional] 
**diffservcode** | **str** | Differentiated services code point (DSCP) in the IP header of the probe packet. | [optional] 
**update_cascade_interface** | **str** | Enable/disable update cascade interface.    enable:Enable update cascade interface.    disable:Disable update cascade interface. | [optional] 
**update_static_route** | **str** | Enable/disable updating the static route.    enable:Enable updating the static route.    disable:Disable updating the static route. | [optional] 
**update_bgp_route** | **str** | Enable/disable updating the BGP route.    enable:Enable updating the BGP route.    disable:Disable updating the BGP route. | [optional] 
**embed_measured_health** | **str** | Enable/disable embedding measured health information.    enable:Enable embed measured health.    disable:Disable embed measured health. | [optional] 
**sla_id_redistribute** | **int** | Select the ID from the SLA sub-table. The selected SLA&#39;s priority value will be distributed into the routing table (0 - 32, default &#x3D; 0). | [optional] 
**sla_fail_log_period** | **int** | Time interval in seconds that SLA fail log messages will be generated (0 - 3600, default &#x3D; 0). | [optional] 
**sla_pass_log_period** | **int** | Time interval in seconds that SLA pass log messages will be generated (0 - 3600, default &#x3D; 0). | [optional] 
**threshold_warning_packetloss** | **int** | Warning threshold for packet loss (percentage, default &#x3D; 0). | [optional] 
**threshold_alert_packetloss** | **int** | Alert threshold for packet loss (percentage, default &#x3D; 0). | [optional] 
**threshold_warning_latency** | **int** | Warning threshold for latency (ms, default &#x3D; 0). | [optional] 
**threshold_alert_latency** | **int** | Alert threshold for latency (ms, default &#x3D; 0). | [optional] 
**threshold_warning_jitter** | **int** | Warning threshold for jitter (ms, default &#x3D; 0). | [optional] 
**threshold_alert_jitter** | **int** | Alert threshold for jitter (ms, default &#x3D; 0). | [optional] 
**vrf** | **int** | Virtual Routing Forwarding ID. | [optional] 
**source** | **str** | Source IP address used in the health-check packet to the server. | [optional] 
**source6** | **str** | Source IPv6 address used in the health-check packet to server. | [optional] 
**members** | [**List[SystemSdwanGet200ResponseHealthCheckInnerMembersInner]**](SystemSdwanGet200ResponseHealthCheckInnerMembersInner.md) | Member sequence number list. | [optional] 
**mos_codec** | **str** | Codec to use for MOS calculation (default &#x3D; g711).    g711:Calculate MOS based on the G.711 codec.    g722:Calculate MOS based on the G.722 codec.    g729:Calculate MOS based on the G.729 codec. | [optional] 
**class_id** | **int** | Traffic class ID. | [optional] 
**packet_loss_weight** | **int** | Coefficient of packet-loss in the formula of custom-profile-1. | [optional] 
**latency_weight** | **int** | Coefficient of latency in the formula of custom-profile-1. | [optional] 
**jitter_weight** | **int** | Coefficient of jitter in the formula of custom-profile-1. | [optional] 
**bandwidth_weight** | **int** | Coefficient of reciprocal of available bidirectional bandwidth in the formula of custom-profile-1. | [optional] 
**sla** | [**List[SystemSdwanGet200ResponseHealthCheckInnerSlaInner]**](SystemSdwanGet200ResponseHealthCheckInnerSlaInner.md) | Service level agreement (SLA). | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdwan_get200_response_health_check_inner import SystemSdwanGet200ResponseHealthCheckInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdwanGet200ResponseHealthCheckInner from a JSON string
system_sdwan_get200_response_health_check_inner_instance = SystemSdwanGet200ResponseHealthCheckInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdwanGet200ResponseHealthCheckInner.to_json())

# convert the object into a dict
system_sdwan_get200_response_health_check_inner_dict = system_sdwan_get200_response_health_check_inner_instance.to_dict()
# create an instance of SystemSdwanGet200ResponseHealthCheckInner from a dict
system_sdwan_get200_response_health_check_inner_from_dict = SystemSdwanGet200ResponseHealthCheckInner.from_dict(system_sdwan_get200_response_health_check_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


