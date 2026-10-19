# SystemSdnConnectorNameGet200ResponseNicInnerIpInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | IP configuration name. | [optional] 
**private_ip** | **str** | Private IP address. | [optional] 
**public_ip** | **str** | Public IP name. | [optional] 
**resource_group** | **str** | Resource group of Azure public IP. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdn_connector_name_get200_response_nic_inner_ip_inner import SystemSdnConnectorNameGet200ResponseNicInnerIpInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdnConnectorNameGet200ResponseNicInnerIpInner from a JSON string
system_sdn_connector_name_get200_response_nic_inner_ip_inner_instance = SystemSdnConnectorNameGet200ResponseNicInnerIpInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdnConnectorNameGet200ResponseNicInnerIpInner.to_json())

# convert the object into a dict
system_sdn_connector_name_get200_response_nic_inner_ip_inner_dict = system_sdn_connector_name_get200_response_nic_inner_ip_inner_instance.to_dict()
# create an instance of SystemSdnConnectorNameGet200ResponseNicInnerIpInner from a dict
system_sdn_connector_name_get200_response_nic_inner_ip_inner_from_dict = SystemSdnConnectorNameGet200ResponseNicInnerIpInner.from_dict(system_sdn_connector_name_get200_response_nic_inner_ip_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


