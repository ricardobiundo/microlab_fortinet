# SystemLldpNetworkPolicyNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | LLDP network policy name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**voice** | [**List[SystemLldpNetworkPolicyNameGet200ResponseVoiceInner]**](SystemLldpNetworkPolicyNameGet200ResponseVoiceInner.md) | Voice. | [optional] 
**voice_signaling** | [**List[SystemLldpNetworkPolicyNameGet200ResponseVoiceInner]**](SystemLldpNetworkPolicyNameGet200ResponseVoiceInner.md) | Voice signaling. | [optional] 
**guest** | [**List[SystemLldpNetworkPolicyNameGet200ResponseVoiceInner]**](SystemLldpNetworkPolicyNameGet200ResponseVoiceInner.md) | Guest. | [optional] 
**guest_voice_signaling** | [**List[SystemLldpNetworkPolicyNameGet200ResponseVoiceInner]**](SystemLldpNetworkPolicyNameGet200ResponseVoiceInner.md) | Guest Voice Signaling. | [optional] 
**softphone** | [**List[SystemLldpNetworkPolicyNameGet200ResponseVoiceInner]**](SystemLldpNetworkPolicyNameGet200ResponseVoiceInner.md) | Softphone. | [optional] 
**video_conferencing** | [**List[SystemLldpNetworkPolicyNameGet200ResponseVoiceInner]**](SystemLldpNetworkPolicyNameGet200ResponseVoiceInner.md) | Video Conferencing. | [optional] 
**streaming_video** | [**List[SystemLldpNetworkPolicyNameGet200ResponseVoiceInner]**](SystemLldpNetworkPolicyNameGet200ResponseVoiceInner.md) | Streaming Video. | [optional] 
**video_signaling** | [**List[SystemLldpNetworkPolicyNameGet200ResponseVoiceInner]**](SystemLldpNetworkPolicyNameGet200ResponseVoiceInner.md) | Video Signaling. | [optional] 

## Example

```python
from microlab_fortinet.models.system_lldp_network_policy_name_get200_response import SystemLldpNetworkPolicyNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemLldpNetworkPolicyNameGet200Response from a JSON string
system_lldp_network_policy_name_get200_response_instance = SystemLldpNetworkPolicyNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemLldpNetworkPolicyNameGet200Response.to_json())

# convert the object into a dict
system_lldp_network_policy_name_get200_response_dict = system_lldp_network_policy_name_get200_response_instance.to_dict()
# create an instance of SystemLldpNetworkPolicyNameGet200Response from a dict
system_lldp_network_policy_name_get200_response_from_dict = SystemLldpNetworkPolicyNameGet200Response.from_dict(system_lldp_network_policy_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


