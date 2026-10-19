# SystemAcmeGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**interface** | [**List[SystemAcmeGet200ResponseInterfaceInner]**](SystemAcmeGet200ResponseInterfaceInner.md) | Interface(s) on which the ACME client will listen for challenges. | [optional] 
**use_ha_direct** | **str** | Enable the use of &#39;ha-mgmt&#39; interface to connect to the ACME server when &#39;ha-direct&#39; is enabled in HA configuration    enable:Enable setting.    disable:Disable setting. | [optional] 
**source_ip** | **str** | Source IPv4 address used to connect to the ACME server. | [optional] 
**source_ip6** | **str** | Source IPv6 address used to connect to the ACME server. | [optional] 
**accounts** | [**List[SystemAcmeGet200ResponseAccountsInner]**](SystemAcmeGet200ResponseAccountsInner.md) | ACME accounts list. | [optional] 
**acc_details** | **str** | Print Account information and decrypted key. | [optional] 
**status** | **str** | Print information about the current status of the acme client. | [optional] 

## Example

```python
from microlab_fortinet.models.system_acme_get200_response import SystemAcmeGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemAcmeGet200Response from a JSON string
system_acme_get200_response_instance = SystemAcmeGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemAcmeGet200Response.to_json())

# convert the object into a dict
system_acme_get200_response_dict = system_acme_get200_response_instance.to_dict()
# create an instance of SystemAcmeGet200Response from a dict
system_acme_get200_response_from_dict = SystemAcmeGet200Response.from_dict(system_acme_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


