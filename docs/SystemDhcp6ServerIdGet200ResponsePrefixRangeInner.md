# SystemDhcp6ServerIdGet200ResponsePrefixRangeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**start_prefix** | **str** | Start of prefix range. | [optional] 
**end_prefix** | **str** | End of prefix range. | [optional] 
**prefix_length** | **int** | Prefix length. | [optional] 

## Example

```python
from microlab_fortinet.models.system_dhcp6_server_id_get200_response_prefix_range_inner import SystemDhcp6ServerIdGet200ResponsePrefixRangeInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemDhcp6ServerIdGet200ResponsePrefixRangeInner from a JSON string
system_dhcp6_server_id_get200_response_prefix_range_inner_instance = SystemDhcp6ServerIdGet200ResponsePrefixRangeInner.from_json(json)
# print the JSON string representation of the object
print(SystemDhcp6ServerIdGet200ResponsePrefixRangeInner.to_json())

# convert the object into a dict
system_dhcp6_server_id_get200_response_prefix_range_inner_dict = system_dhcp6_server_id_get200_response_prefix_range_inner_instance.to_dict()
# create an instance of SystemDhcp6ServerIdGet200ResponsePrefixRangeInner from a dict
system_dhcp6_server_id_get200_response_prefix_range_inner_from_dict = SystemDhcp6ServerIdGet200ResponsePrefixRangeInner.from_dict(system_dhcp6_server_id_get200_response_prefix_range_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


