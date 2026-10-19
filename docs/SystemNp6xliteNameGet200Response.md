# SystemNp6xliteNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Device Name. | [optional] 
**fastpath** | **str** | Enable/disable NP6XLITE offloading (also called fast path).    disable:Disable NP6XLITE offloading (fast path).    enable:Enable NP6XLITE offloading (fast path). | [optional] 
**per_session_accounting** | **str** | Enable/disable per-session accounting.    disable:Disable per-session accounting.    traffic-log-only:Per-session accounting only for sessions with traffic logging enabled in firewall policy.    enable:Per-session accounting for all sessions. | [optional] 
**session_timeout_interval** | **int** | Set session timeout interval (0 - 1000 sec, default 40 sec). | [optional] 
**ipsec_inner_fragment** | **str** | Enable/disable NP6XLite IPsec fragmentation type: inner.    disable:NP6XLite ipsec fragmentation type: outer.    enable:Enable NP6XLite ipsec fragmentation type: inner. | [optional] 
**ipsec_throughput_msg_frequency** | **str** | Set NP6XLite IPsec throughput message frequency (0 &#x3D; disable).    disable:Disable NP6Xlite throughput update message.    32kb:Set NP6Xlite throughput update message frequency to 32KB.    64kb:Set NP6Xlite throughput update message frequency to 64KB.    128kb:Set NP6Xlite throughput update message frequency to 128KB.    256kb:Set NP6Xlite throughput update message frequency to 256KB.    512kb:Set NP6Xlite throughput update message frequency to 512KB.    1mb:Set NP6Xlite throughput update message frequency to 1MB.    2mb:Set NP6Xlite throughput update message frequency to 2MB.    4mb:Set NP6Xlite throughput update message frequency to 4MB.    8mb:Set NP6Xlite throughput update message frequency to 8MB.    16mb:Set NP6Xlite throughput update message frequency to 16MB.    32mb:Set NP6Xlite throughput update message frequency to 32MB.    64mb:Set NP6Xlite throughput update message frequency to 64MB.    128mb:Set NP6Xlite throughput update message frequency to 128MB.    256mb:Set NP6Xlite throughput update message frequency to 256MB.    512mb:Set NP6Xlite throughput update message frequency to 512MB.    1gb:Set NP6Xlite throughput update message frequency to 1GB. | [optional] 
**ipsec_sts_timeout** | **str** | Set NP6XLite IPsec STS message timeout.    1:Set NP6Xlite STS message timeout to 1 sec (recommended for IPSec throughput GUI).    2:Set NP6Xlite STS message timeout to 2 sec.    3:Set NP6Xlite STS message timeout to 3 sec.    4:Set NP6Xlite STS message timeout to 4 sec.    5:Set NP6Xlite STS message timeout to 5 sec (default).    6:Set NP6Xlite STS message timeout to 6 sec.    7:Set NP6Xlite STS message timeout to 7 sec.    8:Set NP6Xlite STS message timeout to 8 sec.    9:Set NP6Xlite STS message timeout to 9 sec.    10:Set NP6Xlite STS message timeout to 10 sec. | [optional] 
**hpe** | [**List[SystemNp6xliteNameGet200ResponseHpeInner]**](SystemNp6xliteNameGet200ResponseHpeInner.md) | HPE configuration. | [optional] 
**fp_anomaly** | [**List[SystemNp6xliteNameGet200ResponseFpAnomalyInner]**](SystemNp6xliteNameGet200ResponseFpAnomalyInner.md) | NP6XLITE IPv4 anomaly protection. The trap-to-host forwards anomaly sessions to the CPU. | [optional] 

## Example

```python
from microlab_fortinet.models.system_np6xlite_name_get200_response import SystemNp6xliteNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNp6xliteNameGet200Response from a JSON string
system_np6xlite_name_get200_response_instance = SystemNp6xliteNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemNp6xliteNameGet200Response.to_json())

# convert the object into a dict
system_np6xlite_name_get200_response_dict = system_np6xlite_name_get200_response_instance.to_dict()
# create an instance of SystemNp6xliteNameGet200Response from a dict
system_np6xlite_name_get200_response_from_dict = SystemNp6xliteNameGet200Response.from_dict(system_np6xlite_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


