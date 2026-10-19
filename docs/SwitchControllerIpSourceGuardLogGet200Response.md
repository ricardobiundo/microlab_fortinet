# SwitchControllerIpSourceGuardLogGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**log_violations** | **str** | Enable/Disable log violations for IP source guard logging.    enable:Enable log violations for IP source guard logging.    disable:Disable log violations for IP source guard logging. | [optional] 
**violation_timer** | **int** | IP source gurad log violation timer in seconds (0 - 1500, default &#x3D; 0). | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_ip_source_guard_log_get200_response import SwitchControllerIpSourceGuardLogGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerIpSourceGuardLogGet200Response from a JSON string
switch_controller_ip_source_guard_log_get200_response_instance = SwitchControllerIpSourceGuardLogGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerIpSourceGuardLogGet200Response.to_json())

# convert the object into a dict
switch_controller_ip_source_guard_log_get200_response_dict = switch_controller_ip_source_guard_log_get200_response_instance.to_dict()
# create an instance of SwitchControllerIpSourceGuardLogGet200Response from a dict
switch_controller_ip_source_guard_log_get200_response_from_dict = SwitchControllerIpSourceGuardLogGet200Response.from_dict(switch_controller_ip_source_guard_log_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


