# SystemIkeGet200ResponseDhGroup1Inner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mode** | **str** | Use software (CPU) or hardware (CPX) to perform calculations for this Diffie-Hellman group.    software:Prefer CPU to perform Diffie-Hellman calculations.    hardware:Prefer CPX to perform Diffie-Hellman calculations.    global:Use global dh-mode setting. | [optional] 
**keypair_cache** | **str** | Configure custom key pair cache size for this Diffie-Hellman group.    global:Use global Diffie-Hellman key pair cache setting.    custom:Use custom Diffie-Hellman key pair cache setting. | [optional] 
**keypair_count** | **int** | Number of key pairs to pre-generate for this Diffie-Hellman group (per-worker). | [optional] 

## Example

```python
from microlab_fortinet.models.system_ike_get200_response_dh_group1_inner import SystemIkeGet200ResponseDhGroup1Inner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIkeGet200ResponseDhGroup1Inner from a JSON string
system_ike_get200_response_dh_group1_inner_instance = SystemIkeGet200ResponseDhGroup1Inner.from_json(json)
# print the JSON string representation of the object
print(SystemIkeGet200ResponseDhGroup1Inner.to_json())

# convert the object into a dict
system_ike_get200_response_dh_group1_inner_dict = system_ike_get200_response_dh_group1_inner_instance.to_dict()
# create an instance of SystemIkeGet200ResponseDhGroup1Inner from a dict
system_ike_get200_response_dh_group1_inner_from_dict = SystemIkeGet200ResponseDhGroup1Inner.from_dict(system_ike_get200_response_dh_group1_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


