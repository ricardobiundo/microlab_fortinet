# SwitchControllerQosIpDscpMapNameGet200ResponseMapInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Dscp mapping entry name. | [optional] 
**cos_queue** | **int** | COS queue number. | [optional] 
**diffserv** | **str** | Differentiated service.    CS0:DSCP CS0.    CS1:DSCP CS1.    AF11:DSCP AF11.    AF12:DSCP AF12.    AF13:DSCP AF13.    CS2:DSCP CS2.    AF21:DSCP AF21.    AF22:DSCP AF22.    AF23:DSCP AF23.    CS3:DSCP CS3.    AF31:DSCP AF31.    AF32:DSCP AF32.    AF33:DSCP AF33.    CS4:DSCP CS4.    AF41:DSCP AF41.    AF42:DSCP AF42.    AF43:DSCP AF43.    CS5:DSCP CS5.    EF:DSCP EF.    CS6:DSCP CS6.    CS7:DSCP CS7. | [optional] 
**ip_precedence** | **str** | IP Precedence.    network-control:Network control.    internetwork-control:Internetwork control.    critic-ecp:Critic ECP.    flashoverride:Flash override.    flash:Flash.    immediate:Immediate.    priority:Priority.    routine:Routine. | [optional] 
**value** | **str** | Raw values of DSCP (0 - 63). | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_qos_ip_dscp_map_name_get200_response_map_inner import SwitchControllerQosIpDscpMapNameGet200ResponseMapInner

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerQosIpDscpMapNameGet200ResponseMapInner from a JSON string
switch_controller_qos_ip_dscp_map_name_get200_response_map_inner_instance = SwitchControllerQosIpDscpMapNameGet200ResponseMapInner.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerQosIpDscpMapNameGet200ResponseMapInner.to_json())

# convert the object into a dict
switch_controller_qos_ip_dscp_map_name_get200_response_map_inner_dict = switch_controller_qos_ip_dscp_map_name_get200_response_map_inner_instance.to_dict()
# create an instance of SwitchControllerQosIpDscpMapNameGet200ResponseMapInner from a dict
switch_controller_qos_ip_dscp_map_name_get200_response_map_inner_from_dict = SwitchControllerQosIpDscpMapNameGet200ResponseMapInner.from_dict(switch_controller_qos_ip_dscp_map_name_get200_response_map_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


