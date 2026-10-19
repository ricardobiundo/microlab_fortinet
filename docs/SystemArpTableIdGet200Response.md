# SystemArpTableIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique integer ID of the entry. | [optional] 
**interface** | **str** | Interface name. | [optional] 
**ip** | **str** | IP address. | [optional] 
**mac** | **str** | MAC address. | [optional] 

## Example

```python
from microlab_fortinet.models.system_arp_table_id_get200_response import SystemArpTableIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemArpTableIdGet200Response from a JSON string
system_arp_table_id_get200_response_instance = SystemArpTableIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemArpTableIdGet200Response.to_json())

# convert the object into a dict
system_arp_table_id_get200_response_dict = system_arp_table_id_get200_response_instance.to_dict()
# create an instance of SystemArpTableIdGet200Response from a dict
system_arp_table_id_get200_response_from_dict = SystemArpTableIdGet200Response.from_dict(system_arp_table_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


