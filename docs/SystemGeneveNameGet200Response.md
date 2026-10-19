# SystemGeneveNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | GENEVE device or interface name. Must be an unique interface name. | [optional] 
**interface** | **str** | Outgoing interface for GENEVE encapsulated traffic. | [optional] 
**vni** | **int** | GENEVE network ID. | [optional] 
**type** | **str** | GENEVE type.    ethernet:Internal packet includes Ethernet header.    ppp:Internal packet does not include Ethernet header. | [optional] 
**ip_version** | **str** | IP version to use for the GENEVE interface and so for communication over the GENEVE. IPv4 or IPv6 unicast.    ipv4-unicast:Use IPv4 unicast addressing over the GENEVE.    ipv6-unicast:Use IPv6 unicast addressing over the GENEVE. | [optional] 
**remote_ip** | **str** | IPv4 address of the GENEVE interface on the device at the remote end of the GENEVE. | [optional] 
**remote_ip6** | **str** | IPv6 IP address of the GENEVE interface on the device at the remote end of the GENEVE. | [optional] 
**dstport** | **int** | GENEVE destination port (1 - 65535, default &#x3D; 6081). | [optional] 

## Example

```python
from microlab_fortinet.models.system_geneve_name_get200_response import SystemGeneveNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemGeneveNameGet200Response from a JSON string
system_geneve_name_get200_response_instance = SystemGeneveNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemGeneveNameGet200Response.to_json())

# convert the object into a dict
system_geneve_name_get200_response_dict = system_geneve_name_get200_response_instance.to_dict()
# create an instance of SystemGeneveNameGet200Response from a dict
system_geneve_name_get200_response_from_dict = SystemGeneveNameGet200Response.from_dict(system_geneve_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


