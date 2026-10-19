# SystemMobileTunnelNameGet200ResponseNetworkInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Network entry ID. | [optional] 
**interface** | **str** | Select the associated interface name from available options. | [optional] 
**prefix** | **str** | Class IP and Netmask with correction (Format:xxx.xxx.xxx.xxx xxx.xxx.xxx.xxx or xxx.xxx.xxx.xxx/x). | [optional] 

## Example

```python
from microlab_fortinet.models.system_mobile_tunnel_name_get200_response_network_inner import SystemMobileTunnelNameGet200ResponseNetworkInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemMobileTunnelNameGet200ResponseNetworkInner from a JSON string
system_mobile_tunnel_name_get200_response_network_inner_instance = SystemMobileTunnelNameGet200ResponseNetworkInner.from_json(json)
# print the JSON string representation of the object
print(SystemMobileTunnelNameGet200ResponseNetworkInner.to_json())

# convert the object into a dict
system_mobile_tunnel_name_get200_response_network_inner_dict = system_mobile_tunnel_name_get200_response_network_inner_instance.to_dict()
# create an instance of SystemMobileTunnelNameGet200ResponseNetworkInner from a dict
system_mobile_tunnel_name_get200_response_network_inner_from_dict = SystemMobileTunnelNameGet200ResponseNetworkInner.from_dict(system_mobile_tunnel_name_get200_response_network_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


