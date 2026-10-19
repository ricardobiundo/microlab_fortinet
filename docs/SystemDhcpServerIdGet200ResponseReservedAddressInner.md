# SystemDhcpServerIdGet200ResponseReservedAddressInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**type** | **str** | DHCP reserved-address type.    mac:Match with MAC address.    option82:Match with DHCP option 82. | [optional] 
**ip** | **str** | IP address to be reserved for the MAC address. | [optional] 
**mac** | **str** | MAC address of the client that will get the reserved IP address. | [optional] 
**action** | **str** | Options for the DHCP server to configure the client with the reserved MAC address.    assign:Configure the client with this MAC address like any other client.    block:Block the DHCP server from assigning IP settings to the client with this MAC address.    reserved:Assign the reserved IP address to the client with this MAC address. | [optional] 
**circuit_id_type** | **str** | DHCP option type.    hex:DHCP option in hex.    string:DHCP option in string. | [optional] 
**circuit_id** | **str** | Option 82 circuit-ID of the client that will get the reserved IP address. | [optional] 
**remote_id_type** | **str** | DHCP option type.    hex:DHCP option in hex.    string:DHCP option in string. | [optional] 
**remote_id** | **str** | Option 82 remote-ID of the client that will get the reserved IP address. | [optional] 
**description** | **str** | Description. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dhcp_server_id_get200_response_reserved_address_inner import SystemDhcpServerIdGet200ResponseReservedAddressInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDhcpServerIdGet200ResponseReservedAddressInner from a JSON string
system_dhcp_server_id_get200_response_reserved_address_inner_instance = SystemDhcpServerIdGet200ResponseReservedAddressInner.from_json(json)
# print the JSON string representation of the object
print(SystemDhcpServerIdGet200ResponseReservedAddressInner.to_json())

# convert the object into a dict
system_dhcp_server_id_get200_response_reserved_address_inner_dict = system_dhcp_server_id_get200_response_reserved_address_inner_instance.to_dict()
# create an instance of SystemDhcpServerIdGet200ResponseReservedAddressInner from a dict
system_dhcp_server_id_get200_response_reserved_address_inner_from_dict = SystemDhcpServerIdGet200ResponseReservedAddressInner.from_dict(system_dhcp_server_id_get200_response_reserved_address_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


