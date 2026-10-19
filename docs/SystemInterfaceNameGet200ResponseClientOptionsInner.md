# SystemInterfaceNameGet200ResponseClientOptionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**code** | **int** | DHCP client option code. | [optional] 
**type** | **str** | DHCP client option type.    hex:DHCP option in hex.    string:DHCP option in string.    ip:DHCP option in IP.    fqdn:DHCP option in domain search option format. | [optional] 
**value** | **str** | DHCP client option value. | [optional] 
**ip** | **str** | DHCP option IPs. | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_client_options_inner import SystemInterfaceNameGet200ResponseClientOptionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseClientOptionsInner from a JSON string
system_interface_name_get200_response_client_options_inner_instance = SystemInterfaceNameGet200ResponseClientOptionsInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseClientOptionsInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_client_options_inner_dict = system_interface_name_get200_response_client_options_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseClientOptionsInner from a dict
system_interface_name_get200_response_client_options_inner_from_dict = SystemInterfaceNameGet200ResponseClientOptionsInner.from_dict(system_interface_name_get200_response_client_options_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


