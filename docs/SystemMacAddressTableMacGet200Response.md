# SystemMacAddressTableMacGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mac** | **str** | MAC address. | [optional] 
**interface** | **str** | Interface name. | [optional] 
**reply_substitute** | **str** | New MAC for reply traffic. | [optional] 

## Example

```python
from microlab_fortinet.models.system_mac_address_table_mac_get200_response import SystemMacAddressTableMacGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemMacAddressTableMacGet200Response from a JSON string
system_mac_address_table_mac_get200_response_instance = SystemMacAddressTableMacGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemMacAddressTableMacGet200Response.to_json())

# convert the object into a dict
system_mac_address_table_mac_get200_response_dict = system_mac_address_table_mac_get200_response_instance.to_dict()
# create an instance of SystemMacAddressTableMacGet200Response from a dict
system_mac_address_table_mac_get200_response_from_dict = SystemMacAddressTableMacGet200Response.from_dict(system_mac_address_table_mac_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


