# SystemSdnConnectorNameGet200ResponseRouteTableInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Route table name. | [optional] 
**subscription_id** | **str** | Subscription ID of Azure route table. | [optional] 
**resource_group** | **str** | Resource group of Azure route table. | [optional] 
**route** | [**List[SystemSdnConnectorNameGet200ResponseRouteTableInnerRouteInner]**](SystemSdnConnectorNameGet200ResponseRouteTableInnerRouteInner.md) | Configure Azure route. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdn_connector_name_get200_response_route_table_inner import SystemSdnConnectorNameGet200ResponseRouteTableInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdnConnectorNameGet200ResponseRouteTableInner from a JSON string
system_sdn_connector_name_get200_response_route_table_inner_instance = SystemSdnConnectorNameGet200ResponseRouteTableInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdnConnectorNameGet200ResponseRouteTableInner.to_json())

# convert the object into a dict
system_sdn_connector_name_get200_response_route_table_inner_dict = system_sdn_connector_name_get200_response_route_table_inner_instance.to_dict()
# create an instance of SystemSdnConnectorNameGet200ResponseRouteTableInner from a dict
system_sdn_connector_name_get200_response_route_table_inner_from_dict = SystemSdnConnectorNameGet200ResponseRouteTableInner.from_dict(system_sdn_connector_name_get200_response_route_table_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


