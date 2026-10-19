# SwitchControllerQosIpDscpMapNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Dscp map name. | [optional] 
**description** | **str** | Description of the ip-dscp map name. | [optional] 
**map** | [**List[SwitchControllerQosIpDscpMapNameGet200ResponseMapInner]**](SwitchControllerQosIpDscpMapNameGet200ResponseMapInner.md) | Maps between IP-DSCP value to COS queue. | [optional] 

## Example

```python
from microlab_fortinet.models.switch_controller_qos_ip_dscp_map_name_get200_response import SwitchControllerQosIpDscpMapNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SwitchControllerQosIpDscpMapNameGet200Response from a JSON string
switch_controller_qos_ip_dscp_map_name_get200_response_instance = SwitchControllerQosIpDscpMapNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(SwitchControllerQosIpDscpMapNameGet200Response.to_json())

# convert the object into a dict
switch_controller_qos_ip_dscp_map_name_get200_response_dict = switch_controller_qos_ip_dscp_map_name_get200_response_instance.to_dict()
# create an instance of SwitchControllerQosIpDscpMapNameGet200Response from a dict
switch_controller_qos_ip_dscp_map_name_get200_response_from_dict = SwitchControllerQosIpDscpMapNameGet200Response.from_dict(switch_controller_qos_ip_dscp_map_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


