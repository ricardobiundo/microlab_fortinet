# SystemLteModemGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable USB LTE/WIMAX device.    enable:Enable USB LTE/WIMA device.    disable:Disable USB LTE/WIMA device. | [optional] 
**extra_init** | **str** | Extra initialization string for USB LTE/WIMAX devices. | [optional] 
**pdptype** | **str** | Packet Data Protocol (PDP) context type.    IPv4:Only IPv4. | [optional] 
**authtype** | **str** | Authentication type for PDP-IP packet data calls.    none:Username and password not required.    pap:Use PAP authentication.    chap:Use CHAP authentication. | [optional] 
**username** | **str** | Authentication username for PDP-IP packet data calls. | [optional] 
**passwd** | **str** | Authentication password for PDP-IP packet data calls. | [optional] 
**apn** | **str** | Login APN string for PDP-IP packet data calls. | [optional] 
**modem_port** | **int** | Modem port index (0 - 20). | [optional] 

## Example

```python
from microlab_fortinet.models.system_lte_modem_get200_response import SystemLteModemGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SystemLteModemGet200Response from a JSON string
system_lte_modem_get200_response_instance = SystemLteModemGet200Response.from_json(json)
# print the JSON string representation of the object
print(SystemLteModemGet200Response.to_json())

# convert the object into a dict
system_lte_modem_get200_response_dict = system_lte_modem_get200_response_instance.to_dict()
# create an instance of SystemLteModemGet200Response from a dict
system_lte_modem_get200_response_from_dict = SystemLteModemGet200Response.from_dict(system_lte_modem_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


