# UserRadiusNameGet200ResponseAccountingServerInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID (0 - 4294967295). | [optional] 
**status** | **str** | Status.    enable:Log to remote syslog server.    disable:Do not log to remote syslog server. | [optional] 
**server** | **str** | Server CN domain name or IP address. | [optional] 
**secret** | **str** | Secret key. | [optional] 
**port** | **int** | RADIUS accounting port number. | [optional] 
**source_ip** | **str** | Source IP address for communications to the RADIUS server. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.user_radius_name_get200_response_accounting_server_inner import UserRadiusNameGet200ResponseAccountingServerInner

# TODO update the JSON string below
json = "{}"
# create an instance of UserRadiusNameGet200ResponseAccountingServerInner from a JSON string
user_radius_name_get200_response_accounting_server_inner_instance = UserRadiusNameGet200ResponseAccountingServerInner.from_json(json)
# print the JSON string representation of the object
print(UserRadiusNameGet200ResponseAccountingServerInner.to_json())

# convert the object into a dict
user_radius_name_get200_response_accounting_server_inner_dict = user_radius_name_get200_response_accounting_server_inner_instance.to_dict()
# create an instance of UserRadiusNameGet200ResponseAccountingServerInner from a dict
user_radius_name_get200_response_accounting_server_inner_from_dict = UserRadiusNameGet200ResponseAccountingServerInner.from_dict(user_radius_name_get200_response_accounting_server_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


