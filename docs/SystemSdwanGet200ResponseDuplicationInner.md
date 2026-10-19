# SystemSdwanGet200ResponseDuplicationInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Duplication rule ID (1 - 255). | [optional] 
**service_id** | [**List[SystemSdwanGet200ResponseDuplicationInnerServiceIdInner]**](SystemSdwanGet200ResponseDuplicationInnerServiceIdInner.md) | SD-WAN service rule ID list. | [optional] 
**srcaddr** | [**List[SystemSdwanGet200ResponseServiceInnerDstInner]**](SystemSdwanGet200ResponseServiceInnerDstInner.md) | Source address or address group names. | [optional] 
**dstaddr** | [**List[SystemSdwanGet200ResponseServiceInnerDstInner]**](SystemSdwanGet200ResponseServiceInnerDstInner.md) | Destination address or address group names. | [optional] 
**srcaddr6** | [**List[SystemSdwanGet200ResponseServiceInnerDst6Inner]**](SystemSdwanGet200ResponseServiceInnerDst6Inner.md) | Source address6 or address6 group names. | [optional] 
**dstaddr6** | [**List[SystemSdwanGet200ResponseServiceInnerDst6Inner]**](SystemSdwanGet200ResponseServiceInnerDst6Inner.md) | Destination address6 or address6 group names. | [optional] 
**srcintf** | [**List[SystemSdwanGet200ResponseDuplicationInnerSrcintfInner]**](SystemSdwanGet200ResponseDuplicationInnerSrcintfInner.md) | Incoming (ingress) interfaces or zones. | [optional] 
**dstintf** | [**List[SystemSdwanGet200ResponseDuplicationInnerSrcintfInner]**](SystemSdwanGet200ResponseDuplicationInnerSrcintfInner.md) | Outgoing (egress) interfaces or zones. | [optional] 
**service** | [**List[SystemSdwanGet200ResponseDuplicationInnerServiceInner]**](SystemSdwanGet200ResponseDuplicationInnerServiceInner.md) | Service and service group name. | [optional] 
**packet_duplication** | **str** | Configure packet duplication method.    disable:Disable packet duplication.    force:Duplicate packets across all interface members of the SD-WAN zone.    on-demand:Duplicate packets across all interface members of the SD-WAN zone based on the link quality. | [optional] 
**sla_match_service** | **str** | Enable/disable packet duplication matching health-check SLAs in service rule.    enable:Enable packet duplication matching health-check SLAs in service rule (matching all SLAs of current defined service).    disable:Disable packet duplication matching health-check SLAs in service rule (matching all SLAs of all defined health-check). | [optional] 
**packet_de_duplication** | **str** | Enable/disable discarding of packets that have been duplicated.    enable:Enable discarding of packets that have been duplicated.    disable:Disable discarding of packets that have been duplicated. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdwan_get200_response_duplication_inner import SystemSdwanGet200ResponseDuplicationInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdwanGet200ResponseDuplicationInner from a JSON string
system_sdwan_get200_response_duplication_inner_instance = SystemSdwanGet200ResponseDuplicationInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdwanGet200ResponseDuplicationInner.to_json())

# convert the object into a dict
system_sdwan_get200_response_duplication_inner_dict = system_sdwan_get200_response_duplication_inner_instance.to_dict()
# create an instance of SystemSdwanGet200ResponseDuplicationInner from a dict
system_sdwan_get200_response_duplication_inner_from_dict = SystemSdwanGet200ResponseDuplicationInner.from_dict(system_sdwan_get200_response_duplication_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


