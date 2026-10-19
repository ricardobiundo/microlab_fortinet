# UserTacacsNameGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | TACACS+ server entry name. | [optional] 
**server** | **str** | Primary TACACS+ server CN domain name or IP address. | [optional] 
**secondary_server** | **str** | Secondary TACACS+ server CN domain name or IP address. | [optional] 
**tertiary_server** | **str** | Tertiary TACACS+ server CN domain name or IP address. | [optional] 
**port** | **int** | Port number of the TACACS+ server. | [optional] 
**key** | **str** | Key to access the primary server. | [optional] 
**secondary_key** | **str** | Key to access the secondary server. | [optional] 
**tertiary_key** | **str** | Key to access the tertiary server. | [optional] 
**status_ttl** | **int** | Time for which server reachability is cached so that when a server is unreachable, it will not be retried for at least this period of time (0 &#x3D; cache disabled, default &#x3D; 300). | [optional] 
**authen_type** | **str** | Allowed authentication protocols/methods.    mschap:MSCHAP.    chap:CHAP.    pap:PAP.    ascii:ASCII.    auto:Use PAP, MSCHAP, and CHAP (in that order). | [optional] 
**authorization** | **str** | Enable/disable TACACS+ authorization.    enable:Enable TACACS+ authorization.    disable:Disable TACACS+ authorization. | [optional] 
**source_ip** | **str** | Source IP address for communications to TACACS+ server. | [optional] 
**interface_select_method** | **str** | Specify how to select outgoing interface to reach server.    auto:Set outgoing interface automatically.    sdwan:Set outgoing interface by SD-WAN or policy routing rules.    specify:Set outgoing interface manually. | [optional] 
**interface** | **str** | Specify outgoing interface to reach server. | [optional] 
**vrf_select** | **int** | VRF ID used for connection to server. | [optional] 

## Example

```python
from microlab_fortinet.models.user_tacacs_name_get200_response import UserTacacsNameGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UserTacacsNameGet200Response from a JSON string
user_tacacs_name_get200_response_instance = UserTacacsNameGet200Response.from_json(json)
# print the JSON string representation of the object
print(UserTacacsNameGet200Response.to_json())

# convert the object into a dict
user_tacacs_name_get200_response_dict = user_tacacs_name_get200_response_instance.to_dict()
# create an instance of UserTacacsNameGet200Response from a dict
user_tacacs_name_get200_response_from_dict = UserTacacsNameGet200Response.from_dict(user_tacacs_name_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


