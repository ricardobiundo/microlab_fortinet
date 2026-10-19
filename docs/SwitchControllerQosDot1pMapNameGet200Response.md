# SwitchControllerQosDot1pMapNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Dot1p map name. | [optional] 
**description** | **str** | Description of the 802.1p name. | [optional] 
**egress_pri_tagging** | **str** | Enable/disable egress priority-tag frame.    disable:Disable egress priority tagging.    enable:Enable egress priority tagging. | [optional] 
**priority_0** | **str** | COS queue mapped to dot1p priority number.    queue-0:COS queue 0 (lowest priority).    queue-1:COS queue 1.    queue-2:COS queue 2.    queue-3:COS queue 3.    queue-4:COS queue 4.    queue-5:COS queue 5.    queue-6:COS queue 6.    queue-7:COS queue 7 (highest priority). | [optional] 
**priority_1** | **str** | COS queue mapped to dot1p priority number.    queue-0:COS queue 0 (lowest priority).    queue-1:COS queue 1.    queue-2:COS queue 2.    queue-3:COS queue 3.    queue-4:COS queue 4.    queue-5:COS queue 5.    queue-6:COS queue 6.    queue-7:COS queue 7 (highest priority). | [optional] 
**priority_2** | **str** | COS queue mapped to dot1p priority number.    queue-0:COS queue 0 (lowest priority).    queue-1:COS queue 1.    queue-2:COS queue 2.    queue-3:COS queue 3.    queue-4:COS queue 4.    queue-5:COS queue 5.    queue-6:COS queue 6.    queue-7:COS queue 7 (highest priority). | [optional] 
**priority_3** | **str** | COS queue mapped to dot1p priority number.    queue-0:COS queue 0 (lowest priority).    queue-1:COS queue 1.    queue-2:COS queue 2.    queue-3:COS queue 3.    queue-4:COS queue 4.    queue-5:COS queue 5.    queue-6:COS queue 6.    queue-7:COS queue 7 (highest priority). | [optional] 
**priority_4** | **str** | COS queue mapped to dot1p priority number.    queue-0:COS queue 0 (lowest priority).    queue-1:COS queue 1.    queue-2:COS queue 2.    queue-3:COS queue 3.    queue-4:COS queue 4.    queue-5:COS queue 5.    queue-6:COS queue 6.    queue-7:COS queue 7 (highest priority). | [optional] 
**priority_5** | **str** | COS queue mapped to dot1p priority number.    queue-0:COS queue 0 (lowest priority).    queue-1:COS queue 1.    queue-2:COS queue 2.    queue-3:COS queue 3.    queue-4:COS queue 4.    queue-5:COS queue 5.    queue-6:COS queue 6.    queue-7:COS queue 7 (highest priority). | [optional] 
**priority_6** | **str** | COS queue mapped to dot1p priority number.    queue-0:COS queue 0 (lowest priority).    queue-1:COS queue 1.    queue-2:COS queue 2.    queue-3:COS queue 3.    queue-4:COS queue 4.    queue-5:COS queue 5.    queue-6:COS queue 6.    queue-7:COS queue 7 (highest priority). | [optional] 
**priority_7** | **str** | COS queue mapped to dot1p priority number.    queue-0:COS queue 0 (lowest priority).    queue-1:COS queue 1.    queue-2:COS queue 2.    queue-3:COS queue 3.    queue-4:COS queue 4.    queue-5:COS queue 5.    queue-6:COS queue 6.    queue-7:COS queue 7 (highest priority). | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_qos_dot1p_map_name_get200_response import SwitchControllerQosDot1pMapNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerQosDot1pMapNameGet200Response from a JSON string
switch_controller_qos_dot1p_map_name_get200_response_instance = SwitchControllerQosDot1pMapNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerQosDot1pMapNameGet200Response.to_json())

# convert the object into a dict
switch_controller_qos_dot1p_map_name_get200_response_dict = switch_controller_qos_dot1p_map_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerQosDot1pMapNameGet200Response from a dict
switch_controller_qos_dot1p_map_name_get200_response_from_dict = SwitchControllerQosDot1pMapNameGet200Response.from_dict(switch_controller_qos_dot1p_map_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


