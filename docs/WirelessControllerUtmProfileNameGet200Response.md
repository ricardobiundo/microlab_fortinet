# WirelessControllerUtmProfileNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | UTM profile name. | [optional] 
**comment** | **str** | Comment. | [optional] 
**utm_log** | **str** | Enable/disable UTM logging.    enable:Enable UTM logging.    disable:Disable UTM logging. | [optional] 
**ips_sensor** | **str** | IPS sensor name. | [optional] 
**application_list** | **str** | Application control list name. | [optional] 
**antivirus_profile** | **str** | AntiVirus profile name. | [optional] 
**webfilter_profile** | **str** | WebFilter profile name. | [optional] 
**scan_botnet_connections** | **str** | Block or monitor connections to Botnet servers or disable Botnet scanning.    disable:Do not scan connections to botnet servers.    monitor:Log connections to botnet servers.    block:Block connections to botnet servers. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_utm_profile_name_get200_response import WirelessControllerUtmProfileNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerUtmProfileNameGet200Response from a JSON string
wireless_controller_utm_profile_name_get200_response_instance = WirelessControllerUtmProfileNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerUtmProfileNameGet200Response.to_json())

# convert the object into a dict
wireless_controller_utm_profile_name_get200_response_dict = wireless_controller_utm_profile_name_get200_response_instance.to_dict()
# create an instance of WirelessControllerUtmProfileNameGet200Response from a dict
wireless_controller_utm_profile_name_get200_response_from_dict = WirelessControllerUtmProfileNameGet200Response.from_dict(wireless_controller_utm_profile_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


