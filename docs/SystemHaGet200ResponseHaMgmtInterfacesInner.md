# SystemHaGet200ResponseHaMgmtInterfacesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Table ID. | [optional] 
**interface** | **str** | Interface to reserve for HA management. | [optional] 
**dst** | **str** | Default route destination for reserved HA management interface. | [optional] 
**gateway** | **str** | Default route gateway for reserved HA management interface. | [optional] 
**dst6** | **str** | Default IPv6 destination for reserved HA management interface. | [optional] 
**gateway6** | **str** | Default IPv6 gateway for reserved HA management interface. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ha_get200_response_ha_mgmt_interfaces_inner import SystemHaGet200ResponseHaMgmtInterfacesInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemHaGet200ResponseHaMgmtInterfacesInner from a JSON string
system_ha_get200_response_ha_mgmt_interfaces_inner_instance = SystemHaGet200ResponseHaMgmtInterfacesInner.from_json(json)
# print the JSON string representation of the object
print(SystemHaGet200ResponseHaMgmtInterfacesInner.to_json())

# convert the object into a dict
system_ha_get200_response_ha_mgmt_interfaces_inner_dict = system_ha_get200_response_ha_mgmt_interfaces_inner_instance.to_dict()
# create an instance of SystemHaGet200ResponseHaMgmtInterfacesInner from a dict
system_ha_get200_response_ha_mgmt_interfaces_inner_from_dict = SystemHaGet200ResponseHaMgmtInterfacesInner.from_dict(system_ha_get200_response_ha_mgmt_interfaces_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


