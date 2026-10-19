# SystemInterfaceNameGet200ResponseL2tpClientSettingsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user** | **str** | L2TP user name. | [optional] 
**password** | **str** | L2TP password. | [optional] 
**peer_host** | **str** | L2TP peer host address. | [optional] 
**peer_mask** | **str** | L2TP peer mask. | [optional] 
**peer_port** | **int** | L2TP peer port number. | [optional] 
**auth_type** | **str** | L2TP authentication type.    auto:Automatically choose authentication.    pap:PAP authentication.    chap:CHAP authentication.    mschapv1:MS-CHAPv1 authentication.    mschapv2:MS-CHAPv2 authentication. | [optional] 
**mtu** | **int** | L2TP MTU. | [optional] 
**distance** | **int** | Distance of learned routes. | [optional] 
**priority** | **int** | Priority of learned routes. | [optional] 
**defaultgw** | **str** | Enable/disable default gateway.    enable:Enable default gateway.    disable:Disable default gateway. | [optional] 
**ip** | **str** | IP. | [optional] 
**hello_interval** | **int** | L2TP hello message interval in seconds (0 - 3600 sec, default &#x3D; 60). | [optional] 

## Example

```python
from microlab_fortinet.models.system_interface_name_get200_response_l2tp_client_settings_inner import SystemInterfaceNameGet200ResponseL2tpClientSettingsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SystemInterfaceNameGet200ResponseL2tpClientSettingsInner from a JSON string
system_interface_name_get200_response_l2tp_client_settings_inner_instance = SystemInterfaceNameGet200ResponseL2tpClientSettingsInner.from_json(json)
# print the JSON string representation of the object
print(SystemInterfaceNameGet200ResponseL2tpClientSettingsInner.to_json())

# convert the object into a dict
system_interface_name_get200_response_l2tp_client_settings_inner_dict = system_interface_name_get200_response_l2tp_client_settings_inner_instance.to_dict()
# create an instance of SystemInterfaceNameGet200ResponseL2tpClientSettingsInner from a dict
system_interface_name_get200_response_l2tp_client_settings_inner_from_dict = SystemInterfaceNameGet200ResponseL2tpClientSettingsInner.from_dict(system_interface_name_get200_response_l2tp_client_settings_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


