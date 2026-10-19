# SystemInterfaceNameGet200ResponseDhcpSnoopingServerListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | DHCP server name. | [optional] 
**server_ip** | **str** | IP address for DHCP server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_dhcp_snooping_server_list_inner import SystemInterfaceNameGet200ResponseDhcpSnoopingServerListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseDhcpSnoopingServerListInner from a JSON string
system_interface_name_get200_response_dhcp_snooping_server_list_inner_instance = SystemInterfaceNameGet200ResponseDhcpSnoopingServerListInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseDhcpSnoopingServerListInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_dhcp_snooping_server_list_inner_dict = system_interface_name_get200_response_dhcp_snooping_server_list_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseDhcpSnoopingServerListInner from a dict
system_interface_name_get200_response_dhcp_snooping_server_list_inner_from_dict = SystemInterfaceNameGet200ResponseDhcpSnoopingServerListInner.from_dict(system_interface_name_get200_response_dhcp_snooping_server_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


