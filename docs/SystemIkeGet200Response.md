# SystemIkeGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**embryonic_limit** | **int** | Maximum number of IPsec tunnels to negotiate simultaneously. | [optional] 
**dh_multiprocess** | **str** | Enable/disable multiprocess Diffie-Hellman daemon for IKE.    enable:Enable multiprocess Diffie-Hellman for IKE.    disable:Disable multiprocess Diffie-Hellman for IKE. | [optional] 
**dh_worker_count** | **int** | Number of Diffie-Hellman workers to start. | [optional] 
**dh_mode** | **str** | Use software (CPU) or hardware (CPX) to perform Diffie-Hellman calculations.    software:Prefer CPU to perform Diffie-Hellman calculations.    hardware:Prefer CPX to perform Diffie-Hellman calculations. | [optional] 
**dh_keypair_cache** | **str** | Enable/disable Diffie-Hellman key pair cache.    enable:Enable Diffie-Hellman key pair cache.    disable:Disable Diffie-Hellman key pair cache. | [optional] 
**dh_keypair_count** | **int** | Number of key pairs to pre-generate for each Diffie-Hellman group (per-worker). | [optional] 
**dh_keypair_throttle** | **str** | Enable/disable Diffie-Hellman key pair cache CPU throttling.    enable:Enable Diffie-Hellman key pair cache CPU throttling.    disable:Disable Diffie-Hellman key pair cache CPU throttling. | [optional] 
**dh_group_1** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 1 (MODP-768). | [optional] 
**dh_group_2** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 2 (MODP-1024). | [optional] 
**dh_group_5** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 5 (MODP-1536). | [optional] 
**dh_group_14** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 14 (MODP-2048). | [optional] 
**dh_group_15** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 15 (MODP-3072). | [optional] 
**dh_group_16** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 16 (MODP-4096). | [optional] 
**dh_group_17** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 17 (MODP-6144). | [optional] 
**dh_group_18** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 18 (MODP-8192). | [optional] 
**dh_group_19** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 19 (EC-P256). | [optional] 
**dh_group_20** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 20 (EC-P384). | [optional] 
**dh_group_21** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 21 (EC-P521). | [optional] 
**dh_group_27** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 27 (EC-P224BP). | [optional] 
**dh_group_28** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 28 (EC-P256BP). | [optional] 
**dh_group_29** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 29 (EC-P384BP). | [optional] 
**dh_group_30** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 30 (EC-P512BP). | [optional] 
**dh_group_31** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 31 (EC-X25519). | [optional] 
**dh_group_32** | [**List[SystemIkeGet200ResponseDhGroup1Inner]**](SystemIkeGet200ResponseDhGroup1Inner.md) | Diffie-Hellman group 32 (EC-X448). | [optional] 

## Example

```python
from microlab_fortinet.models.system_ike_get200_response import SystemIkeGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIkeGet200Response from a JSON string
system_ike_get200_response_instance = SystemIkeGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemIkeGet200Response.to_json())

# convert the object into a dict
system_ike_get200_response_dict = system_ike_get200_response_instance.to_dict()
# create an instance of SystemIkeGet200Response from a dict
system_ike_get200_response_from_dict = SystemIkeGet200Response.from_dict(system_ike_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


