# SystemSdnConnectorNameGet200ResponseGcpProjectListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | GCP project ID. | [optional] 
**gcp_zone_list** | [**List[SystemSdnConnectorNameGet200ResponseGcpProjectListInnerGcpZoneListInner]**](SystemSdnConnectorNameGet200ResponseGcpProjectListInnerGcpZoneListInner.md) | Configure GCP zone list. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdn_connector_name_get200_response_gcp_project_list_inner import SystemSdnConnectorNameGet200ResponseGcpProjectListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdnConnectorNameGet200ResponseGcpProjectListInner from a JSON string
system_sdn_connector_name_get200_response_gcp_project_list_inner_instance = SystemSdnConnectorNameGet200ResponseGcpProjectListInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdnConnectorNameGet200ResponseGcpProjectListInner.to_json())

# convert the object into a dict
system_sdn_connector_name_get200_response_gcp_project_list_inner_dict = system_sdn_connector_name_get200_response_gcp_project_list_inner_instance.to_dict()
# create an instance of SystemSdnConnectorNameGet200ResponseGcpProjectListInner from a dict
system_sdn_connector_name_get200_response_gcp_project_list_inner_from_dict = SystemSdnConnectorNameGet200ResponseGcpProjectListInner.from_dict(system_sdn_connector_name_get200_response_gcp_project_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


