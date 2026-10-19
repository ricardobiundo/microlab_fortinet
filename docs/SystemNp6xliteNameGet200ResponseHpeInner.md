# SystemNp6xliteNameGet200ResponseHpeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tcpsyn_max** | **int** | Maximum TCP SYN only packet rate (1K - 1G pps, default &#x3D; 600K pps). | [optional] 
**tcpsyn_ack_max** | **int** | Maximum TCP carries SYN and ACK flags packet rate (1K - 1G pps, default &#x3D; 600K pps). | [optional] 
**tcpfin_rst_max** | **int** | Maximum TCP carries FIN or RST flags packet rate (1K - 1G pps, default &#x3D; 600K pps). | [optional] 
**tcp_others_max** | **int** | Maximum TCP packet rate for TCP packets that match none of the 3 types above (1K - 1G pps, default &#x3D; 600K pps). | [optional] 
**udp_max** | **int** | Maximum UDP packet rate (1K - 1G pps, default &#x3D; 600K pps). | [optional] 
**icmp_max** | **int** | Maximum ICMP packet rate (1K - 1G pps, default &#x3D; 200K pps). | [optional] 
**sctp_max** | **int** | Maximum SCTP packet rate (1K - 1G pps, default &#x3D; 200K pps). | [optional] 
**esp_max** | **int** | Maximum ESP packet rate (1K - 1G pps, default &#x3D; 200K pps). | [optional] 
**ip_frag_max** | **int** | Maximum fragmented IP packet rate (1K - 1G pps, default &#x3D; 200K pps). | [optional] 
**ip_others_max** | **int** | Maximum IP packet rate for other packets (packet types that cannot be set with other options) (1K - 1G pps, default &#x3D; 200K pps). | [optional] 
**arp_max** | **int** | Maximum ARP packet rate (1K - 1G pps, default &#x3D; 200K pps). | [optional] 
**l2_others_max** | **int** | Maximum L2 packet rate for L2 packets that are not ARP packets (1K - 1G pps, default &#x3D; 200K pps). | [optional] 
**pri_type_max** | **int** | Maximum overflow rate of priority type traffic (1K - 1G pps, default &#x3D; 200K pps). Includes L2: HA, 802.3ad LACP, heartbeats. L3: OSPF. L4_TCP: BGP. L4_UDP: IKE, SLBC, BFD. | [optional] 
**enable_shaper** | **str** | Enable/Disable NPU host protection engine (HPE) shaper.    disable:Disable NPU HPE shaping based on packet type.    enable:Enable NPU HPE shaping based on packet type. | [optional] 

## Example

```python
from microlab_fortinet.models.system_np6xlite_name_get200_response_hpe_inner import SystemNp6xliteNameGet200ResponseHpeInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNp6xliteNameGet200ResponseHpeInner from a JSON string
system_np6xlite_name_get200_response_hpe_inner_instance = SystemNp6xliteNameGet200ResponseHpeInner.from_json(json)
# print the JSON string representation of the object
print(SystemNp6xliteNameGet200ResponseHpeInner.to_json())

# convert the object into a dict
system_np6xlite_name_get200_response_hpe_inner_dict = system_np6xlite_name_get200_response_hpe_inner_instance.to_dict()
# create an instance of SystemNp6xliteNameGet200ResponseHpeInner from a dict
system_np6xlite_name_get200_response_hpe_inner_from_dict = SystemNp6xliteNameGet200ResponseHpeInner.from_dict(system_np6xlite_name_get200_response_hpe_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


