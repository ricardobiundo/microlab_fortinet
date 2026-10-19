# SystemPtpGet200ResponseServerInterfaceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID. | [optional] 
**server_interface_name** | **str** | Interface name. | [optional] 
**delay_mechanism** | **str** | End to end delay detection or peer to peer delay detection.    E2E:End to end delay detection.    P2P:Peer to peer delay detection. | [optional] 

## Example

```python
from microlab_fortinet.models.system_ptp_get200_response_server_interface_inner import SystemPtpGet200ResponseServerInterfaceInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemPtpGet200ResponseServerInterfaceInner from a JSON string
system_ptp_get200_response_server_interface_inner_instance = SystemPtpGet200ResponseServerInterfaceInner.from_json(json)
# print the JSON string representation of the object
print(SystemPtpGet200ResponseServerInterfaceInner.to_json())

# convert the object into a dict
system_ptp_get200_response_server_interface_inner_dict = system_ptp_get200_response_server_interface_inner_instance.to_dict()
# create an instance of SystemPtpGet200ResponseServerInterfaceInner from a dict
system_ptp_get200_response_server_interface_inner_from_dict = SystemPtpGet200ResponseServerInterfaceInner.from_dict(system_ptp_get200_response_server_interface_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


