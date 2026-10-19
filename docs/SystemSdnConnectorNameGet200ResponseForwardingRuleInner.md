# SystemSdnConnectorNameGet200ResponseForwardingRuleInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rule_name** | **str** | Forwarding rule name. | [optional] 
**target** | **str** | Target instance name. | [optional] 

## Example

```python
from microlab_fortinet.models.system_sdn_connector_name_get200_response_forwarding_rule_inner import SystemSdnConnectorNameGet200ResponseForwardingRuleInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSdnConnectorNameGet200ResponseForwardingRuleInner from a JSON string
system_sdn_connector_name_get200_response_forwarding_rule_inner_instance = SystemSdnConnectorNameGet200ResponseForwardingRuleInner.from_json(json)
# print the JSON string representation of the object
print(SystemSdnConnectorNameGet200ResponseForwardingRuleInner.to_json())

# convert the object into a dict
system_sdn_connector_name_get200_response_forwarding_rule_inner_dict = system_sdn_connector_name_get200_response_forwarding_rule_inner_instance.to_dict()
# create an instance of SystemSdnConnectorNameGet200ResponseForwardingRuleInner from a dict
system_sdn_connector_name_get200_response_forwarding_rule_inner_from_dict = SystemSdnConnectorNameGet200ResponseForwardingRuleInner.from_dict(system_sdn_connector_name_get200_response_forwarding_rule_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


