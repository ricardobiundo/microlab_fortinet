# System3gModemCustomIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**vendor** | **str** | MODEM vendor name. | [optional] 
**model** | **str** | MODEM model name. | [optional] 
**vendor_id** | **str** | USB vendor ID in hexadecimal format (0000-ffff). | [optional] 
**product_id** | **str** | USB product ID in hexadecimal format (0000-ffff). | [optional] 
**class_id** | **str** | USB interface class in hexadecimal format (00-ff). | [optional] 
**init_string** | **str** | Init string in hexadecimal format (even length). | [optional] 
**modeswitch_string** | **str** | USB modeswitch arguments. For example: &#39;-v 1410 -p 9030 -V 1410 -P 9032 -u 3&#39;. | [optional] 

## Example

```python
from microlab_fortinet.models.system3g_modem_custom_id_get200_response import System3gModemCustomIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of System3gModemCustomIdGet200Response from a JSON string
system3g_modem_custom_id_get200_response_instance = System3gModemCustomIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(System3gModemCustomIdGet200Response.to_json())

# convert the object into a dict
system3g_modem_custom_id_get200_response_dict = system3g_modem_custom_id_get200_response_instance.to_dict()
# create an instance of System3gModemCustomIdGet200Response from a dict
system3g_modem_custom_id_get200_response_from_dict = System3gModemCustomIdGet200Response.from_dict(system3g_modem_custom_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


