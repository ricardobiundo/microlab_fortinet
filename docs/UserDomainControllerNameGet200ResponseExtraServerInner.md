# UserDomainControllerNameGet200ResponseExtraServerInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Server ID. | [optional] 
**ip_address** | **str** | Domain controller IP address. | [optional] 
**port** | **int** | Port to be used for communication with the domain controller (default &#x3D; 445). | [optional] 
**source_ip_address** | **str** | FortiGate IPv4 address to be used for communication with the domain controller. | [optional] 
**source_port** | **int** | Source port to be used for communication with the domain controller. | [optional] 

## Example

```python
from microlab_fortinet.models.user_domain_controller_name_get200_response_extra_server_inner import UserDomainControllerNameGet200ResponseExtraServerInner

# TODO update the JSON string below
json = "{}"
# create an instance of UserDomainControllerNameGet200ResponseExtraServerInner from a JSON string
user_domain_controller_name_get200_response_extra_server_inner_instance = UserDomainControllerNameGet200ResponseExtraServerInner.from_json(json)
# print the JSON string representation of the object
print(UserDomainControllerNameGet200ResponseExtraServerInner.to_json())

# convert the object into a dict
user_domain_controller_name_get200_response_extra_server_inner_dict = user_domain_controller_name_get200_response_extra_server_inner_instance.to_dict()
# create an instance of UserDomainControllerNameGet200ResponseExtraServerInner from a dict
user_domain_controller_name_get200_response_extra_server_inner_from_dict = UserDomainControllerNameGet200ResponseExtraServerInner.from_dict(user_domain_controller_name_get200_response_extra_server_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


