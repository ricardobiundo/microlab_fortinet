# SystemNpuGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dedicated_management_cpu** | **str** | Enable to dedicate one CPU for GUI and CLI connections when NPs are busy.    enable:Enable dedication of CPU #0 for management tasks.    disable:Disable dedication of CPU #0 for management tasks. | [optional] 
**dedicated_management_affinity** | **str** | Affinity setting for management daemons (hexadecimal value up to 256 bits in the format of xxxxxxxxxxxxxxxx). | [optional] 
**capwap_offload** | **str** | Enable/disable offloading managed FortiAP and FortiLink CAPWAP sessions.    enable:Enable CAPWAP offload.    disable:Disable CAPWAP offload. | [optional] 
**ipsec_mtu_override** | **str** | Enable/disable NP6 IPsec MTU override.    disable:Disable NP6 IPsec MTU override.    enable:Enable NP6 IPsec MTU override. | [optional] 
**ipsec_ordering** | **str** | Enable/disable IPsec ordering.    disable:Disable IPsec ordering.    enable:Enable IPsec ordering. | [optional] 
**ipsec_enc_subengine_mask** | **str** | IPsec encryption subengine mask (0x1 - 0x0f, default 0x0f). | [optional] 
**ipsec_dec_subengine_mask** | **str** | IPsec decryption subengine mask (0x1 - 0x0f, default 0x0f). | [optional] 
**priority_protocol** | [**List[SystemNpuGet200ResponsePriorityProtocolInner]**](SystemNpuGet200ResponsePriorityProtocolInner.md) | Configure NPU priority protocol. | [optional] 

## Example

```python
from microlab_fortinet.models.system_npu_get200_response import SystemNpuGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemNpuGet200Response from a JSON string
system_npu_get200_response_instance = SystemNpuGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemNpuGet200Response.to_json())

# convert the object into a dict
system_npu_get200_response_dict = system_npu_get200_response_instance.to_dict()
# create an instance of SystemNpuGet200Response from a dict
system_npu_get200_response_from_dict = SystemNpuGet200Response.from_dict(system_npu_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


