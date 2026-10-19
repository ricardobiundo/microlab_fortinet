# SystemSdnConnectorNameGet200ResponseNicInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Network interface name. | [optional] 
**peer_nic** | **str** | Peer network interface name. | [optional] 
**ip** | [**List[SystemSdnConnectorNameGet200ResponseNicInnerIpInner]**](SystemSdnConnectorNameGet200ResponseNicInnerIpInner.md) | Configure IP configuration. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdn_connector_name_get200_response_nic_inner import SystemSdnConnectorNameGet200ResponseNicInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdnConnectorNameGet200ResponseNicInner from a JSON string
system_sdn_connector_name_get200_response_nic_inner_instance = SystemSdnConnectorNameGet200ResponseNicInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdnConnectorNameGet200ResponseNicInner.to_json())

# convert the object into a dict
system_sdn_connector_name_get200_response_nic_inner_dict = system_sdn_connector_name_get200_response_nic_inner_instance.to_dict()
# create an instance of SystemSdnConnectorNameGet200ResponseNicInner from a dict
system_sdn_connector_name_get200_response_nic_inner_from_dict = SystemSdnConnectorNameGet200ResponseNicInner.from_dict(system_sdn_connector_name_get200_response_nic_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


