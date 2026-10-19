# SystemCentralManagementGet200ResponseServerListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**server_type** | **str** | FortiGuard service type.    update:AV, IPS, and AV-query update server.    rating:Web filter and anti-spam rating server.    vpatch-query:Virtual patch query server.    iot-collect:IoT device collection server. | [optional] 
**addr_type** | **str** | Indicate whether the FortiGate communicates with the override server using an IPv4 address, an IPv6 address or a FQDN.    ipv4:IPv4 address.    ipv6:IPv6 address.    fqdn:FQDN. | [optional] 
**server_address** | **str** | IPv4 address of override server. | [optional] 
**server_address6** | **str** | IPv6 address of override server. | [optional] 
**fqdn** | **str** | FQDN address of override server. | [optional] 

## Example

```python
from microlab_fortinet.models.system_central_management_get200_response_server_list_inner import SystemCentralManagementGet200ResponseServerListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemCentralManagementGet200ResponseServerListInner from a JSON string
system_central_management_get200_response_server_list_inner_instance = SystemCentralManagementGet200ResponseServerListInner.from_json(json)
# print the JSON string representation of the object
print(SystemCentralManagementGet200ResponseServerListInner.to_json())

# convert the object into a dict
system_central_management_get200_response_server_list_inner_dict = system_central_management_get200_response_server_list_inner_instance.to_dict()
# create an instance of SystemCentralManagementGet200ResponseServerListInner from a dict
system_central_management_get200_response_server_list_inner_from_dict = SystemCentralManagementGet200ResponseServerListInner.from_dict(system_central_management_get200_response_server_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


