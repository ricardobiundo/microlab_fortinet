# SystemIpsecAggregateNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | IPsec aggregate name. | [optional] 
**member** | [**List[SystemIpsecAggregateNameGet200ResponseMemberInner]**](SystemIpsecAggregateNameGet200ResponseMemberInner.md) | Member tunnels of the aggregate. | [optional] 
**algorithm** | **str** | Frame distribution algorithm.    L3:Use layer 3 address for distribution.    L4:Use layer 4 information for distribution.    round-robin:Per-packet round-robin distribution.    redundant:Use first tunnel that is up for all traffic.    weighted-round-robin:Weighted round-robin distribution. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ipsec_aggregate_name_get200_response import SystemIpsecAggregateNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemIpsecAggregateNameGet200Response from a JSON string
system_ipsec_aggregate_name_get200_response_instance = SystemIpsecAggregateNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemIpsecAggregateNameGet200Response.to_json())

# convert the object into a dict
system_ipsec_aggregate_name_get200_response_dict = system_ipsec_aggregate_name_get200_response_instance.to_dict()
# create an instance of SystemIpsecAggregateNameGet200Response from a dict
system_ipsec_aggregate_name_get200_response_from_dict = SystemIpsecAggregateNameGet200Response.from_dict(system_ipsec_aggregate_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


