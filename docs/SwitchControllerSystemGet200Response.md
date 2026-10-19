# SwitchControllerSystemGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**parallel_process_override** | **str** | Enable/disable parallel process override.    disable:Disable maximum parallel process override.    enable:Enable maximum parallel process override. | [optional] 
**parallel_process** | **int** | Maximum number of parallel processes. | [optional] 
**data_sync_interval** | **int** | Time interval between collection of switch data (30 - 1800 sec, default &#x3D; 60, 0 &#x3D; disable). | [optional] 
**iot_weight_threshold** | **int** | MAC entry&#39;s confidence value. Value is re-queried when below this value (default &#x3D; 1, 0 &#x3D; disable). | [optional] 
**iot_scan_interval** | **int** | IoT scan interval (2 - 10080 mins, default &#x3D; 60 mins, 0 &#x3D; disable). | [optional] 
**iot_holdoff** | **int** | MAC entry&#39;s creation time. Time must be greater than this value for an entry to be created (0 - 10080 mins, default &#x3D; 5 mins). | [optional] 
**iot_mac_idle** | **int** | MAC entry&#39;s idle time. MAC entry is removed after this value (0 - 10080 mins, default &#x3D; 1440 mins). | [optional] 
**nac_periodic_interval** | **int** | Periodic time interval to run NAC engine (5 - 180 sec, default &#x3D; 60). | [optional] 
**dynamic_periodic_interval** | **int** | Periodic time interval to run Dynamic port policy engine (5 - 180 sec, default &#x3D; 60). | [optional] 
**tunnel_mode** | **str** | Compatible/strict tunnel mode.    compatible:Least restrictive. Supports the lowest levels of security but highest compatibility between all FortiSwitch and FortiGate devices. 3rd party certificates permitted.    moderate:Moderate level of security. 3rd party certificates permitted.    strict:Highest level of security requirements. If enabled, the FortiGate device follows the same security mode requirements as in FIPS/CC mode. | [optional] 
**caputp_echo_interval** | **int** | Echo interval for the caputp echo requests from swtp. | [optional] 
**caputp_max_retransmit** | **int** | Maximum retransmission count for the caputp tunnel packets. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_system_get200_response import SwitchControllerSystemGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerSystemGet200Response from a JSON string
switch_controller_system_get200_response_instance = SwitchControllerSystemGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerSystemGet200Response.to_json())

# convert the object into a dict
switch_controller_system_get200_response_dict = switch_controller_system_get200_response_instance.to_dict()
# create an instance of SwitchControllerSystemGet200Response from a dict
switch_controller_system_get200_response_from_dict = SwitchControllerSystemGet200Response.from_dict(switch_controller_system_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


