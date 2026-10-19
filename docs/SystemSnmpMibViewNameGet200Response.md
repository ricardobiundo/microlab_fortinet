# SystemSnmpMibViewNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | MIB view name. | [optional] 
**include** | **str** | OID subtrees to be included in the view. Maximum 16 allowed. | [optional] 
**exclude** | **str** | OID subtrees to be excluded in the view. Maximum 64 allowed. | [optional] 

## Example

```python
from microlab_fortinet.models.system_snmp_mib_view_name_get200_response import SystemSnmpMibViewNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemSnmpMibViewNameGet200Response from a JSON string
system_snmp_mib_view_name_get200_response_instance = SystemSnmpMibViewNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemSnmpMibViewNameGet200Response.to_json())

# convert the object into a dict
system_snmp_mib_view_name_get200_response_dict = system_snmp_mib_view_name_get200_response_instance.to_dict()
# create an instance of SystemSnmpMibViewNameGet200Response from a dict
system_snmp_mib_view_name_get200_response_from_dict = SystemSnmpMibViewNameGet200Response.from_dict(system_snmp_mib_view_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


