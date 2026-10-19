# WirelessControllerLogGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Enable/disable wireless event logging.    enable:Enable wireless event logging.    disable:Disable wireless event logging. | [optional] 
**addrgrp_log** | **str** | Lowest severity level to log address group message.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 
**ble_log** | **str** | Lowest severity level to log BLE detection message.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 
**clb_log** | **str** | Lowest severity level to log client load balancing message.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 
**dhcp_starv_log** | **str** | Lowest severity level to log DHCP starvation event message.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 
**led_sched_log** | **str** | Lowest severity level to log LED schedule event message.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 
**radio_event_log** | **str** | Lowest severity level to log radio event message.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 
**rogue_event_log** | **str** | Lowest severity level to log rogue AP event message.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 
**sta_event_log** | **str** | Lowest severity level to log station event message.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 
**sta_locate_log** | **str** | Lowest severity level to log station locate message.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 
**wids_log** | **str** | Lowest severity level to log WIDS message.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 
**wtp_event_log** | **str** | Lowest severity level to log WTP event message.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 
**wtp_fips_event_log** | **str** | Lowest severity level to log FAP fips event message.    emergency:Emergency level.    alert:Alert level.    critical:Critical level.    error:Error level.    warning:Warning level.    notification:Notification level.    information:Information level.    debug:Debug level. | [optional] 

## Example

```python
from microlab_fortinet.models.wireless_controller_log_get200_response import WirelessControllerLogGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of WirelessControllerLogGet200Response from a JSON string
wireless_controller_log_get200_response_instance = WirelessControllerLogGet200Response.from_json(json)
# print the JSON string representation of the object
print(WirelessControllerLogGet200Response.to_json())

# convert the object into a dict
wireless_controller_log_get200_response_dict = wireless_controller_log_get200_response_instance.to_dict()
# create an instance of WirelessControllerLogGet200Response from a dict
wireless_controller_log_get200_response_from_dict = WirelessControllerLogGet200Response.from_dict(wireless_controller_log_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


