# SystemFipsCcGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable ciphers for FIPS mode of operation.    enable:Enable FIPS-CC mode.    disable:Disable FIPS-CC mode. | [optional] 
**self_test_period** | **int** | Self test period. | [optional] 
**key_generation_self_test** | **str** | Enable/disable self tests after key generation.    enable:Enable self tests after key generation.    disable:Disable self tests after key generation. | [optional] 

## Example

```python
from microlab_fortinet.models.system_fips_cc_get200_response import SystemFipsCcGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemFipsCcGet200Response from a JSON string
system_fips_cc_get200_response_instance = SystemFipsCcGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemFipsCcGet200Response.to_json())

# convert the object into a dict
system_fips_cc_get200_response_dict = system_fips_cc_get200_response_instance.to_dict()
# create an instance of SystemFipsCcGet200Response from a dict
system_fips_cc_get200_response_from_dict = SystemFipsCcGet200Response.from_dict(system_fips_cc_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


