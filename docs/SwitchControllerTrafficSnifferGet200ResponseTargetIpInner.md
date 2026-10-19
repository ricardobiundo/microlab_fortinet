# SwitchControllerTrafficSnifferGet200ResponseTargetIpInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip** | **str** | Sniffer IP. | [optional] 
**description** | **str** | Description for the sniffer IP. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_traffic_sniffer_get200_response_target_ip_inner import SwitchControllerTrafficSnifferGet200ResponseTargetIpInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerTrafficSnifferGet200ResponseTargetIpInner from a JSON string
switch_controller_traffic_sniffer_get200_response_target_ip_inner_instance = SwitchControllerTrafficSnifferGet200ResponseTargetIpInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerTrafficSnifferGet200ResponseTargetIpInner.to_json())

# convert the object into a dict
switch_controller_traffic_sniffer_get200_response_target_ip_inner_dict = switch_controller_traffic_sniffer_get200_response_target_ip_inner_instance.to_dict()
# create an instance of SwitchControllerTrafficSnifferGet200ResponseTargetIpInner from a dict
switch_controller_traffic_sniffer_get200_response_target_ip_inner_from_dict = SwitchControllerTrafficSnifferGet200ResponseTargetIpInner.from_dict(switch_controller_traffic_sniffer_get200_response_target_ip_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


