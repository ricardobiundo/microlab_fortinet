# SystemNpuGet200ResponsePriorityProtocolInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp** | **str** | Enable/disable NPU BGP priority protocol.    enable:Enable NPU BGP priority protocol.    disable:Disable NPU BGP priority protocol. | [optional] 
**slbc** | **str** | Enable/disable NPU SLBC priority protocol.    enable:Enable NPU SLBC priority protocol.    disable:Disable NPU SLBC priority protocol. | [optional] 
**bfd** | **str** | Enable/disable NPU BFD priority protocol.    enable:Enable NPU BFD priority protocol.    disable:Disable NPU BFD priority protocol. | [optional] 

## Example

```python
from microlab_fortinet.models.system_npu_get200_response_priority_protocol_inner import SystemNpuGet200ResponsePriorityProtocolInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNpuGet200ResponsePriorityProtocolInner from a JSON string
system_npu_get200_response_priority_protocol_inner_instance = SystemNpuGet200ResponsePriorityProtocolInner.from_json(json)
# print the JSON string representation of the object
print(SystemNpuGet200ResponsePriorityProtocolInner.to_json())

# convert the object into a dict
system_npu_get200_response_priority_protocol_inner_dict = system_npu_get200_response_priority_protocol_inner_instance.to_dict()
# create an instance of SystemNpuGet200ResponsePriorityProtocolInner from a dict
system_npu_get200_response_priority_protocol_inner_from_dict = SystemNpuGet200ResponsePriorityProtocolInner.from_dict(system_npu_get200_response_priority_protocol_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


