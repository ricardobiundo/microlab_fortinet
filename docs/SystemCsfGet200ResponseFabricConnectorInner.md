# SystemCsfGet200ResponseFabricConnectorInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**serial** | **str** | Serial. | [optional] 
**accprofile** | **str** | Override access profile. | [optional] 
**configuration_write_access** | **str** | Enable/disable downstream device write access to configuration.    enable:Enable downstream device write access to configuration.    disable:Disable downstream device write access to configuration. | [optional] 
**vdom** | [**List[SystemAdminNameGet200ResponseVdomInner]**](SystemAdminNameGet200ResponseVdomInner.md) | Virtual domains that the connector has access to. If none are set, the connector will only have access to the VDOM that it joins the Security Fabric through. | [optional] 

## Example

```python
from microlab_fortinet.models.system_csf_get200_response_fabric_connector_inner import SystemCsfGet200ResponseFabricConnectorInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemCsfGet200ResponseFabricConnectorInner from a JSON string
system_csf_get200_response_fabric_connector_inner_instance = SystemCsfGet200ResponseFabricConnectorInner.from_json(json)
# print the JSON string representation of the object
print(SystemCsfGet200ResponseFabricConnectorInner.to_json())

# convert the object into a dict
system_csf_get200_response_fabric_connector_inner_dict = system_csf_get200_response_fabric_connector_inner_instance.to_dict()
# create an instance of SystemCsfGet200ResponseFabricConnectorInner from a dict
system_csf_get200_response_fabric_connector_inner_from_dict = SystemCsfGet200ResponseFabricConnectorInner.from_dict(system_csf_get200_response_fabric_connector_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


