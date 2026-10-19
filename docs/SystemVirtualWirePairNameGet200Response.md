# SystemVirtualWirePairNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Virtual-wire-pair name. Must be a unique interface name. | [optional] 
**member** | [**List[SystemAcmeGet200ResponseInterfaceInner]**](SystemAcmeGet200ResponseInterfaceInner.md) | Interfaces belong to the virtual-wire-pair. | [optional] 
**wildcard_vlan** | **str** | Enable/disable wildcard VLAN.    enable:Enable wildcard VLAN.    disable:Disable wildcard VLAN. | [optional] 
**vlan_filter** | **str** | VLAN ranges to allow | [optional] 

## Example

```python
from microlab_fortinet.models.system_virtual_wire_pair_name_get200_response import SystemVirtualWirePairNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemVirtualWirePairNameGet200Response from a JSON string
system_virtual_wire_pair_name_get200_response_instance = SystemVirtualWirePairNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemVirtualWirePairNameGet200Response.to_json())

# convert the object into a dict
system_virtual_wire_pair_name_get200_response_dict = system_virtual_wire_pair_name_get200_response_instance.to_dict()
# create an instance of SystemVirtualWirePairNameGet200Response from a dict
system_virtual_wire_pair_name_get200_response_from_dict = SystemVirtualWirePairNameGet200Response.from_dict(system_virtual_wire_pair_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


