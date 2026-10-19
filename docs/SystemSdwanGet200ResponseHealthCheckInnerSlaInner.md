# SystemSdwanGet200ResponseHealthCheckInnerSlaInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | SLA ID. | [optional] 
**link_cost_factor** | **str** | Criteria on which to base link selection.    latency:Select link based on latency.    jitter:Select link based on jitter.    packet-loss:Select link based on packet loss.    custom-profile-1:Select link based on custom profile.    mos:Select link based on Mean Opinion Score (MOS).    remote:Select link based on available remote SLA status.  | [optional] 
**latency_threshold** | **int** | Latency for SLA to make decision in milliseconds. (0 - 10000000, default &#x3D; 5). | [optional] 
**jitter_threshold** | **int** | Jitter for SLA to make decision in milliseconds. (0 - 10000000, default &#x3D; 5). | [optional] 
**packetloss_threshold** | **int** | Packet loss for SLA to make decision in percentage. (0 - 100, default &#x3D; 0). | [optional] 
**mos_threshold** | **str** | Minimum mean opinion score for SLA to be marked as pass(1.0 - 5.0, default &#x3D; 3.6). | [optional] 
**custom_profile_threshold** | **int** | Custom profile threshold for SLA to be marked as pass(0 - 10000000, default &#x3D; 0). | [optional] 
**priority_in_sla** | **int** | Value to be distributed into routing table when in-sla (0 - 65535, default &#x3D; 0). | [optional] 
**priority_out_sla** | **int** | Value to be distributed into routing table when out-sla (0 - 65535, default &#x3D; 0). | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdwan_get200_response_health_check_inner_sla_inner import SystemSdwanGet200ResponseHealthCheckInnerSlaInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdwanGet200ResponseHealthCheckInnerSlaInner from a JSON string
system_sdwan_get200_response_health_check_inner_sla_inner_instance = SystemSdwanGet200ResponseHealthCheckInnerSlaInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdwanGet200ResponseHealthCheckInnerSlaInner.to_json())

# convert the object into a dict
system_sdwan_get200_response_health_check_inner_sla_inner_dict = system_sdwan_get200_response_health_check_inner_sla_inner_instance.to_dict()
# create an instance of SystemSdwanGet200ResponseHealthCheckInnerSlaInner from a dict
system_sdwan_get200_response_health_check_inner_sla_inner_from_dict = SystemSdwanGet200ResponseHealthCheckInnerSlaInner.from_dict(system_sdwan_get200_response_health_check_inner_sla_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


