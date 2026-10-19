# SystemApiUserNameGet200ResponseTrusthostInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**type** | **str** | Trusthost type.    ipv4-trusthost:IPv4 trusthost.    ipv6-trusthost:IPv6 trusthost. | [optional] 
**ipv4_trusthost** | **str** | IPv4 trusted host address. | [optional] 
**ipv6_trusthost** | **str** | IPv6 trusted host address. | [optional] 

## Example

```python
from microlab_fortinet.models.system_api_user_name_get200_response_trusthost_inner import SystemApiUserNameGet200ResponseTrusthostInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemApiUserNameGet200ResponseTrusthostInner from a JSON string
system_api_user_name_get200_response_trusthost_inner_instance = SystemApiUserNameGet200ResponseTrusthostInner.from_json(json)
# print the JSON string representation of the object
print(SystemApiUserNameGet200ResponseTrusthostInner.to_json())

# convert the object into a dict
system_api_user_name_get200_response_trusthost_inner_dict = system_api_user_name_get200_response_trusthost_inner_instance.to_dict()
# create an instance of SystemApiUserNameGet200ResponseTrusthostInner from a dict
system_api_user_name_get200_response_trusthost_inner_from_dict = SystemApiUserNameGet200ResponseTrusthostInner.from_dict(system_api_user_name_get200_response_trusthost_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


