# SystemDns64Get200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable DNS64 (default &#x3D; disable).    enable:Enable DNS64.    disable:Disable DNS64. | [optional] 
**dns64_prefix** | **str** | DNS64 prefix must be ::/96 (default &#x3D; 64:ff9b::/96). | [optional] 
**always_synthesize_aaaa_record** | **str** | Enable/disable AAAA record synthesis (default &#x3D; enable).    enable:Enable AAAA record synthesis.    disable:Disable AAAA record synthesis. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dns64_get200_response import SystemDns64Get200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDns64Get200Response from a JSON string
system_dns64_get200_response_instance = SystemDns64Get200Response.from_json(json)
# print the JSON string representation of the object
print(SystemDns64Get200Response.to_json())

# convert the object into a dict
system_dns64_get200_response_dict = system_dns64_get200_response_instance.to_dict()
# create an instance of SystemDns64Get200Response from a dict
system_dns64_get200_response_from_dict = SystemDns64Get200Response.from_dict(system_dns64_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


