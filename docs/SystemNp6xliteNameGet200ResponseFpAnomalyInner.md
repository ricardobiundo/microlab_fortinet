# SystemNp6xliteNameGet200ResponseFpAnomalyInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tcp_syn_fin** | **str** | TCP SYN flood SYN/FIN flag set anomalies.    allow:Allow TCP packets with syn_fin flag set to pass.    drop:Drop TCP packets with syn_fin flag set.    trap-to-host:Forward TCP packets with syn_fin flag set to FortiOS. | [optional] 
**tcp_fin_noack** | **str** | TCP SYN flood with FIN flag set without ACK setting anomalies.    allow:Allow TCP packets with FIN flag set without ack setting to pass.    drop:Drop TCP packets with FIN flag set without ack setting.    trap-to-host:Forward TCP packets with FIN flag set without ack setting to FortiOS. | [optional] 
**tcp_fin_only** | **str** | TCP SYN flood with only FIN flag set anomalies.    allow:Allow TCP packets with FIN flag set only to pass.    drop:Drop TCP packets with FIN flag set only.    trap-to-host:Forward TCP packets with FIN flag set only to FortiOS. | [optional] 
**tcp_no_flag** | **str** | TCP SYN flood with no flag set anomalies.    allow:Allow TCP packets without flag set to pass.    drop:Drop TCP packets without flag set.    trap-to-host:Forward TCP packets without flag set to FortiOS. | [optional] 
**tcp_syn_data** | **str** | TCP SYN flood packets with data anomalies.    allow:Allow TCP syn packets with data to pass.    drop:Drop TCP syn packets with data.    trap-to-host:Forward TCP syn packets with data to FortiOS. | [optional] 
**tcp_winnuke** | **str** | TCP WinNuke anomalies.    allow:Allow TCP packets winnuke attack to pass.    drop:Drop TCP packets winnuke attack.    trap-to-host:Forward TCP packets winnuke attack to FortiOS. | [optional] 
**tcp_land** | **str** | TCP land anomalies.    allow:Allow TCP land attack to pass.    drop:Drop TCP land attack.    trap-to-host:Forward TCP land attack to FortiOS. | [optional] 
**udp_land** | **str** | UDP land anomalies.    allow:Allow UDP land attack to pass.    drop:Drop UDP land attack.    trap-to-host:Forward UDP land attack to FortiOS. | [optional] 
**icmp_land** | **str** | ICMP land anomalies.    allow:Allow ICMP land attack to pass.    drop:Drop ICMP land attack.    trap-to-host:Forward ICMP land attack to FortiOS. | [optional] 
**icmp_frag** | **str** | Layer 3 fragmented packets that could be part of layer 4 ICMP anomalies.    allow:Allow L3 fragment packet with L4 protocol as ICMP attack to pass.    drop:Drop L3 fragment packet with L4 protocol as ICMP attack.    trap-to-host:Forward L3 fragment packet with L4 protocol as ICMP attack to FortiOS. | [optional] 
**ipv4_land** | **str** | Land anomalies.    allow:Allow IPv4 land attack to pass.    drop:Drop IPv4 land attack.    trap-to-host:Forward IPv4 land attack to FortiOS. | [optional] 
**ipv4_proto_err** | **str** | Invalid layer 4 protocol anomalies.    allow:Allow IPv4 invalid L4 protocol to pass.    drop:Drop IPv4 invalid L4 protocol.    trap-to-host:Forward IPv4 invalid L4 protocol to FortiOS. | [optional] 
**ipv4_unknopt** | **str** | Unknown option anomalies.    allow:Allow IPv4 with unknown options to pass.    drop:Drop IPv4 with unknown options.    trap-to-host:Forward IPv4 with unknown options to FortiOS. | [optional] 
**ipv4_optrr** | **str** | Record route option anomalies.    allow:Allow IPv4 with record route option to pass.    drop:Drop IPv4 with record route option.    trap-to-host:Forward IPv4 with record route option to FortiOS. | [optional] 
**ipv4_optssrr** | **str** | Strict source record route option anomalies.    allow:Allow IPv4 with strict source record route option to pass.    drop:Drop IPv4 with strict source record route option.    trap-to-host:Forward IPv4 with strict source record route option to FortiOS. | [optional] 
**ipv4_optlsrr** | **str** | Loose source record route option anomalies.    allow:Allow IPv4 with loose source record route option to pass.    drop:Drop IPv4 with loose source record route option.    trap-to-host:Forward IPv4 with loose source record route option to FortiOS. | [optional] 
**ipv4_optstream** | **str** | Stream option anomalies.    allow:Allow IPv4 with stream option to pass.    drop:Drop IPv4 with stream option.    trap-to-host:Forward IPv4 with stream option to FortiOS. | [optional] 
**ipv4_optsecurity** | **str** | Security option anomalies.    allow:Allow IPv4 with security option to pass.    drop:Drop IPv4 with security option.    trap-to-host:Forward IPv4 with security option to FortiOS. | [optional] 
**ipv4_opttimestamp** | **str** | Timestamp option anomalies.    allow:Allow IPv4 with timestamp option to pass.    drop:Drop IPv4 with timestamp option.    trap-to-host:Forward IPv4 with timestamp option to FortiOS. | [optional] 
**ipv4_csum_err** | **str** | Invalid IPv4 IP checksum anomalies.    drop:Drop IPv4 invalid IP checksum.    trap-to-host:Forward IPv4 invalid IP checksum to main CPU for processing. | [optional] 
**tcp_csum_err** | **str** | Invalid IPv4 TCP checksum anomalies.    drop:Drop IPv4 invalid TCP checksum.    trap-to-host:Forward IPv4 invalid TCP checksum to main CPU for processing. | [optional] 
**udp_csum_err** | **str** | Invalid IPv4 UDP checksum anomalies.    drop:Drop IPv4 invalid UDP checksum.    trap-to-host:Forward IPv4 invalid UDP checksum to main CPU for processing. | [optional] 
**icmp_csum_err** | **str** | Invalid IPv4 ICMP checksum anomalies.    drop:Drop IPv4 invalid ICMP checksum.    trap-to-host:Forward IPv4 invalid ICMP checksum to main CPU for processing. | [optional] 
**ipv6_land** | **str** | Land anomalies.    allow:Allow IPv6 land attack to pass.    drop:Drop IPv6 land attack.    trap-to-host:Forward IPv6 land attack to FortiOS. | [optional] 
**ipv6_proto_err** | **str** | Layer 4 invalid protocol anomalies.    allow:Allow IPv6 L4 invalid protocol to pass.    drop:Drop IPv6 L4 invalid protocol.    trap-to-host:Forward IPv6 L4 invalid protocol to FortiOS. | [optional] 
**ipv6_unknopt** | **str** | Unknown option anomalies.    allow:Allow IPv6 with unknown options to pass.    drop:Drop IPv6 with unknown options.    trap-to-host:Forward IPv6 with unknown options to FortiOS. | [optional] 
**ipv6_saddr_err** | **str** | Source address as multicast anomalies.    allow:Allow IPv6 with source address as multicast to pass.    drop:Drop IPv6 with source address as multicast.    trap-to-host:Forward IPv6 with source address as multicast to FortiOS. | [optional] 
**ipv6_daddr_err** | **str** | Destination address as unspecified or loopback address anomalies.    allow:Allow IPv6 with destination address as unspecified or loopback address to pass.    drop:Drop IPv6 with destination address as unspecified or loopback address.    trap-to-host:Forward IPv6 with destination address as unspecified or loopback address to FortiOS. | [optional] 
**ipv6_optralert** | **str** | Router alert option anomalies.    allow:Allow IPv6 with router alert option to pass.    drop:Drop IPv6 with router alert option.    trap-to-host:Forward IPv6 with router alert option to FortiOS. | [optional] 
**ipv6_optjumbo** | **str** | Jumbo options anomalies.    allow:Allow IPv6 with jumbo option to pass.    drop:Drop IPv6 with jumbo option.    trap-to-host:Forward IPv6 with jumbo option to FortiOS. | [optional] 
**ipv6_opttunnel** | **str** | Tunnel encapsulation limit option anomalies.    allow:Allow IPv6 with tunnel encapsulation limit to pass.    drop:Drop IPv6 with tunnel encapsulation limit.    trap-to-host:Forward IPv6 with tunnel encapsulation limit to FortiOS. | [optional] 
**ipv6_opthomeaddr** | **str** | Home address option anomalies.    allow:Allow IPv6 with home address option to pass.    drop:Drop IPv6 with home address option.    trap-to-host:Forward IPv6 with home address option to FortiOS. | [optional] 
**ipv6_optnsap** | **str** | Network service access point address option anomalies.    allow:Allow IPv6 with network service access point address option to pass.    drop:Drop IPv6 with network service access point address option.    trap-to-host:Forward IPv6 with network service access point address option to FortiOS. | [optional] 
**ipv6_optendpid** | **str** | End point identification anomalies.    allow:Allow IPv6 with end point identification option to pass.    drop:Drop IPv6 with end point identification option.    trap-to-host:Forward IPv6 with end point identification option to FortiOS. | [optional] 
**ipv6_optinvld** | **str** | Invalid option anomalies.Invalid option anomalies.    allow:Allow IPv6 with invalid option to pass.    drop:Drop IPv6 with invalid option.    trap-to-host:Forward IPv6 with invalid option to FortiOS. | [optional] 

## Example

```python
from microlab_fortinet.models.system_np6xlite_name_get200_response_fp_anomaly_inner import SystemNp6xliteNameGet200ResponseFpAnomalyInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNp6xliteNameGet200ResponseFpAnomalyInner from a JSON string
system_np6xlite_name_get200_response_fp_anomaly_inner_instance = SystemNp6xliteNameGet200ResponseFpAnomalyInner.from_json(json)
# print the JSON string representation of the object
print(SystemNp6xliteNameGet200ResponseFpAnomalyInner.to_json())

# convert the object into a dict
system_np6xlite_name_get200_response_fp_anomaly_inner_dict = system_np6xlite_name_get200_response_fp_anomaly_inner_instance.to_dict()
# create an instance of SystemNp6xliteNameGet200ResponseFpAnomalyInner from a dict
system_np6xlite_name_get200_response_fp_anomaly_inner_from_dict = SystemNp6xliteNameGet200ResponseFpAnomalyInner.from_dict(system_np6xlite_name_get200_response_fp_anomaly_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


