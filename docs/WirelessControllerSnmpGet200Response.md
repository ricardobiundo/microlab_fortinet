# WirelessControllerSnmpGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**engine_id** | **str** | AC SNMP engineID string (maximum 24 characters). | [optional] 
**contact_info** | **str** | Contact Information. | [optional] 
**trap_high_cpu_threshold** | **int** | CPU usage when trap is sent. | [optional] 
**trap_high_mem_threshold** | **int** | Memory usage when trap is sent. | [optional] 
**community** | [**List[WirelessControllerSnmpGet200ResponseCommunityInner]**](WirelessControllerSnmpGet200ResponseCommunityInner.md) | SNMP Community Configuration. | [optional] 
**user** | [**List[WirelessControllerSnmpGet200ResponseUserInner]**](WirelessControllerSnmpGet200ResponseUserInner.md) | SNMP User Configuration. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_snmp_get200_response import WirelessControllerSnmpGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerSnmpGet200Response from a JSON string
wireless_controller_snmp_get200_response_instance = WirelessControllerSnmpGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerSnmpGet200Response.to_json())

# convert the object into a dict
wireless_controller_snmp_get200_response_dict = wireless_controller_snmp_get200_response_instance.to_dict()
# create an instance of WirelessControllerSnmpGet200Response from a dict
wireless_controller_snmp_get200_response_from_dict = WirelessControllerSnmpGet200Response.from_dict(wireless_controller_snmp_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


