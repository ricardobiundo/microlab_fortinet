# SystemSdnConnectorNameGet200ResponseExternalAccountListInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**role_arn** | **str** | AWS role ARN to assume. | [optional] 
**external_id** | **str** | AWS external ID. | [optional] 
**region_list** | [**List[SystemSdnConnectorNameGet200ResponseExternalAccountListInnerRegionListInner]**](SystemSdnConnectorNameGet200ResponseExternalAccountListInnerRegionListInner.md) | AWS region name list. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdn_connector_name_get200_response_external_account_list_inner import SystemSdnConnectorNameGet200ResponseExternalAccountListInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdnConnectorNameGet200ResponseExternalAccountListInner from a JSON string
system_sdn_connector_name_get200_response_external_account_list_inner_instance = SystemSdnConnectorNameGet200ResponseExternalAccountListInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdnConnectorNameGet200ResponseExternalAccountListInner.to_json())

# convert the object into a dict
system_sdn_connector_name_get200_response_external_account_list_inner_dict = system_sdn_connector_name_get200_response_external_account_list_inner_instance.to_dict()
# create an instance of SystemSdnConnectorNameGet200ResponseExternalAccountListInner from a dict
system_sdn_connector_name_get200_response_external_account_list_inner_from_dict = SystemSdnConnectorNameGet200ResponseExternalAccountListInner.from_dict(system_sdn_connector_name_get200_response_external_account_list_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


