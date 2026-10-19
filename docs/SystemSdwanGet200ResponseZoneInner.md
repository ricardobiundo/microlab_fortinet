# SystemSdwanGet200ResponseZoneInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Zone name. | [optional] 
**advpn_select** | **str** | Enable/disable selection of ADVPN based on SDWAN information.    enable:Enable selection of ADVPN based on SDWAN information.    disable:Disable selection of ADVPN based on SDWAN information. | [optional] 
**advpn_health_check** | **str** | Health check for ADVPN local overlay link quality. | [optional] 
**service_sla_tie_break** | **str** | Method of selecting member if more than one meets the SLA.    cfg-order:Members that meet the SLA are selected in the order they are configured.    fib-best-match:Members that meet the SLA are selected that match the longest prefix in the routing table.    priority:Members that meet the SLA are reselected again based link-cost-factor.    input-device:Members that meet the SLA are selected by matching the input device. | [optional] 
**minimum_sla_meet_members** | **int** | Minimum number of members which meet SLA when the neighbor is preferred. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdwan_get200_response_zone_inner import SystemSdwanGet200ResponseZoneInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdwanGet200ResponseZoneInner from a JSON string
system_sdwan_get200_response_zone_inner_instance = SystemSdwanGet200ResponseZoneInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdwanGet200ResponseZoneInner.to_json())

# convert the object into a dict
system_sdwan_get200_response_zone_inner_dict = system_sdwan_get200_response_zone_inner_instance.to_dict()
# create an instance of SystemSdwanGet200ResponseZoneInner from a dict
system_sdwan_get200_response_zone_inner_from_dict = SystemSdwanGet200ResponseZoneInner.from_dict(system_sdwan_get200_response_zone_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


