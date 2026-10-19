# SystemSnmpRmonStatIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | RMON Ethernet statistics entry ID. | [optional] 
**source** | **str** | Data source of the Ethernet statistics entry. | [optional] 
**owner** | **str** | Owner of the Ethernet statistics entry. | [optional] 

## Example

```python
from microlab_fortinet.models.system_snmp_rmon_stat_id_get200_response import SystemSnmpRmonStatIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSnmpRmonStatIdGet200Response from a JSON string
system_snmp_rmon_stat_id_get200_response_instance = SystemSnmpRmonStatIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSnmpRmonStatIdGet200Response.to_json())

# convert the object into a dict
system_snmp_rmon_stat_id_get200_response_dict = system_snmp_rmon_stat_id_get200_response_instance.to_dict()
# create an instance of SystemSnmpRmonStatIdGet200Response from a dict
system_snmp_rmon_stat_id_get200_response_from_dict = SystemSnmpRmonStatIdGet200Response.from_dict(system_snmp_rmon_stat_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


